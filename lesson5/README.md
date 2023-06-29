# Знакомство с языком программирования C# (семинары)

## Урок 5. Функции и одномерные массивы

### Задача 1. Задайте массив из N элементов, заполненный случайными числами из промежутка [-9, 9]. Найдите сумму отрицательных и положительных элементов массива. 

Например, 
``` в массиве `[3,9,-8,1,0,-7,2,-1,8,-3,-1,6]` сумма положительных чисел равна 29, сумма отрицательных равна -20.```

### Задача 2. Напишите программу замена элементов массива: положительные элементы замените на соответствующие отрицательные, и наоборот.

```[-4, -8, 8, 2] -> [4, 8, -8, -2]```

### Задача 3. Задайте массив. Напишите программу, которая определяет, присутствует ли заданное число в массиве.
```
4; массив [6, 7, 19, 345, 3] -> нет
-3; массив [6, 7, 19, 345, 3] -> да
```

### Задача 4. Задайте одномерный массив из 123 случайных чисел. Найдите количество элементов массива, значения которых лежат в отрезке [10,99].

Пример для массива из 5, а не 123 элементов. В своём решении сделайте для 123
```
[5, 18, 123, 6, 2] -> 1
[1, 2, 3, 6, 2] -> 0
[10, 11, 12, 13, 14] -> 5
```

### Задача 5. Найдите произведение пар чисел в одномерном массиве. Парой считаем первый и последний элемент, второй и предпоследний и т.д. Результат запишите в новом массиве.
```
[1 2 3 4 5] -> 5 8 3
[6 7 3 6] -> 36 21
```


## Домашнее Задание урока 5

### Задача 1. Задайте массив заполненный случайными положительными трёхзначными числами. Напишите программу, которая покажет количество чётных чисел в массиве.
```
[345, 897, 568, 234] -> 2
```

### Задача 2. Задайте одномерный массив, заполненный случайными числами. Найдите сумму элементов, стоящих на нечётных позициях.
```
[3, 7, 23, 12] -> 19
[-4, -6, 89, 6] -> 0
```

### Задача 3. Задайте массив вещественных чисел. Найдите разницу между максимальным и минимальным элементов массива.
```
[3.22, 4.2, 1.15, 77.15, 65.2] => 77.15 - 1.15 = 76
```


#### Рекомендуемая литература:

* Книга, по которая помогает пройти собеседование на C# Junior: "CLR via C#. Программирование на платформе Microsoft .NET", `автор` Рихтер Дж.