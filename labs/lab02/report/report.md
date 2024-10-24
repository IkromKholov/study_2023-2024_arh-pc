---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Подготовил"
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

Цель данной работы заключается в изучении концепции и исследования
систем контроля версий, а так же приобретения практических навыков
работы с системой git.

# Выполнение лабораторной работы

1. Указание имя и email владельца репозитория (рис.[-@fig:001])

![1](image/1.png){#fig:001 width=100%}

2.  Настроил utf-8 в выводе сообщений (рис. [-@fig:002]) 

![2](image/2.png){#fig:002}

3. Задал имя начальной ветки (рис. [-@fig:003])

![3](image/3.png){#fig:003}

4. Настроил параметры autocrIf и safecrIf [-@fig:004])

![4](image/4.png){#fig:004}

5. Создание SSH ключа (рис. [-@fig:005])

![5](image/5.png){#fig:005}

6. Скопировал ключ в буфер обмена (рис. [-@fig:006])

![6](image/6.png){#fig:006}

7. Добавил ключ на сайт
Создание рабочего пространства и репозитория
курса на основе шаблона (рис. [-@fig:007])

![7](image/7.png){#fig:007}

8. Создал каталог для предмета “Архитектура компьютера” (рис. [-@fig:008])

![8](image/8.png){#fig:008}

9. Создаю репозиторий на основе шаблона (рис. [-@fig:009])

![9](image/9.png){#fig:009}

10. Вписываю название и создаю репозиторий (рис. [-@fig:010])

![10](image/10.png){#fig:010}

11. Перешел в папку “Архитектура компьютера” (рис. [-@fig:011])

![11](image/11.png){#fig:011}

12. Клонировал созданный репозиторий (рис. [-@fig:012])

![12](image/12.png){#fig:012}

13. Настройка каталога курса (рис. [-@fig:013])

![13](image/13.png){#fig:013}

14. Перешел в каталог курса (рис. [-@fig:014])

![14](image/14.png){#fig:014}

15. Удалил лишние файлы (рис. [-@fig:015])

![15](image/15.png){#fig:015} 

16. Создал нужные каталоги (рис. [-@fig:016])

![16](image/16.png){#fig:016}

17. Oтправляю файлы на сервер (рис. [-@fig:017])

![17](image/17.png){#fig:017}

18. Создал каталог для отчета (рис. [-@fig:018])

![18](image/18.png){#fig:018}

19. Переместил созданный отчет из загрузок в каталог report (рис. [-@fig:019])

![19](image/19.png){#fig:019}

20. Создал папку для отчета о первой лабораторной (рис. [-@fig:020])

![20](image/20.png){#fig:020}

21. Загрузил файла на github (рис. [-@fig:021])

![21](image/21.png){#fig:021}

# Вывод

Изучил идеологию и как применять средства
контроля версий. Научился на практике, как
работать с git.




