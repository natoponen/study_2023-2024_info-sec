---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Системы линейных уравнений
author:
  - Топонен Н. А.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 23 октября 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Топонен Никита Андреевич
  * студент Российского университет дружбы народов
  * [1132236933@rudn.ru](mailto:1132236933@rudn.ru)
  * <https://github.com/natoponen>

:::
::: {.column width="30%"}

![](./image/unknown.jpg)

:::
::::::::::::::

# Вводная часть

## Цель работы

- Научиться решать СЛАУ с помощью Octave.

## Задание

- Повторить примеры решения СЛАУ с помощью Octave.

# Теоретическое введение

С помощью Octave можно:

- Решать СЛАУ методом Гаусса (как "в ручную", так и встроенной функцией);
- Решать СЛАУ левым делением;
- Находить LUP разложение.

# Выполнение лабораторной работы

## Метод Гаусса

![Приведение матрицы к верхнему треугольному виду "в ручную"](image/3.png){#fig:001 width=30%}

## Метод Гаусса

![Приведение к верхнему треугольному виду встроенной функции](image/4.png){#fig:002 width=70%}

## Левое деление

![Решение СЛАУ левым делением](image/5.png){#fig:003 width=30%}

## Нахождение LUP-разложения

![Нахождение LUP разложения](image/6.png){#fig:004 width=30%}

## Выводы

- Научился решать СЛАУ в Octave.