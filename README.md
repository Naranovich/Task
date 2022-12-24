﻿# Task
Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
Находиться в папке progect

Алгоритм решения:
Делаем перебор значений из исходного массива
Проверяем каждое значение из массива на соответствие условию: длина строки меньше или равна трем
Если строка удовлетворяет условию кладем значение в новый массив
Повторяем пункты 2 и 3 до тех пор пока не достигнем конца исходного массива
Возвращаем новый заполненый массив как результат

Программа:
запустите команду через терминал:dotnet run 
Далее введите значения через пробел, например:

Введите значения через пробел: 2, hello ,world,:)
Пример вывода программы:

[2, hello, world, :)] -> [2, :)]
![2022-12-24_15-20-57](https://user-images.githubusercontent.com/116391432/209436326-484c62d0-e436-4cba-928d-48905c57b9f9.png)
