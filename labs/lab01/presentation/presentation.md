---
## Front matter
lang: ru-RU
title: Установка ОС Linux
author:
  - Гельбарт Лев
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 18 февраля 2023

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

- Установить ОС Linux и прочее ПО (Pandoc, TeX и другие)
- Получить с помощью командной строки информацию о виртуальной машине

## Материалы и методы

- Лабораторные работы 1,2 и 4 из прошлого семестра
- Командная строка

## Использование старых отчетов

- В прошлом семестре уже был установлен Linux
- Tex, lualatex, pandoc и иные тоже уже были установлены
- Поэтому отчеты из прошлого семестра актуальны для этой лабораторной работы
## Получение информации

- Чтобы получить информацию через командную строку использовались две простые команды: mount | grep "..." и dmesg | grep -i "..."

## Итоги
- ПО Linux было установлены, были приведены доказательства этого
- Показано, что нахождение информации через терминал не представляет труда

