---
## Front matter
title: "Индивидуальный проект (3 этап)"
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

Добавить к сайту данные о себе. Написать пост по прошедшей неделе и научный пост на выбор.

# Задание

Добавить к сайту достижения.

    Список достижений.
        Добавить информацию о навыках (Skills).
        Добавить информацию об опыте (Experience).
        Добавить информацию о достижениях (Accomplishments).
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
        Легковесные языки разметки.
        Языки разметки. LaTeX.
        Язык разметки Markdown.


# Выполнение лабораторной работы

В домашней папке перехожу в папку blog/content и открываю файл index.md. Пишу свои навыки(рис. [-@fig:pic1]) (рис. [-@fig:pic2]).

![Добавление навыков](image/pic1.jpeg){ #fig:pic1 width=100% }

![Добавление навыков](image/pic2.jpeg){ #fig:pic2 width=100% }

Добавляю информацию об опыте(рис. [-@fig:pic3]) (рис. [-@fig:pic4]).

![Добавление опыта](image/pic3.jpeg){ #fig:pic3 width=100% }

![Добавление опыта](image/pic4.jpeg){ #fig:pic4 width=100% }

Добавляю информацию о достижениях (рис. [-@fig:pic5]) (рис. [-@fig:pic6]).

![Добавление достижений](image/pic5.jpeg){ #fig:pic5 width=100% }

![Добавление достижений](image/pic6.jpeg){ #fig:pic6 width=100% }

Делаю пост по прошедшей неделе. В папке blog/content/post создаю папку, которую называю 2 week и в ней пишу пост(рис. [-@fig:pic7]) (рис. [-@fig:pic8]).

![Написание поста](image/pic7.jpeg){ #fig:pic7 width=100% }

![Пост на сайте](image/pic8.jpeg){ #fig:pic8 width=100% }

Добавить пост на тему Язык разметки Markdown. В папке blog/content/post создаю папку, которую называю Markdown и в ней пишу пост (рис. [-@fig:pic9]) (рис. [-@fig:pic10]).

![Написание поста](image/pic9.jpeg){ #fig:pic9 width=100% }

![Пост на сайте](image/pic10.jpeg){ #fig:pic10 width=100% }

Затем открываю терминал и перехожу в ~/blog. Добавляю все изменения на Github. Перехожу в папку public и тоже добавляю все изменения на Github(рис. [-@fig:pic11]).

![Добавление измений на Github](image/pic11.jpeg){ #fig:pic11 width=100% }

# Выводы

Добавила к сайту данные о себе. Написала пост по прошедшей неделе и научный пост на выбор.

# Список литературы{.unnumbered}

[1. Этапв реализации проекта](https://esystem.rudn.ru/mod/page/view.php?id=970806)


::: {#refs}
:::
