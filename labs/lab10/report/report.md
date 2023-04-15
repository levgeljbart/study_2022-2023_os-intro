---
## Front matter
title: "Отчёт по лабораторной работе 10"
author: "Гельбарт Лев"

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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.

# Выполнение лабораторной работы

Пишем программу, создающую и архивирующую свой командный файл. Просто приказываем скопировать себя в папку backup, переходим в нее и приказываем архивировать положенную сюда копию файла.

![Командный файл](image/1.png){#fig:001 width=70%}

![Результаты](image/2.png){#fig:002 width=70%}

Пишем код, который бесконечно (пока пользователь не прекратит работу программы через ctrl+c) считывает числа и выводит их пользователю с припиской "ваше число: ".

![Командный файл](image/4.png){#fig:003 width=70%}

![Работа программы](image/3.png){#fig:004 width=70%}

Пишем программу, запрашивающую путь к директории, переходящую туда и выдающую ее содержимое.

![Командный файл](image/6.png){#fig:005 width=70%}

![Работа программы ](image/5.png){#fig:006 width=70%}

Пишем программу, запрашивающую папку, формат файла в ней и через цикл с перебором всех подобных файлов в папке выдающую все эти файлы с абсолютными путями к ним.

![Командный файл](image/8.png){#fig:007 width=70%}

![Работа программы ](image/7.png){#fig:008 width=70%}

# Выводы

Были изучены основы программирования в оболочке ОС UNIX/Linux. Были получены навыки написания небольших командных файлов.
