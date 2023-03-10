---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
subtitle: Дисциплина - операционные системы
author:
  - Пронякова О.М.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 11 марта 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

    * Пронякова Ольга Максимовна
  * студент НКАбд-02-22
  * факультет физико-математических и естественных наук
  * Российский университет дружбы народов
  
:::
::::::::::::::

# Создание презентации

## Цель работы

 - Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.

## Основные задачи

1. Выполните все примеры, приведённые в первой части описания лабораторной работы.
2. Выполните следующие действия, зафиксировав в отчёте по лабораторной работе
используемые при этом команды и результаты их выполнения:
 2.1. Скопируйте файл /usr/include/sys/io.h в домашний каталог и назовите его
equipment. Если файла io.h нет, то используйте любой другой файл в каталоге
/usr/include/sys/ вместо него.
 2.2. В домашнем каталоге создайте директорию ~/ski.plases.
 2.3. Переместите файл equipment в каталог ~/ski.plases.
 2.4. Переименуйте файл ~/ski.plases/equipment в ~/ski.plases/equiplist.
 
## Основные задачи
 
 2.5. Создайте в домашнем каталоге файл abc1 и скопируйте его в каталог
~/ski.plases, назовите его equiplist2.
 2.6. Создайте каталог с именем equipment в каталоге ~/ski.plases.
 2.7. Переместите файлы ~/ski.plases/equiplist и equiplist2 в каталог
~/ski.plases/equipment.
 2.8. Создайте и переместите каталог ~/newdir в каталог ~/ski.plases и назовите
его plans.

## Основные задачи

3. Определите опции команды chmod, необходимые для того, чтобы присвоить перечис-
ленным ниже файлам выделенные права доступа, считая, что в начале таких прав
нет:
 3.1. drwxr--r-- ... australia
 3.2. drwx--x--x ... play
 3.3. -r-xr--r-- ... my_os
 3.4. -rw-rw-r-- ... feathers
При необходимости создайте нужные файлы.

## Основные задачи

4. Проделайте приведённые ниже упражнения, записывая в отчёт по лабораторной
работе используемые при этом команды:
 4.1. Просмотрите содержимое файла /etc/password.
 4.2. Скопируйте файл ~/feathers в файл ~/file.old.
 4.3. Переместите файл ~/file.old в каталог ~/play.
 4.4. Скопируйте каталог ~/play в каталог ~/fun.
 4.5. Переместите каталог ~/fun в каталог ~/play и назовите его games.
 4.6. Лишите владельца файла ~/feathers права на чтение.

## Основные задачи

 4.7. Что произойдёт, если вы попытаетесь просмотреть файл ~/feathers командой
cat?
 4.8. Что произойдёт, если вы попытаетесь скопировать файл ~/feathers?
 4.9. Дайте владельцу файла ~/feathers право на чтение.
 4.10. Лишите владельца каталога ~/play права на выполнение.
 4.11. Перейдите в каталог ~/play. Что произошло?
 4.12. Дайте владельцу каталога ~/play право на выполнение.
5. Прочитайте man по командам mount, fsck, mkfs, kill и кратко их охарактеризуйте,
приведя примеры.

## Выполнение лабораторной работы

1. Выполняю все примеры, приведённые в первой части описания лабораторной работы.
2. Копируйте файл /usr/include/аio.h в домашний каталог и называю его equipment(рис. 1) (рис. 2) (рис. 3).

