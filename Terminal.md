## Terminal
**HW1**
1) Посмотреть где я **-** `pwd`
2) Создать папку **-**`mkdir main`
3) Зайти в папку **-**`cd main`
4) Создать 3 папки
 **-**`mkdir dir1 dir2 dir3`
5) Зайти в любоую папку
 **-** `cd dir1`
6) Создать 5 файлов (3 txt, 2 json)
 **-**`touch 1.txt 2.txt 3.txt 1.json 2.json`
7) Создать 3 папки
 **-**`mkdir dir1 dir2 dir3`
8) Вывести список содержимого папки
 **-**`ls`
9) Открыть любой txt файл
 **-**`vim 1.txt`
10) Написать туда что-нибудь, любой текст<br> **-**`Tap [i] and input Ilon Mask`
11) Сохранить и выйти<br> **-**`Tap Esc and input :wq`
12) Выйти из папки на уровень выш
> **-**`cd ..`
13) Переместить любые 2 файла, которые вы создали, в любую другую папку
 **-**`mv 1.json 2.json dir2/`
14) Скопировать любые 2 файла, которые вы создали, в любую другую папку
 **-**`cp 1.json 2.json `
15) Найти файл по имени
 **-**`find 1.json`
16) Просмотреть содержимое в реальном времени (команда grep) изучите как она работает
 **-**`grep -i -c l a.txt`
17) Вывести несколько первых строк из текстового файла
**-**`sed -n '1,2'p 1.txt / head -2 a.txt`
18) Вывести несколько последних строк из текстового файла
 **-**`sed -n '$'p 1.txt / tail -2 a.txt` 
19) Просмотреть содержимое длинного файла (команда less) изучите как она работает
 **-**`less 1.txt`
20) Вывести дату и время
 **-**`date`


Задание *
1) Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request<br> **-**`curl get http://162.55.220.72:5005`
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13<br> **-**

**#!/bin/bash<br>
mkdir d1<br>
#Open folder<br>
cd d1<br>
#Create 3 folders in d1<br>
mkdir a1 a2 a3<br>
#Open a1<br>
cd a1<br>
#Create 5 file:3txt and 2json<br>
touch 1.txt 2.txt 3.txt 4.json 5.json<br>
#Create 3 folders<br>
mkdir f1 f2 f3<br>
#List the contents of folders<br>
ls<br>
#Move 2 file in f1<br>
mv 4.json 5.json f1<br>**

