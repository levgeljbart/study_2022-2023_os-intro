---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе 9
author:
  - Гельбарт Лев
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 08 апреля 2023

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

- Разобраться с редактором emacs, с его интерфейсом и функционалом.

## Упражнения

- Начнем написав emacs, этим запускаем редактор. Создаем файл Ctrl-x Ctrl-f. Вписываем в него нужный нам текст, сохраняем его Ctrl-x Ctrl-s 
![emacs](image/2.png){#fig:001 width=70%}

## Упражнения

- Вырезаем строку Ctrl-k 
![emacs](image/3.png){#fig:002 width=70%}

## Упражнения

- Вставляем в конец файла Ctrl-y 
![emacs](image/4.png){#fig:003 width=70%}

## Упражнения

- Выделяем часть текста Ctrl-space 
![emacs](image/5.png){#fig:004 width=70%}

## Упражнения

- Другую выделенную часть копируем - вставляем Alt-w, Ctrl-y
![emacs](image/6.png){#fig:005 width=70%}

## Упражнения

- Снова выделяем, на этот раз вырезаем Ctrl-w 
![emacs](image/7.png){#fig:006 width=70%}

## Упражнения

- Отменяем последнее действие Ctrl-/ 
![emacs](image/8.png){#fig:007 width=70%}

## Упражнения

- Теперь играем курсором. Ставим его в начало строки Ctrl-a 
![emacs](image/9.png){#fig:008 width=70%}

## Упражнения

- В конец строки Ctrl-e 
![emacs](image/10.png){#fig:009 width=70%}

## Упражнения

- Перемещаемся в начало буфера Alt-< 
![emacs](image/11.png){#fig:010 width=70%}

## Упражнения

- В конец буфера Alt-> 
![emacs](image/12.png){#fig:011 width=70%}

## Упражнения

- Теперь откроем список активных буферов на весь экран Ctrl-x Ctrl-b (он был и на предыдущих фото).
![emacs](image/13.png){#fig:012 width=70%}

## Упражнения

- Открываем другой буфер Ctrl-x 
![emacs](image/14.png){#fig:013 width=70%}

## Упражнения

- Теперь закрываем это окно Ctrl-x 0
![emacs](image/15.png){#fig:014 width=70%}

## Упражнения

- Переключаемся между буферами, но не выводя меню в явном виде Ctrl-x b 
![emacs](image/16.png){#fig:015 width=70%}

## Упражнения

- Теперь раскроим фрейм на 4 окна Ctrl-x 3, затем в каждой половине Ctrl-x 2
![emacs](image/17.png){#fig:016 width=70%}

## Упражнения

- В каждом окне создадим свой буфер и напишем в каждом свой случайный набор букв Ctrl-x Ctrl-f. Поищем в одном буфере букву "е" Ctrl-s
![emacs](image/18.png){#fig:017 width=70%}

## Упражнения

- Переключимся на другой результат поиска Ctrl-s
![emacs](image/19.png){#fig:018 width=70%}

## Упражнения

- Выходим из поиска Ctrl-g
![emacs](image/20.png){#fig:019 width=70%}

## Упражнения

- Запросим поиск текста на изменение Alt-% 
![emacs](image/21.png){#fig:020 width=70%}

## Упражнения

- Введем текст, на который надо совершить замену
![emacs](image/22.png){#fig:021 width=70%}

## Упражнения

- Теперь задействуем иную модель поиска. Это поиск не посимвольно, а поиск по строке Alt-s 0
![emacs](image/23.png){#fig:022 width=70%}

## Выводы

- Был освоен редактор emacs со своим функционалом и интерфейсом.

