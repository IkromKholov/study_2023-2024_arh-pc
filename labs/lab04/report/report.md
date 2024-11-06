---
## Front matter
title: "Лабораторная работа"
subtitle: "Выполнил"
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

Освоил процедуры компиляции и сборки программ, написанных на ассемблере NASM.

# Выполнение лабораторной работы

1. Создал каталог лаб04 и перешел в него (рис. [-@fig:001]).

![1](image/1.png){#fig:001 width=70%}

2. Создал файл hello.asm (рис. [-@fig:002]).

![2](image/2.png){#fig:002 width=70%}

3. Открыл файл и ввел текст (рис. [-@fig:003]).

![3](image/3.png){#fig:003 width=70%}

4. Скомпилировал объект с помощью nasm и Скомпилировал объект obj.o из hello.asm (рис. [-@fig:004]).

![4](image/4.png){#fig:004 width=70%}

5. Скомпановал объект hello.o и Скомпанвал объект obj.o в файл main. (рис. [-@fig:007]).

![6](image/5.png){#fig:007 width=70%}

6. Запустил файл hello (рис. [-@fig:008]).

![6](image/6.png){#fig:008 width=70%}

7. Скопировал файл hello.asm в lab4.asm (рис. [-@fig:009]).

![7](image/7.png){#fig:009 width=70%}

8. С помощью gedit изменил lab4.asm так, что теперь он выводит мои фамилию и имя (рис. [-@fig:010]).

![8](image/8.png){#fig:010 width=70%}

9. Оттранслировал lab4.asm в объектный файл, выполнил компановку и запустил исполняемый файл (рис. [-@fig:011]).

![9](image/9.png){#fig:011 width=70%}

10. Создал каталог лаб04 и перешел в него (рис. [-@fig:012]).

![10](image/10.png){#fig:012 width=70%}

# Выводы

Благодаря этой лабораторной я освоил процедуру компиляции и сборку программ, написанных на ассемблере NASM


