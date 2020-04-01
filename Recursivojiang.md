# <span style="color:royalblue">SEMANA DE LA CIENCIA 2018</span>
# <span style="color:royalblue">Ficha 2. Algoritmos Recursivos</span> 

El objetivo de esta ficha es mostrar la programación de **algoritmos recursivos**.

Una de las funciones recursivas más famosas es factorial:  

![sin titulo](https://i.loli.net/2020/02/25/YquSFQLtrZ7XB25.png)

Factorial es útil en la composición de permutaciones, por ejemplo. El cálculo es sencillo y su veremos que el código en un lenguaje de programación es casi cortar y pegar la fórmula matemática. 

Otra función recursiva un poquito más difícil es la que hemos mostrado en la presentación. La sucesión de Fibonacci:  

<img src="https://i.loli.net/2020/02/25/zENjUcgsvPSGleb.png" alt="sin titulo" style="zoom:67%;" /><img src="https://i.loli.net/2020/02/25/FGUbtuD5hMpcyEL.png" alt="Sin titulo" style="zoom:67%;" />

Sucesión de Fibonacci: **1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, …**

Una primera implementación puede ser precisamente la fórmula matemática con recursión doble, pero veremos que es muy poco eficiente, pues ni siguiera un buen ordenador será capaz de calcular el Fibonacci de 50, por ejemplo. 

Con ayuda de las matemáticas y de la imaginación vamos a implementar otra solución que calcula cualquier Fibonacci en tiempo record, lo que llamamos ‘tiempo real’. 

![sin titulo](https://i.loli.net/2020/02/25/dSBUmXTPNzcEhji.png)

Para calcular números de Fibonacci con esta función hacemos: fib_final(n, 0,1)   

![Sin titulo](https://i.loli.net/2020/02/25/Xh74jeND5EFdSPb.png)

En la práctica implementaremos varios algoritmos con diferentes complejidades como se marca en esta gráfica. 

<span style="color:red">Rojo</span>: El tiempo de ejecución es tan alto que no podríamos vivir para conocer el resultado.

<span style="color:blue">Azul</span>: El tiempo de ejecución es proporcional al número que actúa como input.

<span style="color:green">Verde</span>: El tiempo de ejecución será el logaritmo del número actúa como input.  