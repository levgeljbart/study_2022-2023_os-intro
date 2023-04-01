---
## Front matter
title: "Отчет по лабораторной работе 8"
author: "Лев Гельбарт"

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

Целью данной лабораторной работы является получение практических навыков работы с редактором vi.

# Выполнение лабораторной работы. Задание 1

Через командную строку создаем дерево каталогов ~work/os/lab06. Переходим внутрь и с помощью vi создаем файл hello.sh (рис. @fig:001).

![Терминал](image/Изображения/1){#fig:001 width=70%}

Вводим текст, сохраняем его и выходим (рис. @fig:002).

![Редактор  vi](image/Изображения/2){#fig:002 width=70%}

Теперь делаем файл исполняемым (рис. @fig:003).

![Терминал](image/Изображения/3){#fig:003 width=70%}

# Выполнение лабораторной работы. Задание 2

Теперь займемся всевозможным редактированием файла. Для начала поставим курсор на конец слова HELL второй строки. Нажмем "a" и допишем "HELL" до "HELLO" (рис. @fig:004).

![Редактор  vi](image/Изображения/4){#fig:004 width=70%}

Теперь установим курсор на четвертую строку и клавишами "dw" стираем "LOCAL" (рис. @fig:004). Случилось так, что этап с рисунка 4 был выполнен последним, т.е. буквы "O" в слове "HELLO" недостает.

![Редактор  vi](image/Изображения/5){#fig:005 width=70%}

Теперь клавишей "i" вводим "local" (рис. @fig:006).

![Редактор  vi](image/Изображения/6){#fig:006 width=70%}

Ставим курсор на последней строке файла. Нажав "o" дописываем в конце строку "echo $HELLO" (рис. @fig:007).

![Редактор  vi](image/Изображения/7){#fig:007 width=70%}

Клавишами "dd" удаляем последнюю строку файла (рис. @fig:008).

![Редактор  vi](image/Изображения/8){#fig:008 width=70%}

Кнопкой "u" отменяем стирание последней строки (рис. @fig:009).

![Редактор  vi](image/Изображения/9){#fig:009 width=70%}

С помощью ":wq" сохраняем и уходим (рис. @fig:010).

![Редактор  vi](image/Изображения/10){#fig:010 width=70%}

# Выводы

Был получен ряд практических навыков работы с редактором vi.
