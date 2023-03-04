---
## Front matter
title: "Markdown"
subtitle: "Лабораторная работа № 3"
author: "Коннова Татьяна Алексеевна"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown

# Задание

- Сделать отчёт по предыдущей лабораторной работе в формате Markdown.
- В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)



# Выполнение лабораторной работы


## Титульный лист


Кликаем на файл report.md и начинаем полноценную работу с ним: указываем автора работы, номер, название лабораторной. (рис. [-@fig:001]) 

![Титульный лист](image/1фио.png){#fig:001 width=70%}

## Представленные цели и поставленное задание

Указываем цели и задание лабораторной работы: (рис. [-@fig:002]) 

![Цели и задания. Прописывание элементов](image/222.png){#fig:002 width=70%}


## Основная часть выполнения

Переходим к ходу выполнения основной части лабораторной работы: (рис. [-@fig:003]) 

![Выполнение основной части лабораторной работы №2](image/333.png){#fig:003 width=70%}

## Ответы на представленные задания на Самостоятельную работу  
Мы предоставляем ответы на контрольные вопросы и на домашнее задание: (рис. [-@fig:004]) 

![Предоставление ответов на самостоятельную работу](image/444.png){#fig:004 width=70%}




## Команда make
Выполняется команда make и из формата md формируются pdf, docx, стоит отметить наличие папки pandoc. (рис. [-@fig:005]) 

![Формирование отчетов в двух доп. форматах](image/666.png){#fig:005 width=70%}



## Формирование объединяющего zip-формата

Сжимаем папку отчета. (рис. [-@fig:006]) 

![zip-формат](image/зип4.png){#fig:006 width=40%}



## Предоставление выводов в работе

Предоставляем выводы, соответствующие поставленным перед нами целям работы (рис. [-@fig:007]) 

![Предоставление выводов в  работе](image/555.png){#fig:007 width=70%}

# Выводы

Мы научились оформлять отчёты с помощью легковесного языка разметки Markdown


