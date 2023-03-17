---
## Front matter
title: "Отчёт по 3 этапу индивидуального проекта"
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

Выполнить третий этап проекта. Добавить новую информацию о себе и новые посты.

# Задание
    **Список достижений.**
- Добавить информацию о навыках (Skills).
- Добавить информацию об опыте (Experience).
- Добавить информацию о достижениях (Accomplishments).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:
- *Легковесные языки разметки.*
- *Языки разметки. LaTeX.*
- *Язык разметки Markdown.*

# Выполнение лабораторной работы

1. Добавим информацию о своих навыках. Для этого переходим в папку "content" и открывает файл "_index.md". (рис. @fig:001).

![Путь папки](image/1.png){#fig:001 width=40%}

2. Изменяем все пункты под себя. (рис. @fig:002).(рис. @fig:003).(рис. @fig:004).(рис. @fig:005).(рис. @fig:006).(рис. @fig:007).

![Навыки](image/2.png){#fig:002 width=40%}

![Навыки](image/3.png){#fig:003 width=40%}

![Опыт](image/4.png){#fig:004 width=40%}

![Опыт](image/5.png){#fig:005 width=40%}

![Достижения](image/6.png){#fig:006 width=40%}

![Достижения](image/7.png){#fig:007 width=40%}

3. Сделаем пост недели. (рис. @fig:008).(рис. @fig:009).

![Пост недели ](image/8.png){#fig:008 width=40%}

![Пост недели](image/9.png){#fig:009 width=40%}

4. Сделаем пост по выбору. (рис. @fig:010).(рис. @fig:011).

![Пост по выбору](image/10.png){#fig:010 width=40%}

![Пост по выбору](image/11.png){#fig:011 width=40%}

5. Строим сайт с помощью команды "hugo" и загружаем через "public" и наш проект. (рис. @fig:012).

![Завершение работы](image/12.png){#fig:012 width=40%}

# Выводы

В процессе выполнения данной лабораторной работы я получила новые навыки по созданию сайта, добавила новую информацию о себе.


