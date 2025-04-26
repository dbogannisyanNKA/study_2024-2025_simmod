---
## Front matter
lang: ru-RU
title: Лабораторная работа №12
subtitle: Пример моделирования простого протокола передачи данных
author:
  - Оганнисян Д. Б.
institute:
  - Российский университет дружбы народов, Москва, Россия

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
::: {.column width="60%"}

  * Оганнисян Давит Багратович
  * студент
  * Российский университет дружбы народов
  * [1132226440@pfur.ru](mailto:1132226440@pfur.ru)
  * <https://dbogannisyanNKA.github.io/ru/>

:::
::: {.column width="25%"}

![](./image/1000005793.png)

:::
::::::::::::::

## Цели и задачи

**Цель работы**

Реализовать простой протокол передачи данных в CPN Tools.

**Задание**

- Реализовать простой протокол передачи данных в CPN Tools.
- Вычислить пространство состояний, сформировать отчет о нем и построить граф.

## Выполнение лабораторной работы

![Задание деклараций](image/1.png){#fig:001 width=70%}

## Выполнение лабораторной работы

![Начальный граф](image/2.png){#fig:002 width=60%}

## Выполнение лабораторной работы

![Добавление промежуточных состояний](image/3.png){#fig:003 width=60%}

## Выполнение лабораторной работы

![Задание деклараций](image/4.png){#fig:004 width=70%}

## Выполнение лабораторной работы

![Модель простого протокола передачи данных](image/5.png){#fig:005 width=70%}

## Выполнение лабораторной работы

![Запуск модели простого протокола передачи данных](image/6.png){#fig:006 width=70%}

## Упражнение

```
 Statistics
------------------------------------------------------------------------

  State Space
     Nodes:  13341
     Arcs:   206461
     Secs:   300
     Status: Partial

  Scc Graph
     Nodes:  6975
     Arcs:   170859
     Secs:   14
```

## Упражнение

```
 Boundedness Properties
------------------------------------------------------------------------

  Best Integer Bounds
                             Upper      Lower
     Main'A 1                20         0
     Main'B 1                10         0
     Main'C 1                6          0
     Main'D 1                5          0
     Main'NextRec 1          1          1
     Main'NextSend 1         1          1
     Main'Reciever 1         1          1
     Main'SA 1               1          1
     Main'SP 1               1          1
     Main'Send 1             8          8
```

## Упражнение

![Пространство состояний для модели простого протокола передачи данных](image/7.png){#fig:007 width=70%}

## Выводы

В процессе выполнения данной лабораторной работы я реализовал простой протокол передачи данных в CPN Tools и провел  анализ его пространства состояний.
