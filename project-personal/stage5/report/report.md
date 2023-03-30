---
## Front matter
title: "Отчёт по 5 этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Сячинова Ксения Ивановна"

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
lot: false # List of tables
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

Продолжение создания сайта. Получение новых навыков.

# Задание

**Добавить к сайту все остальные элементы.**

- Сделать записи для персональных проектов.

- Сделать пост по прошедшей неделе.

- Добавить пост на тему по выбору.

 *Языки научного программирования.*

# Выполнение лабораторной работы

1. Сделаем записи для персональных проектов. Для этого переходим в папку
contents -> project и делаем необходимые изменения.(рис. @fig:001), (рис. @fig:002)

![Проект в формате md](image/1.png){#fig:001 width=70%}

![Проект на сайте](image/2.png){#fig:002 width=70%}

2. Затем сделаем новый пост. Создаём новую папку в которй будет вся инфомрация. (рис. @fig:003), (рис. @fig:004)

![Проект в формате md](image/3.png){#fig:003 width=70%}

![Проект на сайте](image/4.png){#fig:004 width=70%}

3. Сделаем пост на тему "Языки научного программирования"(рис. @fig:005), (рис. @fig:006)

![Проект в формате md](image/5.png){#fig:005 width=70%}

![Проект на сайте](image/6.png){#fig:006 width=70%}

4. Затем выгружаем все материалы на сайт. Для этого делаем команды из publica и из папки нашего проекта.(рис. @fig:007), (рис. @fig:008)

![Загрузка сайта](image/7.png){#fig:007 width=70%}

![Загрузка сайта](image/8.png){#fig:008 width=70%}

# Выводы

В процессе выполнения данного этапа проекта, я приобрела практические навыки по созданию сайта, получила новые знания. 
