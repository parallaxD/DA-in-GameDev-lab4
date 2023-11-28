# DA-in-GameDev-lab4

Отчет по лабораторной работе #4 выполнил(а):
- Куплевацкий Денис Игоревич
- РИ220931

Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
  
- Цель работы

- Задание 1. В проекте Unity реализовать перцептрон, который умеет производить вычисления:
OR | дать комментарии о корректности работы
AND | дать комментарии о корректности работы
NAND | дать комментарии о корректности работы
XOR | дать комментарии о корректности работы

  
- Задание 2. Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.
  
- Задание 3. Построить визуальную модель работы перцептрона на сцене Unity.
  
- Выводы.

## Цель работы
Познакомиться с работой перцептрона при помощи Unity.

## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления:
### OR | дать комментарии о корректности работы
### AND | дать комментарии о корректности работы
### NAND | дать комментарии о корректности работы
### XOR | дать комментарии о корректности работы
 
Ход работы: 
- Операция OR: перцептрон легко обучаем, для обучения необходимо около четырёх эпох.
- Операция AND: перцептрон обучаем, но для обучения необходимо около восьми эпох.
- Операция NAND: перцептрон обучаем, но для обучения необходимо около семи эпох.
- XOR: перцептрон не получается обучить, так как однослойный перцептрон может решать только линейные задачи, а XOR таковой не является.



## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.

OR: ![image](https://github.com/parallaxD/DA-in-GameDev-lab4/assets/81700733/11e78a77-470e-4825-8efb-2f5523544a56)
AND: ![image](https://github.com/parallaxD/DA-in-GameDev-lab4/assets/81700733/e487e0df-b86f-4a24-a51e-f932bd14717d)
NAND: ![image](https://github.com/parallaxD/DA-in-GameDev-lab4/assets/81700733/eced7282-4e17-42d4-a379-570d3f87fd18)
XOR: ![image](https://github.com/parallaxD/DA-in-GameDev-lab4/assets/81700733/1719d25f-08b2-4661-ad1d-00d226d5d3e9)


Проанализировав графики, можно сделать вывод, что минимальное необходимое количество эпох для обучения однослойного перцептрона зависит от сложности логической операции. Например, с операцией OR перцептрон "справляется" быстрее, чем, например, с операцией "AND".



## Выводы

В ходе лабораторной работы я пробовал обучать однослойный перцептрон некоторым логическим операциям (OR, AND, NAND, XOR). С первыми тремя всё прошло успешно, а с XOR перцептрон "не справился". (XOR-проблема, описанная Minsky)

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