![Переход в каталог](image/pic17.jpeg){ #fig:pic17 width=100% }

## Выполнение лабораторной работы

![Копирование файла](image/pic18.jpeg){ #fig:pic18 width=100% }

![Проверка](image/pic19.jpeg){ #fig:pic19 width=100% }

## Выполнение лабораторной работы

В домашнем каталоге создаю директорию ~/ski.plases(рис. 4).

![Создание директории](image/pic20.jpeg){ #fig:pic20 width=100% }

## Выполнение лабораторной работы

Перемещаю файл equipment в каталог ~/ski.plases(рис. 5).

![Перемещение файла в каталог](image/pic21.jpeg){ #fig:pic21 width=100% }

## Выполнение лабораторной работы

Переимещаю файл ~/ski.plases/equipment в ~/ski.plases/equiplist(рис. 6).

![Перемещение файла](image/pic22.jpeg){ #fig:pic22 width=100% }

## Выполнение лабораторной работы

Создаю в домашнем каталоге файл abc1 и копирую его в каталог ~/ski.plases, назовите его equiplist2(рис. 7).

![Создание и копирование файла](image/pic23.jpeg){ #fig:pic23 width=100% }

## Выполнение лабораторной работы

Создаю каталог с именем equipment в каталоге ~/ski.plases(рис. 8).

![Создание каталога](image/pic24.jpeg){ #fig:pic24 width=100% }

## Выполнение лабораторной работы

Перемещаю файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment(рис. 9).

![Перемещение файлов в каталог](image/pic25.jpeg){ #fig:pic25 width=100% }

## Выполнение лабораторной работы

Создаю и перемещаю каталог ~/newdir в каталог ~/ski.plases и называю его plans(рис. 10).

![Создание и еремещение каталога](image/pic26.jpeg){ #fig:pic26 width=100% }

## Выполнение лабораторной работы

Создаю некоторые файлы и каталоги(рис. 11).

![Создание файлов и каталогов](image/pic27.jpeg){ #fig:pic27 width=100% }

## Выполнение лабораторной работы

3. Определяю опции команды chmod, необходимые для того, чтобы присвоить создвнным файлам выделенные права доступа, считая, что в начале таких прав нет(рис. 12) (рис. 13).

![Определение опции команды chmod](image/pic28.jpeg){ #fig:pic28 width=100% }

## Выполнение лабораторной работы

![Проверка](image/pic29.jpeg){ #fig:pic29 width=100% }

## Выполнение лабораторной работы

4. Просмотриваю содержимое файла /etc/passwd(рис. 14) (рис. 15).

![Просмотр содержимого файла](image/pic30.jpeg){ #fig:pic30 width=100% }

## Выполнение лабораторной работы

![Просмотр содержимого файла](image/pic31.jpeg){ #fig:pic31 width=100% }

## Выполнение лабораторной работы

Копирую файл ~/feathers в файл ~/file.old(рис. 16).

![Копирование файла](image/pic32.jpeg){ #fig:pic32 width=100% }

## Выполнение лабораторной работы

Перемещаю файл ~/file.old в каталог ~/play(рис. 17).

![Перемещение файла](image/pic33.jpeg){ #fig:pic33 width=100% }

## Выполнение лабораторной работы

Копирую каталог ~/play в каталог ~/fun(рис. 18).

![Копирование каталога](image/pic34.jpeg){ #fig:pic34 width=100% }

## Выполнение лабораторной работы

Перемещаю каталог ~/fun в каталог ~/play и называю его games(рис. 19).

![Перемещение каталога](image/pic35.jpeg){ #fig:pic35 width=100% }

## Выполнение лабораторной работы

Лишаю владельца файла ~/feathers права на чтение(рис. 20).

![Лишение владельца файла права на чтение](image/pic36.jpeg){ #fig:pic36 width=100% }

## Выполнение лабораторной работы

Смотрю, что произойдёт, если я попытаюсь просмотреть файл ~/feathers командой cat(рис. 21).

![Выполнение команды](image/pic37.jpeg){ #fig:pic37 width=100% }

## Выполнение лабораторной работы

Смотрю, что произойдёт, если я попытаюсь скопировать файл ~/feathers(рис. 22).

![Выполнение команды](image/pic38.jpeg){ #fig:pic38 width=100% }

## Выполнение лабораторной работы

Даю владельцу файла ~/feathers право на чтение(рис. 23).

![Право на чтение](image/pic39.jpeg){ #fig:pic39 width=100% }

## Выполнение лабораторной работы

Лишаю владельца каталога ~/play права на выполнение. Далее перехожу в каталог ~/play. Даю владельцу каталога ~/play право на выполнение(рис. 24).

![Выполнение команд](image/pic40.jpeg){ #fig:pic40 width=100% }

## Выполнение лабораторной работы

5. Читаю man по командам и кратко их охарактеризовываю. Выполнение команды man mount(рис. 25) (рис. 26).

![Выполнение команды](image/pic41.jpeg){ #fig:pic41 width=100% }

![Выполнение команды](image/pic42.jpeg){ #fig:pic42 width=100% }

## Выполнение лабораторной работы

Выполнение команды man fsck(рис. 27) (рис. 28).

![Выполнение команды](image/pic43.jpeg){ #fig:pic43 width=100% }

![Выполнение команды](image/pic44.jpeg){ #fig:pic44 width=100% }

## Выполнение лабораторной работы

Выполнение команды man mkfs(рис. 29) (рис. 30).

![Выполнение команды](image/pic45.jpeg){ #fig:pic45 width=100% }

![Выполнение команды](image/pic46.jpeg){ #fig:pic46 width=100% }

## Выполнение лабораторной работы

Выполнение команды man kill(рис. 31) (рис. 32).

![Выполнение команды](image/pic47.jpeg){ #fig:pic47 width=100% }

![Выполнение команды](image/pic48.jpeg){ #fig:pic48 width=100% }

## Выводы

 - Ознакомилась с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобрела практические навыки по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.












