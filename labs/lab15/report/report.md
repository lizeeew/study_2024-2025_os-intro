---
## Front matter
title: "Отчет по выполнению первого этапа индивидуального проекта"
subtitle: "Раздел Операционные системы" 
author: "Репкина Елизавета"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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


# Задание


    Установить необходимое программное обеспечение.
    Скачать шаблон темы сайта.
    Разместить его на хостинге git.
    Установить параметр для URLs сайта.
    Разместить заготовку сайта на Github pages.

#Выполнение

Скачиваю последнюю версию hugo (рис. [-@fig:001])

![Установка](image/1.png){#fig:001 width=70%}

Создаю новый репозиторий(рис. [-@fig:002])

![Создание](image/2.png){#fig:002 width=70%}

Привязываю репозиторий (рис. [-@fig:003])

![команда git clone](image/3.png){#fig:003 width=70%}

Запуск hugo (рис. [-@fig:004])

![Запуск](image/4.png){#fig:004 width=70%}


Удаляяю public (рис. [-@fig:005])

![Удаление](image/5.png){#fig:005 width=70%}

открываю сайт  (рис. [-@fig:006])

![Сайт](image/6.png){#fig:006 width=70%}

Создаю еще один репозиторий (рис. [-@fig:007])

![Создание репозитория ](image/7.png){#fig:007 width=70%}

Клонирую репозиторий (рис. [-@fig:008])

![Клонирование](image/8.png){#fig:008 width=70%}

Создаю ветку main  (рис. [-@fig:009])

![Создание(image/9.png){#fig:009 width=70%}

Создаю файл и отправляю на git  (рис. [-@fig:010])

![Создание файла](image/10.png){#fig:010 width=70%}


Добавляю подмодуль(рис. [-@fig:011])

![Добавление](image/11.png){#fig:011 width=70%}

Запуск Hugo (рис. [-@fig:012])

![Запуск](image/12.png){#fig:012 width=70%}

Компилирую (рис. [-@fig:013])

![Выполнение команд](image/13.png){#fig:013 width=70%}







::: {#refs}
:::
