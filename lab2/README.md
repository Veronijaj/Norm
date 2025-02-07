## Формулировка индивидуального задания
### Вариант №34. 
Вычислить значение функции в точке при помощи разложения в ряд: 

$\arccos{x}=2\pi-\arcsin{x} = 2\pi-\sum_{n=1}^\infty \cfrac{(2n)!}{4^n(n!)^2(2n+1)}x^{2n+1}$

### Программа № 1
должна обеспечивать возможность вычисления значения функции при 
определённых значениях параметров, указанных пользователем. При этом, пользователь должен 
иметь возможность указать количество членов ряда, которое необходимо использовать при 
вычислениях.

![Diagram1](https://github.com/Veronijaj/Inf/blob/main/lab2/diagram%20(1).png)

### Программа № 2 
должна обеспечивать возможность вычисления значения функции при 
определённых значениях параметров, указанных пользователем. При этом, пользователь должен 
иметь возможность указать точность, с которой должно быть вычислено значение функции

![Diagram2](https://github.com/Veronijaj/Inf/blob/main/lab2/diagram%20(10).png)

# Выводы
В ходе выполнения данной работы на примере программы, выполняющей расчёт арккосинуса были 
рассмотрены базовые принципы работы построения программ на языке C и обработки целых чисел:
1. Организация ввода/вывода.
2. Объявление и использование переменных.
3. Использование условного оператора if и цикла while.
4. Выполнение арифметических операций операндами с плавающей точкой одинарной точности 
(тип данных float).
5. Использование операций библиотеки math.h.
6. Написание отладчика, проверяющего корректность вводимых данных
