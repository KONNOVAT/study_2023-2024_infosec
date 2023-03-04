---
## Front matter
title: "Этап 1"
subtitle: "Отчет по Индивидуальному проекту"
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

    Установить необходимое программное обеспечение.
    Скачать шаблон темы сайта.
    Разместить его на хостинге git.
    Установить параметр для URLs сайта.
    Разместить заготовку сайта на Github pages.


# Задание

Размещение на Github pages заготовки для персонального сайта.


# Выполнение отчета


## Скачивание и основные этапы

Скачиваем Hugo, вырезаем файл в папку bin (рис. [-@fig:001]) 


- Клонирование репозитория 

В тероминале делаем git clone --recursive git@github.com:KONNOVAT/road.git (рис. [-@fig:001]) 



- Работа с Hugo

~/bin/hugo


Выгрузили файлы


![Цели и задания. Прописывание элементов](image/1111.png){#fig:001 width=70%}

## Удаление public


Так как данный файл нам пока не нужен, мы удаляем его и еще раз делаем данную команду



~/bin/hugo server



## Открытие сайта и работа с репозиторием 

Переходим на localhost:1313 


Замечу, что синей ошибки у меня не появилось. 


Создаем новый репозиторий с именем konnovat.github.io




git clone --recursive git@github.com:KONNOVAT/konnovat.github.io.git

git checkout -b main


Добавиm README.md



![Этапы работы](image/3331.png){#fig:002 width=70%}


touch README.md


git add .




git commit -am "Добавили README.md"


git push origin




git submodule add -b main git@github.com:KONNOVAT/KONNOVAT.github.io.git public


~/bin/hugo


![Этапы работы](image/ce,.png){#fig:002 width=70%}





![Этапы работы](image/2222png){#fig:002 width=70%}



Комментируем public в gitignore

git submodule add -b main git@github.com:KONNOVAT/KONNOVAT.github.io.git public


~/bin/hugo


cd public/


git remote -v


![Окно терминала](image/3333.png){#fig:003 width=70%}



git add .



git commit -am "Добавили сайт"







Добавили сайт


git push origin




Окончательно преходим на сайт 


KONNOVAT.github.io


![Терминал и  окно](image/4444.png){#fig:004 width=70%}




# Выводы

Мы научились работать с индивидуальным проектом


