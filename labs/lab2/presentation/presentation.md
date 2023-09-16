---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
subtitle: Дискреционное разграничение прав в Linux. Основные атрибуты
author: |
	 Ким Реачна\inst{1}

institute: |
	\inst{1}Российский Университет Дружбы Народов

date: 15 сентября, 2023, Москва, Россия

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
# Вводная часть

## Цели и задачи

Получение практических навыков работы в консоли с атрибутами файлов, закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux. 

# Процесс выполнения лабораторной работы

## Определяем UID и группу

![Информация о пользователе guest](image/2.png){ #fig:002 width=70% height=70% }

## Файл с данными о пользователях

![Сожержимое файла /etc/passwd](image/3.png){ #fig:003 width=70% height=70% }

## Доступ к домашним директориям

![Расширенные атрибуты](image/4.png){ #fig:004 width=70% height=70% }

## Атрибуты директории

![Снятие атрибутов с директории](image/6.png){ #fig:006 width=70% height=70% }

## Права и разрешённые действия

![Минимальные права для совершения операций](image/8.png){ #fig:008 width=70% height=70% }

# Выводы по проделанной работе

## Вывод

В ходе выполнения лабораторной работы были получены навыки работы с атрибутами файлов и сведения о разграничении доступа.
