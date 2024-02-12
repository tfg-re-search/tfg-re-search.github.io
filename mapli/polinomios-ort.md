---
layout: page
title: 
---
# Polinomios ortogonales y aplicaciones

## Profesores implicados 

Antonia M. Delgado, Lidia Fernández, Clotilde
Martínez, Teresa E. Pérez, Miguel Piñar, Joaquín F. Sánchez Lara. Grupo
en Ortogonalidad y Aplicaciones (FQM 384 - GOYA)

## Breve descripción

Los polinomios ortogonales en el sentido más clásico vienen definidos de
la siguiente forma. Dado un peso $w$ (una función positiva) soportado en
un conjunto $I$ de la recta real, existe una familia de polinomios
$\lbrace p_n\rbrace_{n=0}^\infty$ tales que cada $p_n$ es de grado $n$ y

$$\int_I x^kp_n(x)w(x)dx\begin{cases}=0\,,\text{ si }k < n\,,\\ \neq 0\,, \text{ si } k=n\,.\end{cases}$$

Estos polinomios presentan gran riqueza de propiedades y aplicaciones
debido a sus múltiples relaciones con diferentes ramas de las
matemáticas. Entre estas propiedades podemos contar con las relacionadas
con espacios de Hilbert, relaciones de recurrencia, relaciones con
matrices con estructura, ecuaciones diferenciales, sistemas dinámicos,
propiedades electrostáticas de los ceros de los polinomios, propiedades
asintóticas, etc. Esto a su vez provoca que aparezcan en una gran
variedad de aplicaciones, como en teoría de aproximación, fórmulas de
cuadratura, física matemática (soluciones de la ecuación de
Schrödinger), procesos estocásticos, modelización de sistemas, etc.

Pero el sentido de la ortogonalidad que presentan estos polinomios es
ampliable a otros muchos contextos. Se pueden considerar ortogonalidades
respecto a medidas discretas, respecto a medidas no positivas, medidas
soportadas en el plano complejo, ortogonalidades que incluyan a las
derivadas de los polinomios, ortogonalidades variantes (el peso también
depende de $n$), polinomios matriciales,…y polinomios ortogonales en
varias variables (en el que parte del grupo lleva realizando una gran
actividad en los últimos años).

## Descripción de líneas

### Línea 1: Polinomios ortogonales clásicos

Estos polinomios están caracterizados por ser soluciones de una ecuación
diferencial lineal 

$$Ay''+By'+\lambda_n y=0,$$ 

donde $A$ y $B$ son
polinomios de grado a lo sumo $2$ y $1$ respectivamente y $\lambda_n$ es
una constante dependiente del grado $n$. Estos polinomios han sido
ampliamente estudiados por lo que se conocen bastante bien sus
propiedades.

### Línea 2: Polinomios ortogonales clásicos en varias variables

Estos polinomios son una extensión de los polinomios ortogonales
clásicos llevada al contexto de polinomios en varias variables.

### Línea 3: Redes de Toda y polinomios ortogonales

Una red de Toda es un sistema dinámico para un sistema finito o infinito
de partículas cuya posición viene dada por
$\dots, x_{n-1} < x_n < x_{n+1} < \dots $ y cuyo movimiento se rige por la
ecuación difero-diferencial

$$x_n''=e^{x_{n-1}-x_n}-e^{x_n-x_{n+1}},$$

donde $x''$ se refiere a la derivada segunda respecto del tiempo. Dicho
de otro modo, la aceleración con la que se mueve una partícula depende
de la posición de esa partícula respecto a las dos que tiene
inmediatamente a izquierda y derecha. Las soluciones de este sistema
dinámico están íntimamente ligadas con los polinomios ortogonales
$p_n(x;t)$ respecto a un peso de la forma $e^{tx}w(x)$ siendo $t$ el
tiempo y más en concreto con los coeficientes de la relación de
recurrencia que satisfacen dichos polinomios ortogonales

$$xp_n(x:t)=p_{n+1}(x;t)+b_n(t)p_n(x;t)+a_n^2(t)p_{n-1}(x;t).$$

### Línea 4: Polinomios ortogonales en el simplex

Se trata de polinomios ortogonales en varias variables en el caso de que
el peso de ortogonalidad esté soportado en el simplex $T^d$

$$T^d=\lbrace(x_1,x_2,\dots,x_d)\in\mathbb{R}^d: x_1\geq 0, x_2\geq 0, \dots, x_d\geq 0, x_1+x_2+\dots+x_d\leq 1\rbrace.$$

Usualmente se escogen pesos de la forma

$$w(x)=x_1^{\alpha_1}x_2^{\alpha_2}\dots x_d^{\alpha_d}(1-|x_1+x_2+\dots+x_d|)^{\alpha_{d+1}},$$

lo que lleva a poder encontrar bases ortogonales de polinomios
expresadas en términos de los polinomios de Jacobi univariados.

### Línea 5: Polinomios de Zernike

Los polinomios de Zernike son una familia de polinomios en 2 variables
que son ortogonales en el disco
$\lbrace(x,y)\in\mathbb{R}^2: x^2+y^2\leq 1\rbrace$ respecto al peso $w(x,y)=1$.
Estos polinomios son usados como un estándar en óptica debido a que los
coeficientes de las series de Fourier que aparecen al usar esta base,
describen las diferentes aberraciones ópticas (astigmatismo, coma,
defocus, trefoil, ...) que puede tener un ojo o cualquier otro
dispositivo óptico.

### Línea 6: Interpretación electrostática de raíces de polinomios ortogonales

La disposición que adoptan los ceros de un polinomio ortogonal
(univariado) sugiere que se localizan de forma que tratan de maximizar
en cierto sentido las distancias que los separan entre sí. En algunos
casos se puede dar una descripción de estás raíces a través de un modelo
electrostático en el que los ceros de los polinomios se corresponden con
cargas eléctricas unitarias que, aún teniendo libertad para moverse
libremente por la recta real o el plano complejo, permanecen en una
posición de equilibrio. A través de esta relación se pueden dar
múltiples propiedades sobre el comportamiento que puedan tener las
raíces de los polinomios ortogonales.

## Enlaces de interés

[Página del grupo de investigación](https://www.ugr.es/~goya)

[Página de la Red a la que pertenece el grupo](https://euler.us.es/~orthonet/)

## Tipologías posibles

-   Complemento de profundización
-   Iniciación a la investigación

## Bibliografía (para profundizar un poco)

-   T. S. Chihara, An Introduction to Ortghogonal Polynomials, Gordon and Breach, New York, 1977.

-   C. F. Dunkl, Y. Xu, Orthogonal Polynomials of Several Variables, 2nd edition, Encyclopedia of Mathematics and its  Applications, vol. 155. Cambridge University Press, Cambridge (2014).

-   G. Szegö, Orthogonal Polynomials, fourth ed., Amer. Math. Soc., Providence, RI, 1975.

