---
## Front matter
title: "Лабораторная работа №3."
subtitle: "Подготовил:"
author: "Холов Икром"

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

Целью работы является освоение процедуры оформления отчетов, с помощью Markdown

# Выполнение лабораторной работы

1. Окртыл терминал (рис.[-@fig:001])

![open_ter](image/open_ter.png){#fig:001 width=100%}

2. Перешел в каталог курса и обновил локальные депозиторий (рис. [-@fig:002]) (рис. ([-@fig:003])

![go_to_arcpc.png](image/go_to_arcpc.png){#fig:002}

![git_pull.png](image/git_pull.png){#fig:003}

3. Перешел в каталог с отчетом  (рис. [-@fig:004])

![go_to_report.png](image/go_to_report.png){#fig:004}

4. Провел компиляцию шаблона с помощью Makefile (рис. [-@fig:005])

![make_1.png](image/make_1.png){#fig:005}

5. Удалил файлы созданные make и убедился в этом с поомщью ls (рис. [-@fig:006])

![make_clean.png](image/make_clean.png){#fig:006}

6. Открыл файл  report.md и внимательно изучил его (рис. [-@fig:007])

![report.md.png](image/report.md.png){#fig:007}

# Вывод

Я изучил формаровние отчетов и компелирование их с использованием Makefile

