---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
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

Размещение на GitHub pages заготовки для персонального сайта. 


# Выполнение лабораторной работы

1. Скачивание ПО hugo для выполнения работы (рис. @fig:001).

![Вид файла](image/1.1.png){#fig:001 width=70%}

2. Копирование распакованного файла hugo в созданную папку bin (рис. @fig:002). 

![Папка bin](image/1.2.png){#fig:003 width=70%}

3. Клонирование шаблона hugo academic для персонального сайта (рис. @fig:003)

![](image/1.3.png){#fig:003 width=70%}
 
4. Этапы создания нашего сайта (рис. @fig:004) и проверка на локальном уровне (рис. @fig:005).

![Ввод команды](image/1.6.png){#fig:004 width=70%}

![Проверка на локальном уровне](image/1.7.png){#fig:005 width=70%}

5. Создание личного репозитория (рис. @fig:006) и клонирование в Github (рис. @fig:007).

![Создание личного репозитория](image/1.8.png){#fig:006 width=70%}

![Клонирование](image/1.9.png){#fig:007 width=70%}

6. Создание папки Public для продолжения работы (рис. @fig:008)

![Клонирование](image/1.10.png){#fig:008 width=70%}

7. Добавление всех файлов в репозиторий для активации (рис. @fig:009). 

![Комментирование](image/1.11.png){#fig:009 width=70%}

8. Проверка сайта вне системы (рис. @fig:010). 

![Всё работает! ](image/1.12.png){#fig:010 width=70%}
