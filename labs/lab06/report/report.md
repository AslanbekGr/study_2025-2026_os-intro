
---
## Front matter
title: "Лабараторная работа 6"
subtitle: "Простейший вариант"
author: "Хайманов Асланбек Султанович"

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

# Цель работы

Основы интерфейса Unix

# Задание

- Перейти в каталог /tmp и вывезти содержимое. Определить есть ли в каталоге /var/spool подкаталог cron. Перейти в домашний каталог и вывезти его содержимое. Создать каталог newdir.

- Создать новый каталог morefun и одной командой letters memos misk а затем удалить их. Попробовать удалить каталог newdir командой rm. Удалить каталог newdir и проверить это.

- Команда для просмотра содержимого каталога и подкаталога 

- Использование history

# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. [-@tbl:std-dir] приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                                                                                 |

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы


## Перейти в каталог /tmp и вывезти содержимое. Определить есть ли в каталоге /var/spool подкаталог cron. Перейти в домашний каталог и вывезти его содержимое. Создать каталог newdir.

![Этапы 2.1-3.1](image/1.png){#fig:001 width=100%}

## Создать новый каталог morefun и одной командой letters memos misk а затем удалить их. Попробовать удалить каталог newdir командой rm. Удалить каталог newdir и проверить это.

![Этапы 3.2-3.5](image/2.png){#fig:002 width=100%}

## Команда для просмотра содержимого каталога и подкаталога 
![Этапы 4-5](image/3.png){#fig:003 width=100%}

## Использование history
![Этапы 6-7](image/4.png){#fig:004 width=100%}
# Выводы

В процессе выполнения лабараторной работы ознакомился с интерфейсом unix

# Список литературы{.unnumbered}

::: {#refs}
:::
