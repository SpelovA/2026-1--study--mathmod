---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Подготовка лабораторного стенда"
author: "Спелов Андрей Николаевич"

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

Целью данной работы является приобретение практических навыков установки системы на персональный компьютер.

# Выполнение лабораторной работы

Создаем рабочий каталог для всего курса. (рис. [-@fig:001]).

![Создание каталога для курса.](image/1.png){#fig:001 width=70%}

Создаем репозиторий на Git Verse по шаблону. (рис. [-@fig:002]). 

![Создание репозитория](image/2.png){#fig:002 width=70%}

Клонируем репозиторий в свой курс (рис. [-@fig:003]).

![Клонирование репозиторий в свой курс](image/3.png){#fig:003 width=70%}

 Инициализируем курс (рис. [-@fig:004]):

![Инициализируем курс](image/4.png){#fig:004 width=70%}

Настраиваем параметры git (рис. [-@fig:005]):

![Настраиваем параметры git](image/5.png){#fig:005 width=70%}

Установливаем необходимые пакеты (рис. [-@fig:006]):

![Установливаем необходимые пакеты](image/6.png){#fig:006 width=70%}

Переписываем предложенный код (рис. [-@fig:007]):

![Переписываем предложенный код](image/7.png){#fig:007 width=70%}

Выполняем программу (рис. [-@fig:008]).

![Выполняем программу](image/8.png){#fig:008 width=70%}

Переписываем предложенный код (рис. [-@fig:009]).

![Переписываем предложенный код](image/9.png){#fig:009 width=70%}

Выполняем программу (рис. [-@fig:010])

![Выполняем программу](image/10.png){#fig:010 width=70%}

Переписываем предложенный код (рис. [-@fig:011]).

![Переписываем предложенный код](image/11.png){#fig:011 width=70%}

Выполняем программу (рис. [-@fig:012])

![Выполняем программу](image/12.png){#fig:012 width=70%}

Переписываем предложенный код (рис. [-@fig:013]).

![Переписываем предложенный код](image/13.png){#fig:013 width=70%}

Выполняем программу (рис. [-@fig:014])

![Выполняем программу](image/14.png){#fig:014 width=70%}

Просматриваем созданный график (рис. [-@fig:015])

![Просматриваем созданный график](image/15.png){#fig:015 width=70%}

Переписываем предложенный код (рис. [-@fig:016]).

![Переписываем предложенный код](image/16.png){#fig:016 width=70%}

Выполняем программу (рис. [-@fig:017])

![Выполняем программу](image/17.png){#fig:017 width=70%}

Переписываем предложенный код (рис. [-@fig:018]).

![Переписываем предложенный код](image/18.png){#fig:018 width=70%}

Выполняем программу (рис. [-@fig:019])

![Выполняем программу](image/19.png){#fig:019 width=70%}

Запускаем jupyter и выполняем команды (рис. [-@fig:020])

![Запускаем jupyter и выполняем команды](image/20.png){#fig:020 width=70%}

Добавляем строку в report (рис. [-@fig:021])

![Добавляем строку в report](image/21.png){#fig:021 width=70%}

Компилируем отчет (рис. [-@fig:022])

![Компилируем отчет](image/22.png){#fig:022 width=70%}

Переписываем предложенный код (рис. [-@fig:023]).

![Переписываем предложенный код](image/23.png){#fig:023 width=70%}

Выполняем программу (рис. [-@fig:024])

![Выполняем программу](image/24.png){#fig:024 width=70%}

Запускаем jupyter и выполняем команды (рис. [-@fig:025])

![Запускаем jupyter и выполняем команды](image/25.png){#fig:025 width=70%}

Компилируем отчет (рис. [-@fig:026])

![Компилируем отчет](image/26.png){#fig:026 width=70%}

# Выводы

В ходе выполнения лабораторной работы были приобретены практические навыки установки системы на свой пк.

# Список литературы{.unnumbered}

::: {#refs}
:::
