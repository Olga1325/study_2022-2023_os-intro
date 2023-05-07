---
## Front matter
title: "Индивидуальный проект (5 этап)"
subtitle: "Дисциплина - операционные системы"
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

Сделать записи для персональных проектов. Написать пост по прошедшей неделе и научный пост на выбор.

# Задание


    Сделать записи для персональных проектов.
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
        Языки научного программирования.

# Выполнение лабораторной работы

В папке blog/content/project создаю две папки с названиями С++ и Python(рис. [-@fig:pic1]).

![Создание папок](image/pic1.jpeg){ #fig:pic1 width=100% }

Заполняю в файле Markdown данные. Меняю название иконок на сайте(рис. [-@fig:pic2]) (рис. [-@fig:pic3]).

![Написание проекта](image/pic2.jpeg){ #fig:pic2 width=100% }

![Проекты на сайте](image/pic3.jpeg){ #fig:pic3 width=100% }

Делаю пост по прошедшей неделе. В папке blog/content/post создаю папку, которую называю 3 week и в ней пишу пост. Добавляю пост на тему Языки научного программирования. В папке blog/content/post создаю папку и в ней пишу пост (рис. [-@fig:pic4]) (рис. [-@fig:pic5]) (рис. [-@fig:pic6]).

![Создание папок](image/pic4.jpeg){ #fig:pic4 width=100% }

![Пост на сайте](image/pic5.jpeg){ #fig:pic5 width=100% }

![Пост на сайте](image/pic6.jpeg){ #fig:pic6 width=100% }

# Выводы

Сделала записи для персональных проектов. Написала пост по прошедшей неделе и научный пост на выбор.


# Список литературы{.unnumbered}

[1. Этапв реализации проекта](https://esystem.rudn.ru/mod/page/view.php?id=970806)

::: {#refs}
:::
