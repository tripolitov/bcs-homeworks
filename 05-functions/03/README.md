# Задача 3. Средние зарплаты

## Описание

Напишите функцию, которая для массива чисел (зарплат) находит два средних:

- среднее арифметическое (сумма всех элементов поделенное на количество элементов)
- медианное среднее (упорядочиваем массив и берем центральное значение, в прямом смысле центральное, если чисел четное количество, то берем любое центральное из двух)

Выведите на экран результат работы функции.

## Заготовка для работы:

```cs
using System;

class Program
{
    // ваша функция здесь

    static void Main(string[] args)
    {
        int[] arr = new int[] {30, 20, 108, 27, 120, 34, 19, 25, 43, 112, 48, 20, 37, 23, 101, 43, 98, 54, 23, 204, 58, 88, 212, 32, 27, 43, 56, 77, 33, 87};

        var result = <название вашей функции>(arr);

        Console.WriteLine(result);
    }
}
```

### Примечание

Для массива из примера:

- среднее арифметическое значение - `63.4`
- медианное значение - `43`.

---

### Подсказка

Для вычисления среднего арифметического стоит вспомнить, как производится деление целочисленных типов и что необходимо сделать, чтобы результатом деления стало дробное число.