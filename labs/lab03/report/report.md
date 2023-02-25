---
## Front matter
title: "Отчёт по лабораторной работе No.3"
subtitle: "Язык разметки Markdown"
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

# Введение

Цель лабораторной работы - исследование функционала языка разметки Markdown. Также целью является получение навыков составления отчета на данном языке. 
Для достижения поставленной цели в данном отчете будут продемонстрированы приемы, доступные в Markdown.

# Выполнение лабораторной работы

Для начала следует разобрать базовые приемы языка Markdown. 

1) Создание заголовков 

```
## Подзаголовок 1
### Подзаголовок 2
#### Подзаголовок 3
```

## Подзаголовок 1
### Подзаголовок 2
#### Подзаголовок 3


2) Курсивное и полужирное начертания

```
**Полужирный текст**
*Курсивный текст*
***И курсивный, и полужирный текст***
```

**Полужирный текст**

*Курсивный текст*

***И курсивный, и полужирный текст***


3) Блоки цитирования 

````
> Цитата
```

> Цитата


4) Создание списков

```
- Первое
- Второе
 - Второе А
 - Второе Б
- Третье
```

- Первое
- Второе
 - Второе А
 - Второе Б
- Третье

```
1. Первое
1. Второе
 1. Второе А
 1. Второе Б
1. Третье
```

1. Первое
1. Второе
 1. Второе А
 1. Второе Б
1. Третье


5) Встроенные ссылки

```
[ссылка](report1.md)
```

[ссылка](report1.md)


6) Верхние и нижние индексы

```
H~2~O
```

H~2~O

```
2^10^
```

2^10^


7) Запись формул

```
$\sin^2 (x) + \cos^2 (x) =1$
```

$\sin^2 (x) + \cos^2 (x) =1$


8) Ссылки в тексте

```
$$
\sin^2 (x) + \cos^2 (x) = 1
$$ {#eq:eq:sin2+cos2}

См. формулу ([-@eq:eq:sin2+cos2]).
```

$$
\sin^2 (x) + \cos^2 (x) = 1
$$ {#eq:eq:sin2+cos2}

См. формулу ([-@eq:eq:sin2+cos2]).


# Заключение

Был рассмотрен основной функционал языка разметки Markdown, все, необходимое для оформления отчетов по дальнейшим лабораторным работам, было рассмотрено.

