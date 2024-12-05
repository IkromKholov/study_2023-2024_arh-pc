---
## Front matter
title: "Лабараторная работа №08. НКАбд-01-24"
subtitle: "Подготовил:"
author: "Холов Икром Комронович"

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

Освоить написание программ с использованием циклов и обработкой аргументов командной строки.

# Выполнение лабораторной работы

1. Создал каталог для программ, перешел в него и создал файл lab8-1.asm (рис. [-@fig:001])

![Создал lab08-1.asm](image/Создал_lab08-1.png){#fig:001}

2. Заполнил lab8-1.asm (рис. [-@fig:002])

![Заполнил lab08-1](image/Заполнил_lab08-1.png){#fig:002}

3. Создал исполняемый файл и запустил его (рис. [-@fig:003])

![Проверил lab08-1](image/Проверил_lab08-1.png){#fig:003}

4. Изменил текст программы (рис. [-@fig:004])

![Изменил_lab08-11](image/Изменил_lab08-1.png){#fig:004}

5. Создал исполняемый файл и запустил его (рис. [-@fig:005])

![Проверил_измененный_lab08-1](image/Проверил_измененный_lab08-1.png){#fig:005}

6. Изменил текст программы, с использованием стека в программу для сохранения корректности работы программы (рис. [-@fig:006])

![Исправил_lab08-1](image/Исправил_lab08-1.png){#fig:006}

7. Проверка выполнения (рис. [-@fig:007])

![Проверил_исправление](image/Проверил_исправление.png){#fig:007}

8. Создал файл lab8-2.asm (рис. [-@fig:008])

![Создал_lab08-2](image/Создал_lab08-2.png){#fig:008}

9. Заполнил lab8-2.asm (рис. [-@fig:009])

![Заполнил lab08-2](image/Заполнил_lab08-2.png){#fig:009}

10. Создал исполняемый файл и запустил его, указав аргументы. Программа обработала 4 аргумента (рис. [-@fig:010])

![Проверил_lab08-2](image/Проверил_lab08-2.png){#fig:010}

11. Создал файл lab8-3.asm (рис. [@-fig:011])

![Создал lab08-3.asm](image/Создал_lab08-3.png){#fig:011}

12. Заполнил lab8-3.asm (рис. [-@fig:012])

![Заполнил lab08-3.asm](image/Заполнил_lab08-3.png){#fig:012}

13. Создал исполняемый файл и запустил его (рис. [-@fig:013])

![Проверил lab08-3.asm](image/Проверил_lab08-3.png){#fig:013}

14. Изменил текст программы для вычисления произведения аргументов командной строки (рис. [-@fig:014])

![Изменил_lab08-3](image/Изменил_lab08-3.png){#fig:014}

15. Проверка программы (рис. [-@fig:015])

![Проверил_измененную_lab08-3](image/Проверил_измененную_lab08-3.png){#fig:015}

# Задание для самостоятельной работы 

1. Программа для нахождения вычисления значений функции f(x) для разных x (рис. [-@fig:016]) (рис. [-@fig:017])

![Заполнил_hw](image/Заполнил_hw.png){#fig:016}

![Проверил_hw](image/Проверил_hw.png){#fig:017}

# Выводы

Освоил программу с использованием циклов и обратки аргументов комадной строки

