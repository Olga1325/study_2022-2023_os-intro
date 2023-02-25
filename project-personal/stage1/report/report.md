---
## Front matter
title: "Индивидуальный проект 1 этап"
subtitle: "Дисциплина: операционные системы"
author: "Пронякова Ольга Максимовна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Размещение на Github pages заготовки для персонального сайта.

# Задание

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.


# Выполнение индивидуального пректа

Скачиваем исполняемый файл hugo для того, чтобы генерировать страницы сайта(рис. [-@fig:pic1]).

![ГСкачивание файла](image/pic1.jpeg){ #fig:pic1 width=100% }

Данный файл появляется в папке "Загрузки". Далее его надо разархивировать(рис. [-@fig:pic2]).

![ГРазархивация файла](image/pic2.jpeg){ #fig:pic2 width=100% }

Создаем папку bin с помощью команды mkdir(рис. [-@fig:pic3]).

![ГСоздание папки](image/pic3.jpeg){ #fig:pic3 width=100% }

Помещаем в папку bin исполняемый файл hugo(рис. [-@fig:pic4]).

![Перермещение исполняемого файла hugo в папку bin](image/pic4.jpeg){ #fig:pic4 width=100% }

Заходим в ТУИС и находим ссылку на репозиторий шаблона индивидуального сайта(рис. [-@fig:pic5]).

![Ссылка на репозиторий шаблона индивидуального сайта](image/pic5.jpeg){ #fig:pic5 width=100% }

Далее создаем новый репозиторий(рис. [-@fig:pic6]) (рис. [-@fig:pic7]).

![Создание репозитория](image/pic6.jpeg){ #fig:pic6 width=100% }

![Создание репозитория](image/pic7.jpeg){ #fig:pic7 width=100% }

Копируем ссылку для клонирования репозитория(рис. [-@fig:pic8]).

![Копирование ссылки](image/pic8.jpeg){ #fig:pic8 width=100% }

Клонируем репозиторий(рис. [-@fig:pic9]).

![Клонирование репозитория](image/pic9.jpeg){ #fig:pic9 width=100% }

Переходим в каталог blog и просматриваем файлы(рис. [-@fig:pic10]).

![Просматривание файлов в каталоге blog](image/pic10.jpeg){ #fig:pic10 width=100% }

Выполняем команду ~/bin/hugo(рис. [-@fig:pic11]).

![Выполнение команды ~/bin/hugo](image/pic11.jpeg){ #fig:pic11 width=100% }

Далее просматриваем файлы. Замечаем, что появился новый файл public. Переходим в mc и удаляем данный файл(рис. [-@fig:pic12]) (рис. [-@fig:pic13]).

![Просмотр файлов](image/pic12.jpeg){ #fig:pic12 width=100% }

![Удаление файла public](image/pic13.jpeg){ #fig:pic13 width=100% }

Выполняем команду ~/bin/hugo server(рис. [-@fig:pic14]).

![Выполнение команды ~/bin/hugo server](image/pic14.jpeg){ #fig:pic14 width=100% }

В результате работы данной команды мы получили ссылку, по которой перешли на сайт(рис. [-@fig:pic15]) (рис. [-@fig:pic16]).

![Ссылка для перехода на сайт](image/pic15.jpeg){ #fig:pic15 width=100% }

![Ссылка для перехода на сайт](image/pic16.jpeg){ #fig:pic16 width=100% }

Создаем репозиторий с названием моего пользователя на Github(рис. [-@fig:pic17]).

![Создание репозитория](image/pic17.jpeg){ #fig:pic17 width=100% }

Открываем терминал и проверяем наличие файла blog(рис. [-@fig:pic18]).

![Проверка наличия файла blog](image/pic18.jpeg){ #fig:pic18 width=100% }

Копируем ссылку с Github(рис. [-@fig:pic19]).

![Копирование ссылки](image/pic19.jpeg){ #fig:pic19 width=100% }

Далее клонируем репозиторий и проверяем его наличие(рис. [-@fig:pic20]) (рис. [-@fig:pic21]).

![Клонирование репозитория](image/pic20.jpeg){ #fig:pic20 width=100% }

![Проверка наличия репозитория](image/pic21.jpeg){ #fig:pic21 width=100% }

Переходим в него и создаем ветку main(рис. [-@fig:pic22]).

![Создание ветки main](image/pic22.jpeg){ #fig:pic22 width=100% }

Создаем пустой файл README.md, чтобы активировать репозиторий, и добавляем данный файл на Github(рис. [-@fig:pic23]). 

![Создание пустого файла](image/pic23.jpeg){ #fig:pic23 width=100% }

Проверяем наличие данного файла в созданном репозитории на Github(рис. [-@fig:pic24]). 

![Проверка наличия пустого файла в репозитории](image/pic24.jpeg){ #fig:pic24 width=100% }

Копируем ссылку(рис. [-@fig:pic25]). 

![Копирование ссылки](image/pic25.jpeg){ #fig:pic25 width=100% }

Переходим в каталог blog и выполняем команду, которая поможет подключить созданный репозиторий к папке public внутри файла blog. Это нужно сделать, чтобы эффективно генерировать страницы сайта(рис. [-@fig:pic26]). 

![Подключение репозитория к папке public](image/pic26.jpeg){ #fig:pic26 width=100% }

Запускаем mc, находим .gitignore. С помощью клавиши f4 открываем его и комментируем public(рис. [-@fig:pic27]). 

![Комментируем public](image/pic27.jpeg){ #fig:pic27 width=100% }

Затем с помощью команды cat проверяем выполнение наших действий(рис. [-@fig:pic28]). 

![Проверка выполнения действий](image/pic28.jpeg){ #fig:pic28 width=100% }

Повторяем предыдущую команду и видим, что все добавляется в index. Далее вводим команду ~/bin/hugo(рис. [-@fig:pic29]). 

![Повтор команды](image/pic29.jpeg){ #fig:pic29 width=100% }

Проверяем наличие добавленных файлов в папке public(рис. [-@fig:pic30]). 

![Проверка наличия файлов](image/pic30.jpeg){ #fig:pic30 width=100% }

Переходим в public и проверяем, что каталог подключен к созданному репозиторию(рис. [-@fig:pic31]). 

![Проверка подключения каталога к репозиторию](image/pic31.jpeg){ #fig:pic31 width=100% }

Добавляем файлы на Github(рис. [-@fig:pic32]) (рис. [-@fig:pic33]). 

![Добавление файлов на Github](image/pic32.jpeg){ #fig:pic32 width=100% }

![Добавление файлов на Github](image/pic33.jpeg){ #fig:pic33 width=100% }

Проверяем наличие файлов в репозитории на Github(рис. [-@fig:pic34]).

![Проверка наличия файлов на Github](image/pic34.jpeg){ #fig:pic34 width=100% }

Далее копируем ссылку на наш новй сайт и проверяем его наличие(рис. [-@fig:pic35]) (рис. [-@fig:pic36]).

![Проверка наличия сайта](image/pic35.jpeg){ #fig:pic35 width=100% }

![Проверка наличия сайта](image/pic36.jpeg){ #fig:pic36 width=100% }

# Выводы

Разместила на Github pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

[1. Первый этап индивидуального пректа](https://www.youtube.com/watch?v=OpsSv0RE3C4)

::: {#refs}
:::
