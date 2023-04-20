---
## Front matter
title: "Индивидуальный проект (4 этап)"
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

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте. Написать пост по прошедшей неделе и научный пост на выбор.

# Задание


    Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
        eLibrary : https://elibrary.ru/;
        Google Scholar : https://scholar.google.com/;
        ORCID : https://orcid.org/;
        Mendeley : https://www.mendeley.com/;
        ResearchGate : https://www.researchgate.net/;
        Academia.edu : https://www.academia.edu/;
        arXiv : https://arxiv.org/;
        github : https://github.com/.
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
        Оформление отчёта.
        Создание презентаций.
        Работа с библиографией.


# Выполнение лабораторной работы

Зарегестрировалась на соответствующих сайтах и разместила на них ссылки на сайте(рис. [-@fig:pic1]) (рис. [-@fig:pic2]) (рис. [-@fig:pic3]).

![Добавление ссылок на конкретные сайты](image/pic1.jpeg){ #fig:pic1 width=100% }

![выполнение команд в терминале](image/pic2.jpeg){ #fig:pic2 width=100% }

![Проверка выполнение работы](image/pic3.jpeg){ #fig:pic3 width=100% }

Делаю пост по прошедшей неделе. В папке blog/content/post создаю папку, которую называю 3 week и в ней пишу пост(рис. [-@fig:pic4]) (рис. [-@fig:pic5]).

![Написание поста](image/pic4.jpeg){ #fig:pic4 width=100% }

![Пост на сайте](image/pic5.jpeg){ #fig:pic5 width=100% }

Добавить пост на тему Работа с библиографией. В папке blog/content/post создаю папку и в ней пишу пост (рис. [-@fig:pic6]) (рис. [-@fig:pic7]).

![Написание поста](image/pic6.jpeg){ #fig:pic6 width=100% }

![Пост на сайте](image/pic7.jpeg){ #fig:pic7 width=100% }

# Выводы

Зарегистрировалась на соответствующих ресурсах и разместила на них ссылки на сайте. Написала пост по прошедшей неделе и научный пост на выбор.

# Список литературы{.unnumbered}

[1. Этапв реализации проекта](https://esystem.rudn.ru/mod/page/view.php?id=970806)

::: {#refs}
:::
