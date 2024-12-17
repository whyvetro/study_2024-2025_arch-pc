---
## Front matter
title: "Отчет по лабораторной работе №4"
subtitle: "Создание и процесс обработки программ на языке ассемблера NASM"
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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.

                           

# Выполнение лабораторной работы

Я перешла в созданный каталог,создала текстовый файл hello.asm и ввела в него заданный текст.

![Hello.asm](image/image1.png){#fig:001 width=70%}

Для компиляции текста я ввела заданную команду и проверила созданный файл, который имеет имя hello.o.

![Создание объектного файла]((image/image2.png){#fig:002 width=70%}

Затем я скомпилировала исходный файл hello.asm в obj.o и проверила созданные файлы.

![obj.o](image/image3.png){#fig:003 width=70%}

Далее я передала объектный файл на обработку компоновщику и проверила наличие исполняемого файла.

![Исполняемый файл](image/image4.png){#fig:004 width=70%}

Я передала на обработку файл obj.o и проверила наличие исполняемого файла.

![main](image/image5.png){#fig:005 width=70%}

Затем я запустила исполняемый файл hello.

![hello](image/image6.png){#fig:006 width=70%}

# Задания для самостоятельной работы 

С помощью команды cp я скопировала файл hello.asm d afqk с именем lab4.asm

![Копирование файла](image/image7.png){#fig:007 width=70%}

и ввела в созданный файл изменения.

![Измененный текст](image/image8.png){#fig:008 width=70%}

Затем я оттранслировала текст программы, провела компоновку и запустила исполняемый файл.

![Работа программы](image/image9.png){#fig:009 width=70%}

Я скопировала файлы hello.asm и lab4.asm в каталог и проверила их наличие.

![Копирование в каталог](image/image11.png){#fig:010 width=70%}

![Наличие файлов](image/image10.png){#fig:011 width=70%}


# Выводы

Я освоила процедуры компиляции и сборки программ, написанных на ассемблере.



