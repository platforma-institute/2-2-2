# 2-2-2
Модуль 2. Занятие 2. Задание 2.
Напишите класс Selector. Экземпляр этого класса при инициализации получает массив целых чисел. Вызов метода getOdds возвращает нечётные числа из первоначального массива, вызов getEvens — чётные.
Числа должны идти в том же порядке, в котором они были в изначальном массиве.

Вводные данные:<br/>
```java
int[] values = {11, 12, 13, 14, 15, 16, 22, 44, 66};
Selector selector = new Selector(values);
int[] odds = selector.getOdds();
int[] evens = selector.getEvens();
for (int i : odds)
    System.out.print(i + " ");
System.out.println();
for(int i : evens)
    System.out.print(i + " ");
```

Выходные данные:<br/>
11 13 15 <br/>
12 14 16 22 44 66 <br/>
