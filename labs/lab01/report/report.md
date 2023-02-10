---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Компюьтерные науки и технология программирования. Операционные системы"
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

Изучить идеологию и применение средств контроля версий git, а также освоить умения по работе с git.

# Выполнение лабораторной работы

1. Для начала нам нужно создать учётную запись на github. Так как в прошлом семестре мы работали с данной платформой, то мы уже зарегестрировались там. (рис. @fig:001).

![Учётная запись](image/1.png){#fig:001 width=50%}

2. Затем произведём базовую настройку git, а именно:
- Зададим имя и email владельца репозитория
- Настроим utf-8 в выводе сообщений git
- Установка параметра autocrlf 
- Установка параметра safecrlf (рис. @fig:002).

![Базовая настройка git](image/2.png){#fig:002 width=50%}

3. После этого создадим ключ для последующей индентификации пользователя на сервере. Делаем это с помощью команды "ssh-keygen -C Имя Фамилия <workemail>".(рис. @fig:003).

![Создание ключа](image/3.png){#fig:003 width=50%}

4. Командой "cat ~/.ssh/id_rsa.pub | xclip -sel clip" копируем этот ключ и загружаем его на github.(рис. @fig:004)., (рис. @fig:005).

![Копирование ключа](image/4.png){#fig:004 width=50%}

![Загрузка ключа](image/5.png){#fig:005 width=50%}

5. Далее создадим каталог "Операционные системы" в ранее созданом пространстве. Наш каталог будет иметь путь: work/study/2022-2023/"Операционные системы".(рис. @fig:006).

![Создание каталога](image/6.png){#fig:006 width=50%}

6. Создаём репозиторий, который будет создан на основе данного нам шаблона. (рис. @fig:007), (рис. @fig:008).

![Шаблон](image/7.png){#fig:007 width=50%}

![Создание репозитория](image/8.png){#fig:008 width=50%}

7. Затем клонируем репозиторий. Для этогокопируем ссылку созданного репозитория (Code -> SSH) и с помощью команды "git clone --recursive" клонируем. (рис. @fig:009),(рис. @fig:010).

![Копирование кода](image/9.png){#fig:009 width=50%}

![Клонирвание репозитория](image/10.png){#fig:010 width=50%}

8. Настроим каталог курса, где удалим ненужные файлы, создадим необходимые каталоги и отправим файл на сервер.(рис. @fig:011).
 
![Настройка каталога](image/11.png){#fig:011 width=50%}

9. Всё выполненно корректно. Мы создали рабочее пространство для выполнения дальнейших лабораторных работ. (рис. @fig:012).

![Рабочее пространство](image/12.png){#fig:012 width=50%}

# Выводы

В процессе выполнения данной лабораторной работы я создала рабочее пространство для дальнейшей работы. Так же вспомнила идеологию и средства контроля версий git.

# Ответы на контрольные вопросы
1. Контроль версий, также известный как управление исходным кодом, — это практика отслеживания изменений программного кода и управления ими. Системы контроля версий — это программные инструменты, помогающие командам разработчиков управлять изменениями в исходном коде с течением времени.
Какие задачи решает система контроля версий:
- Защищает исходный код от потери. Данные хранятся на удалённом сервере, даже если разработчики удалят файлы с локального компьютера, они останутся в репозитории.
- Обеспечивает командную работу.
- Помогает отменить изменения. 
- Распределённая работа.

2. **Хранилище** версий - в нем
хранятся все документы вместе с историей их
изменения и другой служебной информацией.
- **commit** - сохранение изменений в
репозитории
- **история** - 
- **рабочая копия** - копия проекта, связанная с
репозиторием


