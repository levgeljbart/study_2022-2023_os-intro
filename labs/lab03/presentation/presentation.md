---
## Front matter
lang: ru-RU
title: Презентация No.3
subtitle: Язык разметки Markdown
author:
  - Гельбарт Лев
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 25 февраля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

## Цели и задачи

- Через демонстрацию приемов Markdown освоить этот язык разметки.

## Создание заголовков 

```
## Подзаголовок 1
### Подзаголовок 2
#### Подзаголовок 3
```

## Курсивное и полужирное начертания

```
**Полужирный текст**
*Курсивный текст*
***И курсивный, и полужирный текст***
```

## Блоки цитирования 

````
> Цитата
```

## Создание списков

```
- Первое
- Второе
 - Второе А
 - Второе Б
- Третье
```

```
1. Первое
1. Второе
 1. Второе А
 1. Второе Б
1. Третье
```

## Встроенные ссылки

```
[ссылка](report1.md)
```

## Верхние и нижние индексы

```
H~2~O
```
```
2^10^
```

## Запись формул

```
$\sin^2 (x) + \cos^2 (x) =1$
```

## Ссылки в тексте

```
$$
\sin^2 (x) + \cos^2 (x) = 1
$$ {#eq:eq:sin2+cos2}

См. формулу ([-@eq:eq:sin2+cos2]).
```

## Итоги

- Был рассмотрен основной функционал языка разметки Markdown, все, необходимое для оформления отчетов по дальнейшим лабораторным работам, было рассмотрено.
















