# SEMANA DE LA CIENCIA 2018
## Ficha 2. Algoritmos Recursivos

El objetivo de esta ficha es mostrar la programación de **algoritmos recursivos**.

Una de las funciones recursivas más famosas es factorial: 

![Fórmula 1](F1.png)

Factorial es útil en la composición de permutaciones, por ejemplo. El cálculo es sencillo y su veremos que el código en un lenguaje de programación es casi cortar y pegar la fórmula matemática.

Otra función recursiva un poquito más difícil es la que hemos mostrado en la presentación. La sucesión de Fibonacci: 

![Fórmula 2](F2.png)

Sucesión de Fibonacci: **1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, …**

Una primera implementación puede ser precisamente la fórmula matemática con recursión doble, pero veremos que es muy poco eficiente, pues ni siguiera un buen ordenador será capaz de calcular el Fibonacci de 50, por ejemplo.

Con ayuda de las matemáticas y de la imaginación vamos a implementar otra solución que calcula cualquier Fibonacci en tiempo record, lo que llamamos ‘tiempo real’.
![Fórmula 3](F3.png)
Para calcular números de Fibonacci con esta función hacemos: fib_final(n, 0,1)  
![Gráfico](Graf.png)

En la práctica implementaremos varios algoritmos con diferentes complejidades como se marca en esta gráfica.

<span style="color:red">Rojo</span>: El tiempo de ejecución es tan alto que no podríamos vivir para conocer el resultado.

<span style="color:blue">Azul</span>: El tiempo de ejecución es proporcional al número que actúa como input.

<span style="color:green">Verde</span>: El tiempo de ejecución será el logaritmo del número actúa como input. 