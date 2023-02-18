---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "Первоначальная настройка git"
author: "Лев Гельбарт"

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

Настроить гит репозиторий так, чтобы тот работал.

# Выполнение лабораторной работы

![Терминал](image/1.png){#fig:001 width=70%}

Начнем, как и положено с начала. С установки базовых настроек, создания пустого локального репозитория (рис. @fig:001).

![Терминал](image/2.png){#fig:002 width=70%}

На этом скриншоте выполняются операции, связанные с gitignore, список долгий очень (рис. @fig:002).

![Терминал](image/3.png){#fig:003 width=70%}

Здесь последние наименования в списке и создание SSH-ключа и копирование его в буфер обмена (рис. @fig:003).

![Терминал](image/4.png){#fig:004 width=70%}

Здесь проведена операция git push и клонирование репозитория, пришлось использовать https-адрес вместо ssh, так как с последним в моем компьютере были затруднения (рис. @fig:004).

![Терминал](image/5.png){#fig:005 width=70%}

Здесь показан процесс создания папки os-intro и работы с ее содержим, все появившиеся файлы (361 штука) не скриншотил, только это и последние элементы (рис. @fig:005).

![Терминал](image/6.png){#fig:006 width=70%}

Последние взятые с гита файлы (рис. @fig:006).

# Выводы

Была проведена работа с git репозиториями, необходимая для дальнейшего обучения.
