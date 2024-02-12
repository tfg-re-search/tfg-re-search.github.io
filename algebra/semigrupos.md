---
layout: page
title: 
---
# Semigrupos numéricos y aplicaciones

## Profesores implicados 


- [Patricio Almirón Cuadros](https://directorio.ugr.es/static/PersonalUGR/*/show/5a6188042bb3f73d7fb33a8ef3e23702) [FQM-343](https://semigrupos.ugr.es/) $\to$ [mathscinet](https://mathscinet.ams.org/mathscinet/search/author.html?mrauthid=1315774)
- [Pedro A. García Sánchez](https://algebra.ugr.es/pages/personal/fichas_profesores/pedro), [FQM-343](https://semigrupos.ugr.es/) $\to$ [mathscinet](https://mathscinet.ams.org/mathscinet/search/author.html?mrauthid=601396)
- [Aureliano M. Robles Pérez](https://mateapli.ugr.es/index.php/informacion/directorio-personal/aureliano-m-robles-perez), [FQM-343](https://semigrupos.ugr.es/) $\to$ [mathscinet](https://mathscinet.ams.org/mathscinet/search/author.html?mrauthid=633502)
- [José Carlos Rosales González](https://directorio.ugr.es/static/PersonalUGR/*/show/38e1b86494ce65713f559cc8c3b378f5), [FQM-343](https://semigrupos.ugr.es/) $\to$ [mathscinet](https://mathscinet.ams.org/mathscinet/search/author.html?mrauthid=359302)

## Tipologías posibles


- Complemento de profundización 
- Divulgación de las Matemáticas 
- Herramientas informáticas
- Iniciación a la investigación

## Breve descripción 

Estudio de conjuntos de enteros no negativos cerrados para la suma. 


## Descripción de líneas 

Sea $\mathbb{N}$ el conjunto de los números enteros no negativos. Un semigrupo numérico es un submonoide de $(\mathbb{N},+)$ con complemento finito en $\mathbb{N}$ (un conjunto de enteros no negativos que contiene al cero, es cerrado para la suma, y existe un entero más grande que no está en el conjunto). Inicialmente el estudio de semigrupos numéricos vino motivado por el estudio de soluciones no negativas de una ecuación diofántica lineal con coeficientes enteros no negativos ($a_1x_1+\dots+a_nx_n=b$), y más concretamente sobre cuándo dicha ecuación tenía solución al variar el término independiente ($b$ en nuestro ejemplo). Posteriormente, a determinadas curvas algebraicas se les asociaron semigrupos numéricos, los cuales proporcionaban información sobre propiedades de la curva, de modo que la búsqueda de familias de semigrupos numéricos especiales aumentó significativamente. 


### Línea 1: Invariantes de factorización

Todo semigrupo numérico $S$ admite un único sistema minimal de generadores; llamémosle $\lbrace n_1,\dots,n_e\rbrace$. De esta forma 

$$S=\langle n_1,\dots,n_e\rangle=\lbrace a_1n_1+\dots+a_en_e : a_1,\dots,a_e\in \mathbb{N}\rbrace.$$

Existe por tanto un morfismo (de monoides) sobreyectivo $\phi: \mathbb{N}^e \to S$, $\varphi(a_1,\dots,a_e)= a_1n_1+\dots+a_en_e$. Dado $s\in S$, al conjunto $\varphi^{-1}(s)=\lbrace (a_1,\dots,a_e)\in \mathbb{N} : \varphi(a_1,\dots,a_e)=s\rbrace$ se le conoce como el conjunto de factorizaciones de $s$ en $S$. 

El único semigrupo numérico que verifica que todo elemento tiene una factorización única es $\mathbb{N}$. En el resto siempre hay elementos con más de una factorización (aunque siempre hay un número finito de ellas). También $\mathbb{N}$ es el único semigrupo numérico en el que todas las factorizaciones de un elemento tienen la misma longitud (como consecuencia obvia de la unicidad). Existen varias medidas para ver cómo de lejos estamos de tener factorización única o de ver cuántas posibles longitudes de factorizaciones podemos obtener. Entre ellas caben destacar el conjunto de longitudes de factorizaciones, los conjuntos delta, la elasticidad, la catenariedad o el grado de amansamiento. Los semigrupos numéricos se han convertido en una buena fuente de ejemplos de monoides en los que estudiar estos invariantes. 

Por el teorema de isomorfía, $\mathbb{N}^e/\ker\varphi$ es isomorfo a $S$, donde $\ker\varphi$ es la congruencia núcleo de $\varphi$, esto es, $\ker \varphi=\lbrace (a,b)\in \mathbb{N}^e\times \mathbb{N}^e : \varphi(a)=\varphi(b) \rbrace$. De esta forma un sistema de generadores, como congruencia de $\ker\varphi$, se conoce como una presentación de $S$. Como es de esperar, el conocimiento de una presentación de $S$ proporciona herramientas para comprender el comportamiento de las factorizaciones de los elementos de $S$.

### Línea 2: Intersecciones completas y pegadas

La búsqueda de semigrupos numéricos que fuesen simétricos (por su correspondencia con las singularidades Gorenstein en curvas algebraicas), propició una serie de trabajos que permitían, partiendo de semigrupos simétricos, construir otros semigrupos simétricos. Esto dio lugar al concepto de pegada y, en particular, a una caracterización de los semigrupos intersección completa (el anillo de definición de la curva asociada es intersección completa; su ideal de definición tiene el menor número posible de generadore, lo que equivale a que la presentación minimal del semigrupo tiene tantos elementos como generadores minimales tiene el semigrupo menos uno) en términos de pegadas. 

La pegada de semigrupos pasó, de este modo, a convertirse en una herramienta que proporcionaba nuevos semigrupos usando semigrupos con buenas propiedades y, por tanto, se empezaron a estudiar en la pegada los elementos notables que podían ser calculados de forma asequible a partir de los semigrupos implicados en la pegada. 

Las pegadas se pueden caracterizar en términos de conjuntos de Apéry (lo que proporciona fórmulas para el número de huecos y el máximo hueco, o sea, el número de Frobenius) y también en términos de presentaciones, lo que hace que se puedan construir presentaciones a "medida" con algunas propiedades deseadas.

### Línea 3: Álgebra de semigrupo

Sea $K$ un cuerpo y $S$ un semigrupo numérico generado minimalmente por $\lbrace n_1,\dots,n_p\rbrace$. De manera natural podemos asociar un álgebra a $S$ definiendo $K[S]:=\bigoplus_{s\in S}Kt^s$, donde un elemento $h\in K[S]$ es de la forma $h=\sum_{s\in S} a_s t^s$ con un número finito de $a_s\neq 0$. Dada una presentación $\varphi: \mathbb{N}^p\rightarrow S$ de un semigrupo numérico, se puede extender a una presentación del álgebra de semigrupo mediante el morfismo 

$$\phi: K[x_1,\dots,x_p]\rightarrow K[S],\quad \phi(X_i)=t^{n_i} .$$

El núcleo de $\phi$ se conoce como ideal de definición de $S$. Simplificando notación, si denotamos $a=(a_1,\dots,a_p)\in \mathbb{N}^p$ y $X=x_1^{a_1}\cdot x_p^{a_p}$, Herzog demostró que $(a,b)\in \operatorname{Ker}(\varphi)$ si y solo si $X^a-X^b\in \operatorname{Ker}(\varphi)$. Es más, si $\rho$ es una presentación minimal de $S$ entonces el conjunto $\lbrace X^a-X^b\;\mid\;(a,b)\in\rho\rbrace$ es un sistema minimal de generadores de $\operatorname{Ker}(\phi).$ 

De este modo, podemos interpretar $K[S]$ como el anillo local de una curva $C_S\subset K^p$ dada, en ecuaciones paramétricas, por $\lbrace t^{n_i}\;\text{para }\;i=1,\dots,p\rbrace$ y, en ecuaciones implícitas, por los generadores minimales de $\operatorname{Ker}(\phi)$. Si $S\neq \mathbb{N}$ entonces la curva $C_S$ tiene singularidad aislada en el origen.

En el caso de semigrupos simétricos y semigrupos intersección completa, las operaciones de pegada permiten simplificar los cálculos de algunos de los principales invariantes algebraicos asociados a la curva, así como estudiar algunas de sus propiedades geométricas. 

### Línea 4: Semigrupos de curva plana irreducible

Dada una curva plana irreducible sobre el cuerpo de los complejos se le puede asociar de manera natural un semigrupo numérico. Este semigrupo se define como el conjunto de multiplicidades de intersección de la curva. Una de las propiedades de este semigrupo es que es un ejemplo canónico de semigrupo intersección completa.

El interés en este tipo de semigrupos numéricos reside en que Burau, Brauner y Zariski demostraron que el semigrupo asociado a una curva $C$ es un invariante topológico de la singularidad. De este modo, el estudio de las propiedades combinatorias de esta clase de semigrupos permite deducir propiedades topológicas de la singularidad, así como dar una clasificación topológica de las singularidades aisladas de curva plana irreducible.

### Línea 5: Familias de semigrupos numéricos

Además de las familias asociadas al estudio de curvas algebraicas (semigrupos simétricos, pseudo-simétricos, intersección completa, Arf, saturados), es interesante analizar familias caracterizadas por ciertas propiedades comunes. Dichas propiedades pueden estar relacionadas con (1) el tipo de generadores del semigrupo; (2) los invariantes del semigrupo (dimensión de inmersión, multiplicidad, género, etcétera); (3) ciertos patrones que verifican los elementos del semigrupo; (4) la estructura del conjunto de Apéry; etcétera.

El estudio de familias particulares de semigrupos numéricos, además de ser un problema interesante en sí mismo, puede dar lugar a ejemplos, o contraejemplos, en cuestiones planteadas en la teoría de semigrupos numéricos.


### Línea 6: Problemas abiertos, conjeturas

En este momento hay dos conjeturas que atraen el interés de muchos investigadores en semigrupos numéricos.

La conjetura de Wilf establece una relación entre varios invariantes de los semigrupos (la dimensión de inmersión, el número de Frobenius y el número de elementos 'pequeños') . El intento de resolución de esta conjetura está obligando a replantearse cuál es la mejor manera de describir un semigrupo numérico.

La conjetura de María Bras está relacionada con el conteo de semigrupos numéricos. Así, si se cuentan los semigrupos que tienen un determinado género (número de naturales que no están en el semigrupo), se obtiene una sucesión con un comportamiento similar al de la sucesión Fibonacci. Esta conjetura admite una versión más débil sobre la monotonía de la sucesión aludida, que aún sigue abierta.

Además, en el estudio de los semigrupos numéricos surjen a menudo los comportamientos "modulares". Por ejemplo, en la determinación de fórmulas para problemas de conteo, o en el análisis de la estructura de los conjuntos de Apéry (para familias dadas) se producen repeticiones que dependen del módulo con respecto a ciertos valores. En general, parece que tales valores no se corresponden con los invariantes usuales y, por tanto, no son fáciles de determinar.


### Línea 7: `numericalsgps`

Tener un programa informático que haga cálculos con y en semigrupos numéricos es de gran ayuda para producir ejemplos y contraejemplos, así como para hacerse una idea de si algún resultado puede llegar a ser cierto. El paquete `numericalsgps` de `GAP` empezó a desarrollarse en 2004. Fue aceptado como paquete oficial de `GAP`en 2015, pero aún sigue mejorándose y ampliándose de forma regular. Su manual cuenta con alrededor de 180 páginas. Un recurso informático de estas características necesita un mantenimiento constante.

## Enlaces de interés

- [Numericalsgps](https://www.gap-system.org/Packages/numericalsgps.html)
- [Tutoriales](https://numerical-semigroups.github.io/)
- [Resumen ampliado]({{ site.baseurl | absolute_url }}{% link algebra/resumenes/semigrupos-numericos.md %}) de esta línea
- Último encuentro internacional de semigrupos numéricos ([IMNS](https://www.ugr.es/~imns2010/2022/))
- Red [MyA](https://www.ugr.es/~semigrupos/MyA/)
- [¿Hay alguna posibilidad de pedir 11 nuggets de pollo a pesar de que las cajas son de 4, 6 y 9?](https://www.abc.es/ciencia/posibilidad-pedir-nuggets-pollo-pesar-cajas-20230404212714-nt.html)

## Bibliografía

- A. Assi, M. D'Anna, P. A. García-Sánchez, Numerical semigroups and applications, Second edition, RSME Springer series 3, Springer, Switzerland, 2020 $\to$[springerlink](https://link.springer.com/book/10.1007/978-3-030-54943-5)
- J. C. Rosales y P. A. García-Sánchez, Numerical semigroups, Developments in Mathematics, vol. 20, Springer, New York, 2009 $\to$[springerlink](https://link.springer.com/book/10.1007/978-1-4419-0160-6)

- C.T.C. Wall, Singular points of plane curves, London Math. Soc. Students Texts 63, Cambridge Univ. Press, Cambridge, 2004.
