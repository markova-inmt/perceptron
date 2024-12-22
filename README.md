# perceptron
# ПЕРЦЕПТРОН
Отчет по лабораторной работе #4 выполнил(а):
- Маркова Дарья Сергеевна
- НМТ-233511
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * |  |
| Задание 2 | * |  |
| Задание 3 | * |  |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## Цель работы
Познакомиться с принципом работы перцептрона.
## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления or, and, nand, xor.
Создать пустой проект на Unity, добавить пустой объект Empty Game Object с именем Perceptron, подключить Perceptron.cs к пустому Game Object с именем Perceptron. Для перцептрона вводим необходимые значения входа и выхода для or,and, nand, xor. 
![image](https://github.com/user-attachments/assets/98c8124a-82b9-4a49-b2df-634faa578bad)

![image](https://github.com/user-attachments/assets/e60d231b-b71c-4e30-a861-801424bf98eb)
Для or при 8 эпохах перцептрон выдает корректный результат.

![image](https://github.com/user-attachments/assets/ceae9b7b-b041-4467-b600-0658a8fa8d6f)

![image](https://github.com/user-attachments/assets/ec596aca-7fe3-4a69-9835-c2827c93f5b2)

Аналогично для and при 8 эпохах результат корректен.

![image](https://github.com/user-attachments/assets/9589a983-a396-45f0-8de8-dfc7cf78b580)

![image](https://github.com/user-attachments/assets/c3e06ac0-c115-478a-b1bc-2d814325a438)

 Аналогично для nand

![image](https://github.com/user-attachments/assets/20b3ab36-d2bb-4570-bd35-ba61897e5f0a)

 ![image](https://github.com/user-attachments/assets/3e3bc7dd-8052-4146-8e94-b29a4518d5a0)
 
Для xor конечное число ошибок растет, потому что эта логическая операция не может быть выполнена из-за линейного характера перцептрона. Перцептрон не обучился


## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.

![image](https://github.com/user-attachments/assets/186da015-15b8-4037-a5f3-7411142c202a)
https://docs.google.com/spreadsheets/d/1WuPTmSrn0ttIXCLmDSNaoTkDvtdCJ_sjjbxeg3CKnNo/edit?gid=0#gid=0

В проведенных опытах для or, and, nand концептрон обучается к 3-4 эпохе, для xor независимо от числа эпох концептрон не может обучиться. Необходимое число эпох зависит от смещения и веса.


## Задание 3
### Построить визуальную модель работы перцептрона на сцене Unity.

![image](https://github.com/user-attachments/assets/deba4992-8645-4cb5-832c-21caa687fc25)

![image](https://github.com/user-attachments/assets/1cbfc3cb-3f8a-47a3-9382-3343bcdb6509)

В проект с перцептроном добавляю 2 куба, черный эквивалентен единице, белый нулю. В зависимости от логического оператора (or, and, nand, xor) в результате куб который мы видим после падения будет окрашиваться в ченый или белый цвет. Для xor, в отличие от остальных, перцептрон будет работать некорректно. 


## Выводы

В ходе работы мы познакомились с работой перцептрона и его областью применения, научились реализовать перцептрон на Юнити.

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
