# <span style="color:rgb(205, 92, 92)">SEMANA DE LA CIENCIA</span>
## Ficha 1 <span style="color:rgb(240, 128, 128)">Algoritmos Iterativos</span>
El objetivo de esta ficha es mostrar la <span style="color:rgb(0, 0, 128)">**PROGRAMACIÓN ITERATIVA**</span>.

<span style="color:rgb(128, 128, 0)">**AÑO 569 a.C.:**</span> Nace Pitágoras, matemático y filósofo griego que fundó la escuela pitagórica, una hermandad religiosa y filosófica con un gran sentido de la matemática en la vida cotidiana.


Todos conocemos el <span style="color:rgb(128, 128, 0)">**Teorema de Pitágoras** </span>. Hoy sabemos que los babilonios ya lo conocían pues usaban las ternas que hoy se conocen como pitagóricas:

![Pitágoras-foto](https://i.ibb.co/Rz7Ht0r/Pit-goras.png "Pitágoras")![Terna de Pitagoras](https://i.ibb.co/ZN9VVcs/Terna-Pitag-rica.png "Terna Pitagórica")Una terna (<span style="color:rgb(77, 121, 255)">a</span>, <span style="color:rgb(0, 204, 0)">b</span>, <span style="color:rgb(255, 0, 0)">h</span>) es pitagórica si cumple la ecuación de Pitágoras: 
 ![Ecuación de Pitágoras](https://i.ibb.co/12pTVLp/Formula1.png "Ecuación de Pitágoras")
 
 Por ejemplo, (3, 4, 5) es una terna pitagórica, ya que 32 + 42 = 52. 
 
 Más ejemplos :   (5, 12, 13), (7, 24, 25), (8, 15, 17)
 
 ![Euclides](https://i.ibb.co/z8Yf1ss/Euclides.png "Euclides")
 
 <span style="color:rgb(128, 128, 0)">**AÑO 300 a.C.:**</span> En el ***Libro X de los Elementos de Euclides*** aparece un método para calcular ternas pitagóricas a partir de dos números <span style="color:rgb(128, 128, 0)">**m** </span> y  <span style="color:rgb(128, 128, 0)">**n** </span>: ![Método para calcular ternas pitagóricas](https://i.ibb.co/Jxhp6RK/F-rmula2.png "Método para calcular ternas pitagóricas")

Fue utilizado por los babilonios alrededor del año 1900 a. C.

Más fácil aún es la siguiente terna se calcula a partir de un solo número <span style="color:rgb(128, 128, 0)">**k** </span>. Este método se conoce como **Método Pitagórico**: 

![Método Pitagórico](https://i.ibb.co/BqnCkfv/F-rmula3.png "Método Pitagórico")

<span style="color:rgb(128, 128, 0)">**AÑO 1170:**</span> Nace Leonardo de Pisa, conocido como <span style="color:rgb(128, 128, 0)">**Fibonacci**</span> y descubre su famosa sucesión: 

![Fibonacci](https://i.ibb.co/3F4RPbp/Leonardo-de-Pisa.png "Fibonacci")![Sucesión de Fibonacci](https://i.ibb.co/ZM3dG1p/F-rmula4.png "Sucesión de Fibonacci")

Sucesión de Fibonacci: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, …

A partir de **cuatro términos consecutivos** de la sucesión de Fibonacci: v1, v2, v3, v4, se puede obtener una terna pitagórica de la siguiente manera: 

- **Primer cateto:** Calcular el producto de los extremos: v1 × v4

- **Segundo cateto:** Calcular el doble del producto de los dos términos del medio: 2 × v2 × v3

- **Hipotenusa</span>:** Calcular la suma de los cuadrados de los términos del medio: v22 + v32

Un ejemplo: (3, 5, 8, 13) se produce la terna (39, 80, 89)





