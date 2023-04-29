---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 4"
author: "Кадирова Мехрубон Рахматжоновна"

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

Создание персонального сайта с помощью Github. Размещение своего проекта на хостинге  git.

# Задание

1. Список достижений.
- Добавить информацию о навыках (Skills).
- Добавить информацию об опыте (Experience).
- Добавить информацию о достижениях (Accomplishments).
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
- Язык разметки Markdown.

# Выполнение лабораторной работы

1. Список достижений.
- Добавить информацию о навыках (Skills).

![Информация о навыках в текстовом редакторе](image/1.png){#fig:001 width=70%}

![Информация о навыках на сайте](image/11.png){#fig:002 width=70%}

- Добавить информацию об опыте (Experience).

![Информация об опыте в текстовом редакторе](image/2.png){#fig:003 width=70%}

![Информация об опыте на сайте](image/21.png){#fig:004 width=70%}

- Добавить информацию о достижениях (Accomplishments).

![Информация о достижениях в текстовом редакторе](image/3.png){#fig:005 width=70%}

![Информация о достижениях на сайте](image/31.png){#fig:006 width=70%}

2. Сделать пост по прошедшей неделе.

![Пост о прошедшей неделе на сайте](image/4.png){#fig:007 width=70%}

3. Добавить пост на тему по выбору:
- Язык разметки Markdown.

![Пост о прошедшей Markdown на сайте](image/5.png){#fig:008 width=70%}

# Выводы

Создание персонального сайта с помощью Github. Размещение своего проекта на хостинге  git.
