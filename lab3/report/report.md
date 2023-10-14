---
## Front matter
title: "Отчет по лабораторной работе по предмету Научное программирование"
subtitle: "Лабораторная работа №3. Введение в работу с Octave"
author: "Никита Андреевич Топонен"

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

- Познакомиться с Octave.

# Задание

- Выполнить простейшие математические операции и построить графики с помощью Octave.

# Теоретическое введение

GNU Octave — свободная программная система для математических вычислений, использующая совместимый с MATLAB язык высокого уровня.

Предоставляет интерактивный командный интерфейс для решения линейных и нелинейных математических задач, а также проведения других численных экспериментов. Кроме того, Octave можно использовать для пакетной обработки. Язык Octave оперирует арифметикой вещественных и комплексных скаляров, векторов и матриц, имеет расширения для решения линейных алгебраических задач, нахождения корней систем нелинейных алгебраических уравнений, работы с полиномами, решения различных дифференциальных уравнений, интегрирования систем дифференциальных и дифференциально-алгебраических уравнений первого порядка, интегрирования функций на конечных и бесконечных интервалах. Этот список можно легко расширить, используя язык Octave (или используя динамически загружаемые модули, созданные на Си, C++, Фортране и других).

# Выполнение лабораторной работы

Повторял простейшие математические операции из задания. Также построил графики.

Сначала построил обыкновенный график $y = sin(x)$.

![График $y = sin(x)$](image/1.png){#fig:001 width=70%}

Затем улучшил его изменив цвет и толщину линии, а также добавив название, легенду и решетку.

![Улучшенный график $y = sin(x)$](image/4.png){#fig:002 width=70%}

Далее построил два графика на одном чертеже.

![Два графика на одном чертеже](image/5.png){#fig:003 width=70%}

Затем построил более сложный график $y = x^2*sin(x)$.

![График $y = x^2*sin(x)$](image/graph2.png){#fig:004 width=70%}

Далее сравнил скорость выполнения операций в цикле и векторно. Векторная операция оказалась значительно быстрее.

![Сравнение скорости выполнения](image/6.png){#fig:005 width=70%}

# Выводы

В результате выполнения данной работы я:

- Познакомился с Octave.
- Научился выполнять простейшие математические операции в Octave.
- Научился строить графики и засекать время выполнения программы.

# Список литературы{.unnumbered}
