---
title: 📝💻 \latex 💻📝
summary: Ни дня без латеха
date: 2024-10-04

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'

featured: true 

authors:
  - admin

tags:
  - Жизнь в науке
  - Домашнее задание
  - Работа
---

Добро пожаловать 👋

{{< toc mobile_only=true is_open=true >}}

## LaTex -- это язык разметки

Язык разметки -- набор символов или последовательностей символов, вставляемых в текст для передачи информации о его отображении или строении. Принадлежит классу компьютерных языков. Текстовый документ, написанный с использованием языка разметки, содержит не только сам текст (как последовательность слов и знаков препинания), но и дополнительную информацию о различных его участках -- например, указание на заголовки, выделения, списки и т. д.

Идея языков разметки появилась в 1967 и уже в  1980х Дональд Кнут создал язык разметки Tex, который оказался настолько мощным, что до сих пор лежит в основе широко используемых систем, таких как LaTex, являющийся макропакетом языка TeX.

## Функции LaTex 

LaTex позволяет авторам заботиться только о содержании документа и его логической 
структуре. LaTex в свою очередь проводит    
- нумерацию разделов и формул,    
- размещение ссылок,     
- размещение иллюстраций и таблиц,    
- оформление математических формул,    
- расстановку переносов,    
- определение междусловных пробелов,   
- балансировку текста в абзацах,   
- генерацию содержания, списка иллюстраций, таблиц,    
- оформление алгоритмов, исходных текстов с синтаксической подсветкой,   
- ведение библиографии и др.    

## Технические детали

Как обычно, чтобы воспользоваться замечательным функциональным инструментом, вы должны пройти процесс установки, который часто бывает не очень простым. Но речь не о LaTeX. Его установка довольно проста и прозрачна. Разберем детали установки.

### Дистрибутивы

LaTeX является свободным ПО, поэтому каждый волен распространять его по  своему. На данный момент существует два основных дистрибутива:     
1. TeXLive --- основной дистрибутив, поддерживает Win/Mac/Lin, вустановленном виде (3-4 Гб).
2. MiKTex --- дистрибутив доступный только под MS Windows, предлагает динамическую загрузку недостающих пакетов при сборке. Малый вес в 
установленном виде, требует интернет для дозагрузки пакетов. 
Пользователи иногда жалуются что дозагрузка весьма медленная (типовая 
установка 500-800 мБ).
Также доступны MacTeX и ProTEXt, являющиеся расширениями дистрибутивов 
TeXLive и MiKTex соответственно

### Compilers 

there are four main Latex compilers:

- LaTeX. It only supports the image file formats .eps and .ps. If all images in your project are in the .eps format, it is recommended to use the This compiler.    
- PDFLaTeX. It supports image formats such as .png, .jpg, and .pdf, and converts .eps images to .pdf during the compilation process, which may increase the required time for compilation.    
- XeLaTeX and LuaLaTeX, "out of the box", reliably support UTF-8 as well as TrueType and OpenType fonts. Therefore, they are recommended if you need to use non-Latin characters. They also support image formats such as .png, .jpg, .pdf, and .eps.    
XeLaTeX supports PStricks, while LuaLaTeX does not.     

## Usage

Personally, I use LaTeX almost every day. I write my homework, my work, and my notes using LaTeX. I also write presentations using LaTeX. For me, it is convenient and fast, and I enjoy the beautiful results. Mostly, I use the Overleaf online editor for LaTeX, but I also have a lot of LaTeX notes inside my Jupyter notebooks. I use Microsoft PowerPoint, where I can draw my figures, to create presentations with LaTeX formulas. I only used a local LaTeX repository once, when preparing my graduation work. I recommend LaTeX to everyone. Give it a try and you will love it for all time!