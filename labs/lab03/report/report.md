---
## Front matter
title: "Лабораторная работа №3"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

1. Сделать отчёт по предыдущей лабораторной работе в формате Markdown.

2. В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д,)

# Теоретическое введение

Markdown — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.

# Выполнение лабораторной работы

## Установление необходимого ПО
Установка TexLive
На странице официального сайта TeX Live https://www.tug.org/texlive/acqu
ire-netinstall.html скачиваю архив install-tl-unx.tar.gz (рис. [-@fig:pic1]).

![Скачивание архива TexLive](image/pic1.jpeg){ #fig:pic1 width=100% }

Распаковываю архив и перехожу в распакованную папку с помощью cd. Запускаю скрипт install-tl-* с правами root, используя sudo в начале команды(рис. [-@fig:pic2]) (рис. [-@fig:pic3]).

![Распаковка архива TexLive](image/pic2.jpeg){ #fig:pic2 width=100% }

![Запуск скрипта](image/pic3.jpeg){ #fig:pic3 width=100% }

Добавляю /usr/local/texlive/2022/bin/x86_64-linux в свой PATH для текущей и будущих сессий (рис. [-@fig:pic4]).

![Добавление в PATH](image/pic4.jpeg){ #fig:pic4 width=100% }

## Установка pandoc и pandoc-crossref
Скачиваю архив pandoc версии 2.19.2 (рис. [-@fig:pic5]).

![Скачивание pandoc](image/pic5.jpeg){ #fig:pic5 width=100% }

Скачиваю архив pandoc-crossref и распаковываю его (рис. [-@fig:pic6]) (рис. [-@fig:pic7]).

![Скачивание pandoc-crossref](image/pic6.jpeg){ #fig:pic6 width=100% }

![Распаковка pandoc-crossref](image/pic7.jpeg){ #fig:pic7 width=100% }

Копирую файлы pandoc и pandoc-crossref в каталог /usr/local/bin/ с правами пользователя root с помощью sudo (рис. [-@fig:pic8]).

![Копирование каталогов в другую директорию](image/pic8.jpeg){ #fig:pic8 width=100% }

Проверяю корректность выполненных действий (рис. [-@fig:pic9]).

![Проверка правильности выполнения команды](image/pic9.jpeg){ #fig:pic9 width=100% }

## Заполнение отчета по выполнению лабораторной работы №2 с помощтю языка разметки Markdown

Захожу в каталог второй лабораторной работы, открываю файл report и открываю файл report.md. Начинаю заполнять его(рис. [-@fig:pic10]) (рис. [-@fig:pic11]).

![Заполнение отчета в Markdown](image/pic10.jpeg){ #fig:pic10 width=100% }

![Заполнение отчета в Markdown](image/pic11.jpeg){ #fig:pic11 width=100% }

Компилирую файл с отчетом(рис. [-@fig:pic12]).

![Компиляция файлов](image/pic12.jpeg){ #fig:pic12 width=100% }

Загружаю на Github(рис. [-@fig:pic13]).

![Проверка  наличия файлов на Github](image/pic13.jpeg){ #fig:pic13 width=100% }

# Выводы

Освоила процедуры оформления отчетов с помощью легковесного языка разметки Markfown.

# Список литературы{.unnumbered}

[1. Архитектура ЭВМ](https://esystem.rudn.ru/pluginfile.php/1584622/mod_resource/content/1/Лабораторная%20работа%20№3.pdf)

[2. Лабораторная работа №3 по операционным системам](https://esystem.rudn.ru/pluginfile.php/1975764/mod_resource/content/3/003-lab_markdown.pdf)

::: {#refs}
:::
