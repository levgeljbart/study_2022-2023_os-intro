---
## Front matter
lang: ru-RU
title: Индивидуальный проект, этап 1
author:
  - Лев Гельбарт
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

- Создать по шаблону Hugo персональный сайт научного работника

## Содержание лабораторной работы 1

- Скачивается из репозитория архив с Hugo 
- По шаблону репозитория сайта создается свой репозиторий, который и станет сайтом
- Этот репозиторий копируется на компьютер

## Содержание лабораторной работы 2

- Запускаем hugo server
- В папке будущего сайта создаем ветку main, переключаемся на нее.
- Здесь создаем пустой файл, выгружаем в github

## Содержание лабораторной работы 3

- В файле gitignore надо закомментировать слово public.
- Выполним команду субмодуля, за ней hugo
- Переместимся в папку public, отсюда проверим ее связь с репозиторием на github, выгрузимся туда

## Результаты

- Был создан персональный сайт научного сотрудника
