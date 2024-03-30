# Файлы и каталоги в Linux.


Команда ls выводит содержимое каталога. 

Команда ls сначала выводит список всех файлов (не каталогов), перечисленных в командной строке, а затем выводит список всех файлов, находящихся в каталогах, перечисленных в командной строке.

## 1. Продемонстрируйте и прокомментируйте использование опций –d, -i, -t, -r команды ls.

_опция –d_ 

Опция -d заставляет ls не считать аргументы-каталоги каталогами. Будут отображаться только файлы, которые не начинаются с «.» или все файлы, если задана опция -a. Где «.» текущий каталог

Пример: 

![-d](https://sun9-32.userapi.com/impg/t0pS-7RPs3UeP_oj59v86M2blTnQw9z4BpXKqg/CU0dDUXVzUg.jpg?size=518x116&quality=95&sign=32406117727bf85b1e4d2eedcf0ba828&type=album) 

_опция -i_ 

Когда указана опция -l, то перед каждым списком выводится итоговая строка с общим размером всех файлов в списке, который измеряется в полу-килобайтах (512 байт). 

Пример: 

![-i](https://sun9-58.userapi.com/impg/iKCUOWUjvYgtQpO50iBKWt1ao5UH5RHaZUljpA/LFsy1de6zHI.jpg?size=577x77&quality=95&sign=01907c341723283dbca9740eaf483b2a&type=album)

_опция -t_ 

Опция -t - позволяет сортировать по показываемому временному штампу. 

Пример: На примере видно, как меняется сортировка -i и -t

![-t](https://sun3-23.userapi.com/impg/sAsKkZzfk4APo1yQjb4EscoCWr_Qm94vZ7E9Pw/wCF3sEPSFWc.jpg?size=587x131&quality=95&sign=79c7fdf4d64fa53f83fd3555a86c2bc9&type=album)

_опция -r_ 

Опция -r - производить сортировку в обратном порядке. 

Пример: На примере видно, как меняется сортировка -t и -r

![-r](https://sun9-34.userapi.com/impg/JZ9lIas_-ronDvu-CPjqFqmfgbWFmNflymLLpA/AlKqV6IoZYo.jpg?size=519x107&quality=95&sign=7408e07042eeb625a5178c6736c3f804&type=album)

## 2. Продемонстрируйте и прокомментируйте использование опций –v, -w, -I, -S команды ls.

_опция –v_ 

Опция -v - производить сортировку в соответствии с номером версии файлов. При этом учитывается, что имена файлов часто содержат номера версий или порядковые номера. 

Пример: Интересно, что в данном примере сортировка -t и -v совпадают.

![-v](https://sun9-56.userapi.com/impg/J-Elw2OBF4gVBbC0l0KxLAmWu0X5y56MCrtefA/pgpS7EANe_o.jpg?size=524x166&quality=95&sign=b1818d509b4917bde8d364361bcef11a&type=album)

_опция -w_ 

Опция -w, --width cols - назначает вывод на экран в cols колонок. По умолчанию, если это возможно, данное значение определяется из параметров драйвера терминала; в противном случае используется значение переменной окружения COLUMNS, если она установлена; в противном случае, по умолчанию, устанавливается 80.

Пример: 

![-w](https://sun9-50.userapi.com/impg/D9_YOh3ZdO8Az2taP68onO-O-ZeAgV-t1aV5ig/uD8G0vJz3zY.jpg?size=812x222&quality=95&sign=fa63ac13be8be790806a670c932ad852&type=album)

_опция -I_  

Опция -I, --ignore=шаблон - не показывать файлы, имена которых совпадают с заданным шаблоном (шаблон - это не регулярное выражение), если только они не заданы в командной строке. 
Начальная «.» в имени файла не совпадает с символом «*», заданным в начале шаблона. Где «.» текущий каталог. 

Пример: 

![-I](https://sun9-74.userapi.com/impg/pozSmxqV2FOAzG-qn-sCaG5rHWIGG1ZIcJYleg/U82WH3W0iFQ.jpg?size=883x112&quality=95&sign=1c665f4af96b9dabcf699cb038b131ce&type=album)

_опция -S_ 

Опция -S, --sort=size - производить сортировку по размеру файла, вместо сортировки по алфавиту. Сначала будут показаны наибольшие файлы

Пример: 

![-S](https://sun9-66.userapi.com/impg/mSXlG6V-uPgI4BWpHx-nQllahOlqpBpr18Mo-Q/z70YVzScVOI.jpg?size=868x98&quality=95&sign=f27811150137f07764bb5b414edfee5b&type=album)

## 3. Продемонстрируйте и прокомментируйте использование опций –R, -F, -A, -v команды ls.

_опция –R_

Опция -R, --recursive - рекурсивно выдает список содержимого всех каталогов.

Пример: 

![-R](https://sun9-77.userapi.com/impg/KIr_p4-FFLhWpAU3Iac8hJPosgxpRE_jZlX-vg/QvFxIZNndyw.jpg?size=865x368&quality=95&sign=a2cf5f3f130e1af3bfe83cc6804b321e&type=album)

_опция -F_

Опция -F, --classify, --indicator-style=classify - добавляет к каждому имени файла символ, показывающий его тип. Для обычных исполняемых файлов это «*». Для каталога добавляется «/», для FIFO – «|», для символических ссылок «@», для сокетов «=», для обычных файлов ничего не добавляется.

Пример: 

![-F](https://sun9-30.userapi.com/impg/kmwUSDZO5d1NawAQCZ-W2kxVFUT4N8nXArY1HQ/2xTLbhAN5_s.jpg?size=1366x152&quality=95&sign=016b9feee98bd5a309b17aa96dce9aa1&type=album)

_опция -A_

Опция -A, --almost-all - выдаваст все файлы, кроме «.» и «..»;

Пример: 

![-A](https://sun9-30.userapi.com/impg/kmwUSDZO5d1NawAQCZ-W2kxVFUT4N8nXArY1HQ/2xTLbhAN5_s.jpg?size=1366x152&quality=95&sign=016b9feee98bd5a309b17aa96dce9aa1&type=album)

_опция –v_ 

Уже была, но можно повторить и сравнить теперь с тем, как выдает функция -F

Опция -v - производить сортировку в соответствии с номером версии файлов. При этом учитывается, что имена файлов часто содержат номера версий или порядковые номера. 

Пример: 

![-v](https://sun9-30.userapi.com/impg/kmwUSDZO5d1NawAQCZ-W2kxVFUT4N8nXArY1HQ/2xTLbhAN5_s.jpg?size=1366x152&quality=95&sign=016b9feee98bd5a309b17aa96dce9aa1&type=album)

## 4. Продемонстрируйте и прокомментируйте использование опций –X, -C, --full-time, -h команды ls.

_опция -X_ 

Опция -X, --sort=extension - производить сортировку в алфавитном порядке по расширениям файлов (символы после последней точки «.»). Файлы без расширений будут показаны первыми.

Пример: 

![-X](https://sun9-17.userapi.com/impg/S8i2qv-cRKG6sskTy7F7Zh4bQfhkBqNWy5usjw/rz7BkpD2teU.jpg?size=870x315&quality=95&sign=060daa5b8eb620f953eae1a6b6f4a87d&type=album)

_опция -C_

Опция -C, --format=vertical - будет выдавать файлы в многоколоночном режиме, с сортировкой по вертикали. Опция устанавливается по умолчанию, если стандартный вывод является терминалом. 

Пример: 

![-C](https://sun9-17.userapi.com/impg/S8i2qv-cRKG6sskTy7F7Zh4bQfhkBqNWy5usjw/rz7BkpD2teU.jpg?size=870x315&quality=95&sign=060daa5b8eb620f953eae1a6b6f4a87d&type=album)

_опция --full-time_

Опция --full-time - будет выдавать время в полном, а не в стандартном сокращенном варианте.

Пример: В этой подборке опций, данная самая интересная, можно увидеть права доступа, для пользователя, группы и других.

![текст](https://sun9-17.userapi.com/impg/S8i2qv-cRKG6sskTy7F7Zh4bQfhkBqNWy5usjw/rz7BkpD2teU.jpg?size=870x315&quality=95&sign=060daa5b8eb620f953eae1a6b6f4a87d&type=album)

_опция -h_

Опция -h, --human-readable - добавит к каждому размеру файла букву размера, например, M для двоичных мегабайт. 

Пример: Но все пустое, видимо поэтому, мы размеры не увидем.

![-h](https://sun9-17.userapi.com/impg/S8i2qv-cRKG6sskTy7F7Zh4bQfhkBqNWy5usjw/rz7BkpD2teU.jpg?size=870x315&quality=95&sign=060daa5b8eb620f953eae1a6b6f4a87d&type=album)

## 5. Для чего предназначена команда pwd?

pwd - (present working directory — текущий рабочий каталог; или print working directory — вывести рабочий каталог) — консольная утилита в UNIX-подобных системах, которая выводит полный путь от корневого каталога к текущему рабочему каталогу: в контексте которого (по умолчанию) будут исполняться вводимые команды.

Т.е. Чтобы узнать, где находится пользователь в дереве каталогов, (название текущей папки), нужно ввести команду «pwd». Это позволит вывести название текущей папки на экран.

Пример: 

![pwd](https://sun9-68.userapi.com/impg/BkAJQtCSFMhyI8Z8XrxWAczcyJpG_1YwUz3kjA/cWRbzjDs40Q.jpg?size=323x42&quality=95&sign=0e777e6da7780fcf3b5d98246537566d&type=album)

## 6. Для чего предназначена команда cd? Как её использовать? Что делает команда cd ~?

В каждом созданном каталоге могут быть файлы или другие каталоги. Чтобы не вводить длинные имена файлов, можно сделать текущий каталог с помощью команды cd [полное_имя_каталога]. Команда cd ~ возвращает домашний каталог пользователя в качестве текущего каталога из любого каталога. 

Команда cd без параметров эквивалентна cd ~. Команда cd .. делает родительский каталог текущим.

Пример: Гулять можно почти по всем директория. Но в root и в восстановленные /lost+found так просто не зайти.

![cd](https://sun9-22.userapi.com/impg/Iw_ohPxkg1meaOhfFt0G7rOCEtilIpOIQhvZkw/x2lwyFf_wE4.jpg?size=1576x350&quality=95&sign=2b0dd247dc35565b9c138dcc2ca4eb87&type=album)

## 7. Команда rm

Команда rm удаляет файлы. 

Пример: Можно создать фаил через nano и удалить командой rm

![rm](https://sun9-64.userapi.com/impg/atU81Lpgg387kVQhChgYNldHXZQa9D-Jz0lM1A/WofUUTXdt84.jpg?size=473x137&quality=95&sign=66edc8067c0add3d96cb1d99ad19df8a&type=album)

Пример 2: 

![rm2](https://sun9-68.userapi.com/impg/iIJBF9_eJL6BzMIdoN2snOFD5SrRAVAfpmwW-g/GUMmBvNjVkI.jpg?size=498x111&quality=95&sign=50ea7db20f757b2040dd2e646247fd43&type=album)

## 8. Команда rmdir

Команда rmdir (remove directory) — команда в операционных системах DOS, UNIX, Windows, которая удаляет каталог из файловой системы.

Команда rmdir используется в окне терминала или командной строке для удаления только пустых каталогов.

Пример: rm каталог не удаляет, а удаляет команда rmdir

![rmdir](https://sun9-38.userapi.com/impg/jLhDRNeh5SSMSlTDd2uqLSWhzfXQiRtoTRCTDA/bX0j8waQkEo.jpg?size=452x113&quality=95&sign=31db0c35a10f4dbbb793508c6faacba5&type=album)

## 9. Команда mv

Команда mv задает перемещение файла или каталога. При указании нового имени в пути перемещения - переименовывается

Пример: 

![mv](https://sun9-36.userapi.com/impg/k3cnq2NDmADk4QG1mUOKnZq25Xpx4Tj1F0btmA/LdDFP1d_LEE.jpg?size=551x365&quality=95&sign=3ab8c7e1b2d2bf4fd91d146800e73722&type=album)

## 10. Команда cp

Команда cp (от англ. copy) копирует файлы или каталоги.

Подробности применения команды можно получить, используя команду man cp.

Пример: 

![cp](https://sun9-7.userapi.com/impg/G8N-6vXMRHw-LKXvlTaoQZiRs_vo187sxjyb2Q/dBIq3G-JRxQ.jpg?size=559x235&quality=95&sign=4ec81114a587607c4ebaaca5b8c2ada8&type=album)

## 11. Команда cat

Команда cat (от англ. concatenate) — последовательно выводит указанные файлы, таким образом, объединяя их в единый поток. 

Если вместо имени файла указывается «-», то читается стандартный ввод.

cat a.txt b.txt – содержимое файлов a.txt и b.txt выводится на экран;
cat a.txt b.txt > abc.txt - содержимое файлов a.txt и b.txt
сохраняется в файле abc.txt.

Пример: 

![cat](https://sun9-61.userapi.com/impg/PtLAUDFonURjU9aq-EEn6ZlSy94K4yjQjrr4tw/d5EOn3dBYlw.jpg?size=489x69&quality=95&sign=99b03facf99bf4b4abc6aa91b4ee8910&type=album)

## 12. Соответствует ли строка «sapr» шаблону [!a]? Почему?

Шаблон [!a] говорит о том, что в названии не должно быть "а", значит Строка «sapr» противоречит шаблону.

## Практика 

![dz](https://sun9-17.userapi.com/impg/x2P-d3QyIK-8Q79bFNpZJHKfXs0Rzu9tYiVg9w/OmaJL-LIfR8.jpg?size=440x879&quality=95&sign=7b4d6b4a63228b30d376daf137a699e1&type=album)

Команда head записывает в стандартный поток вывода первые несколько строк каждого из заданных файлов или первые несколько строк из стандартного потока ввода. Если в команде head не указаны флаги, то по умолчанию выводятся первые 10 строк. Можно указать две строки, чтобы увидеть разницу с командой tail

Команда tail записывает в стандартный поток вывода содержимое файла, заданного в параметре Файл, начиная с указанной позиции. Будут показаны последние 10 строк файла accounts. 

Команда cal предназначена для вызова одноименной утилиты, осуществляющей вывод календаря в терминале.

В Linux команда date отображает и устанавливает системную дату и время. 