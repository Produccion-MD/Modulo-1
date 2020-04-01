
# SEMANA DE LA CIENCIA 2018

# Ficha 2. Algoritmos Recursivos


==El objetivo de esta ficha es mostrar la programación de **algoritmos recursivos**.==

Una de las funciones recursivas más famosas es factorial:

<a href="https://ibb.co/y0163sm"><img src="https://i.ibb.co/8Mprh8n/formel1.jpg" alt="formel1" border="0" /></a>

**Factorial** es útil en la composición de permutaciones, por ejemplo. El cálculo es sencillo y su veremos que el código en un lenguaje de programación es casi cortar y pegar la fórmula matemática.

Otra función recursiva un poquito más difícil es la que hemos mostrado en la presentación. 



La sucesión de Fibonacci:

<a href="https://ibb.co/dk4zf85"><img src="https://i.ibb.co/ss9Mg8V/formel2.jpg" alt="formel2" border="0"></a>

Sucesión de Fibonacci:  1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, …
![fibunacci](https://www.natuerlich-online.ch/uploads/_processed_/9/f/csm_38_titel_n_88d85803ed.jpg)

Una primera implementación puede ser precisamente la fórmula matemática con recursión doble, pero veremos que es muy poco eficiente, pues ni siguiera un buen ordenador será capaz de calcular el Fibonacci de 50, por ejemplo.

Con ayuda de las matemáticas y de la imaginación vamos a implementar otra solución que calcula cualquier Fibonacci en tiempo record, lo que llamamos ‘tiempo real’.

<a href="https://ibb.co/5FkzcVD"><img src="https://i.ibb.co/0tKWJ3N/formel3.jpg" alt="formel3" border="0"></a>
Para calcular números de Fibonacci con esta función hacemos: *_fib_final(n, 0,1)_*

<a href="https://ibb.co/HT0Cn2Z"><img src="https://i.ibb.co/7tHQ2zh/formel4.jpg" alt="formel4" border="0"></a>
En la práctica implementaremos varios algoritmos con diferentes complejidades como se marca en esta gráfica.

- Rojo: El tiempo de ejecución es tan alto que no podríamos vivir para conocer el resultado.
- Azul: El tiempo de ejecución es proporcional al número que actúa como input.
- Verde: El tiempo de ejecución será el logaritmo del número actúa como input.


