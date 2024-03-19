# **_Итоговая контрольная работа_** #


## **Задача** ##

    Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## **Алгоритм решения** ##

* Делаем перебор значений из исходного массива;
* Проверяем каждое значение из массива на соответствие условию: длина строки меньше или равна трем;
* Если строка удовлетворяет условию, то кладем значение в новый массив;
* Повторяем пункты 2 и 3 до тех пор, пока не достигнем конца исходного массива;
* Возвращаем новый заполненый массив как результат.

## **Выполнение алгоритма. Блок-схема** ##

![Диаграмма](block.png)

***Выполнение***

1. Для запуска программы выберите файл Program.cs и запустите команду через терминал:
    
 >  dotnet run

2. Далее введите значения через пробел, например:

 >  [“Hello”, “2”, “world”, “:-)”]

3. Пример вывода программы будет выглядеть так:

> [“2”, “:-)”]
