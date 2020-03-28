<center>
# <span style="color:steelblue">SEMANA DE LA CIENCIA 2018</span>
</center>

## <span style="color:steelblue">Ficha 1 Algoritmos Iterativos</span>
El objetivo de esta ficha es mostrar la **PROGRAMACIÓN ITERATIVA**

**<span style="color:steelblue">AÑO 569aC:</span>** Nace Pitágoras, matemático y filósofo griego que fundó la escuela pitagórica: una hermandad religiosa y filosófica con un gran sentido de la matemática en la vida cotidiana.

<center>![pitagoras](http://imgfz.com/i/JW5VAaT.png)</center>

Todos conocemos el teorema de Pitágoras. Hoy sabemos que los babilonios ya lo conocían pues usaban las ternas que hoy se conocen como pitagóricas:

<center>![teorema](http://imgfz.com/i/Fen9bwH.png)</center>

Una terna (a, b, h) es pitagórica si cumple la ecuación de Pitágoras.

Por ejemplo, (3, 4, 5) es una terna pitagórica, ya que 3² + 4² = 5². 

Otros ejemplos son: (5, 12, 13), (7, 24, 25), (8, 15, 17).

**<span style="color:steelblue">AÑO 300aC:</span>**
<center>![euclides](http://imgfz.com/i/JXC1TuG.png)</center> 

En el **Libro X de los Elementos de Euclides** aparece un método para calcular ternas pitagóricas a partir de dos números m y n: <center>![ternas](http://imgfz.com/i/Z8MDYpS.png)
</center>


Este método fue utilizado por los babilonios alrededor del año 1900 a. C.

Más fácil aún. La siguiente terna se calcula a partir de un solo número k. Este método se conoce como método pitagórico:
![pitagorico](http://imgfz.com/i/q7RNbG2.png)

**<span style="color:steelblue">AÑO 1170:</span>**
![fibonacci](https://66.media.tumblr.com/avatar_10292cd31c53_128.pnj)
Nace Leonardo de Pisa, conocido como Fibonacci y descubre su famosa sucesión: 

<center>
![sucesion](http://imgfz.com/i/TFkwEvd.png)</center>

Sucesión de Fibonacci: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, …


A partir de **cuatro términos consecutivos** de la sucesión de Fibonacci: v1, v2, v3, v4 se puede obtener una terna pitagórica. Veamos cómo: 

- Primer cateto: Calcular el producto de los extremos: v1 × v4

- Segundo cateto: Calcular el doble del producto de los dos términos del medio: 2 × v2 × v3

- Hipotenusa: Calcular la suma de los cuadrados de los términos del medio: v2² + v3²

Por ejemplo, (3, 5, 8, 13) produce la terna (39, 80, 89)
