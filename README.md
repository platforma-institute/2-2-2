#Модуль 2. Занятие 2. Задание 2.
Напишите класс Sorter. Экземпляр этого класса конструктор которого получает массив целых чисел. Вызов метода getOdds возвращает нечётные <br/>числа из первоначального массива, вызов getEvens возвращает чётные числа из первоночального массива.<br/>
Порядок чисел менять нельзя. Они должны соответствовать изначальному массиву<br/>
<br/>
Вводные данные:<br/>
```java
int[] arrs = {21, 42, 19, 18, 27, 30, 8, 28, 24, 71, 89};
Sorter sorter = new Sorter(arrs);
int[] odds = sorter.getOdds();
int[] evens = sorter.getEvens();
for (int i : odds)
    System.out.print(i + " ");
System.out.println();
for(int i : evens)
    System.out.print(i + " ");
```

Выходные данные:<br/>
11 19 27 71 89 <br/>
42 18 30 8 28 24 <br/>
