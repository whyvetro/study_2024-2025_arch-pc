---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Система контроля версий Git"
author: "Полина Алексеевна Ларионова"

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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью работы является изучить идеологию и применение средств контроля версий. Приобрести практические навыки по работе с системой git.


# Выполнение лабораторной работы

После создания учетной записи на Github я настроила нужные конфигурации.

![Конфигурации](image/image1.png){#fig:001 width=70%}

Я сгенерировала пару ключей  и внесла открытый ключ в буфер обмена.

![Генерация ключей](image/image2.png){#fig:002 width=70%}

Затем я вставила его на сайте.

![Ssh-key]((image/image3.png){#fig:003 width=70%}

В терминале я создала каталог для предмета "Архитектура компьютера".

![Каталог](image/image4.png){#fig:004 width=70%}

На сайте я создала свой репозиторий.

![Репозиторий](image/image5.png){#fig:005 width=70%}

Потом я перешла в каталог курса и клонировала репозиторий.

![Клонирование](image/image6.png){#fig:006 width=70%}

Я перешла в каталог курса, удалила лишние файлы

![Удаление файлов](image/image7.png){#fig:007 width=70%}

создала необходимые каталоги 

![Создание каталогов](image/image8.png){#fig:008 width=70%}

и отправила файлы на сервер.

![Отправка файлов на сервер](image/image9.png){#fig:009 width=70%}

# Задания для самостоятельной работы 

Я создала отчет по выполнению лабораторной работы в формате Markdown. 

# Выводы

Я изучила идеологию и применение средст контроля и приобрела практические навыки по работе с системой git.


