---
## Front matter
title: "Отчёт по 6 этупа индивидуального проекта"
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

Закончить оформление сайта, приобрести новые навыки по созданию сайта, сделать поддержку двух языков.

# Задание

Размещение двуязычного сайта на Github.

- Сделать поддержку английского и русского языков.
    
- Разместить элементы сайта на обоих языках.

- Разместить контент на обоих языках.

- Сделать пост по прошедшей неделе.
    
- Добавить пост на тему по выбору (на двух языках).

# Выполнение лабораторной работы

1. Будем действовать по алгоритму, который есть на сайте *https://wowchemy.com/docs/hugo-tutorials/language/*. Сначала создаём папку i18n и создаём там два файл ru.yaml и en.ymal. Затем, размещаем там скрипты для русского и английского языка. (рис. @fig:001). (рис. @fig:002). (рис. @fig:003).


![Создание папки](image/1.png){#fig:001 width=50%}

![Создание скриптов](image/2.png){#fig:002 width=50%}

2. Для удобства создаю в папке *content* две папки, в которых будут храниться все файлы на разных языках.(рис. @fig:003).

![Создание папок](image/3.png){#fig:003 width=50%}

3. Затем в папке config -> _default -> languages добавляем русский язык. Проверяем изменения на сайте (рис. @fig:004).(рис. @fig:005).

![Добавление русского](image/4.png){#fig:004 width=50%}

![Проверка](image/5.png){#fig:005 width=50%}

4. Далее делаем перевод всех постов. Вот примеры некоторых. (рис. @fig:006).(рис. @fig:007)(рис. @fig:008).(рис. @fig:009)

![Перевод информации](image/6.png){#fig:006 width=50%}

![Перевод информации](image/7.png){#fig:007 width=50%}

![Перевод поста](image/8.png){#fig:008 width=50%}

![Перевод поста](image/9.png){#fig:009 width=50%}

5. Для перевода меню в папке config делаем новый документ с русским языком(рис. @fig:010)

![Перевод меню](image/10.png){#fig:010 width=50%}

6. Сделаем пост недели и пост по теме. Также переведём их на другой язык

![Новый пост](image/11.png){#fig:011 width=50%}

![Новый пост](image/12.png){#fig:012 width=50%}

7. Затем выгружаем все материалы на сайт. Для этого делаем команды из publica и из папки нашего проекта.

![Загрузка сайта](image/13.png){#fig:013 width=50%}

# Выводы

В процессе выполнения я приобрела практические навыки по созданию сайта, закончила создание сайта.
