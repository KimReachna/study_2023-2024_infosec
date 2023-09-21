---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Два пользователя
author: |
	 Ким Реачна\inst{1}

institute: |
	\inst{1}Российский Университет Дружбы Народов

date: 20 сентября, 2023, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---
# Цели и задачи работы

## Цель лабораторной работы

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей.

# Процесс выполнения лабораторной работы

## Определяем UID и группу двух пользователей

![Информация о пользователях](image/3.png){ #fig:001 width=70% height=70% }

## Файл с данными о пользователях

![Сожержимое файла /etc/group](image/4.png){ #fig:002 width=70% height=70% }

## Атрибуты директории

![Снятие атрибутов с директории](image/5.png){ #fig:003 width=70% height=70%}

## Заполнение таблицы

![Заполнение таблицы](image/6.png){ #fig:004 width=70% height=70% }

## Права и разрешённые действия

![Минимальные права для совершения операций](image/7.png){ #fig:005 width=70% height=70% }

# Выводы по проделанной работе

## Вывод

В ходе выполнения работы, мы смогли приобрести практические навыки работы в консоли с атрибутами файлов для групп пользователей.
