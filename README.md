# Итоговая домашняя работа

## Задача

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

## Решение
1. Необходимо создать 2 массива: массив с данными и массив, отображающий длину значений первого массива. 

2. Создать функцию с циклом "for" соразмерным длине массива, условием цикла указать "i<=3", если результат положительный, элемент первого массива заносится в "count" элемент второго массива. Переменная count предназначена для переноса значений из первого массива во второй. После присвоения переменная "count" увеличивается на 1 и возвращается к циклу for в котором "i" увеличивается на 1. И так проверяется до конца.

3. Создать функцию с циклом "for" для вывода перенесенных значений в терминал. Цикл выводит все значения, полученные из шага №2 с помощью команды "Console.Write($"{array[i]} ")"

4. Вызвать созданные функции по порядку.#   I T - I T O G 5 Z D 
 