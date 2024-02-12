---
layout: page
title: ""
---
# Métodos Algebraicos y Heurísticos en Teoría de Códigos y Criptografía 
## (ALGHEU, PID2019-110525GB-I00)


## Miembros

### Equipo de investigación


- [José Gómez Torrecillas](https://scholar.google.es/citations?user=JLAmmfcAAAAJ&hl=es), Departamento de Álgebra (FQM-379, Algebra & Information Theory)
- [Javier Lobillo Borrero](https://scholar.google.es/citations?user=1tl1rJgAAAAJ&hl=es), Departamento de Álgebra (FQM-379, Algebra & Information Theory)
- [Gabriel Navarro Garulo](https://scholar.google.es/citations?user=XcePyDEAAAAJ&hl=es), Departamento de Ciencias de la Computación e IA (TIC-111, Razonamiento Aproximado e Inteligencia Artificial)
- [Manuel Pegalajar Cuéllar](https://scholar.google.es/citations?user=GN4K2gkAAAAJ&hl=es), Departamento de Ciencias de la Computación e IA (TIC-111, Razonamiento Aproximado e Inteligencia Artificial)

### Colaboradores

- [José Manuel Muñoz Fuentes](https://www.ugr.es/personal/jose-manuel-munoz-fuentes), Investigador predoctoral (Departamento de Álgebra, UGR). 
- [Tamar Mesablishvili](https://directorio.ugr.es/static/PersonalUGR/*/show/f49a670a02b38e68a7e192fe1aa0cec1), Investigadora predoctoral (Departamento de Álgebra, UGR).
- [Alessandro Neri](https://scholar.google.com/citations?user=d2osIFUAAAAJ&hl=en), University of Ghent (Belgium)
- [Peter Kutas](https://scholar.google.com/citations?user=VoIiJSQAAAAJ&hl=en), University of Birmingham (UK)
- [Gianira Alfarano](https://scholar.google.com/citations?user=Kib5M0YAAAAJ&hl=en), Eindhoven University of Technology (Netherlands)
- [Patricio Sánchez Hernández](https://scholar.google.com/citations?user=wTx5ojYAAAAJ&hl=en), Universidad Juárez del Estado de Durango (México)


## Tipologías posibles


- Complemento de profundización 
- Herramientas informáticas
- Iniciación a la investigación

## Breve descripción 

La Teoría de Códigos es una rama de las Matemáticas y las Ciencias de la Computación que se ocupa del diseño y análisis de métodos para detectar y corregir errores en la transmisión de información. Los códigos correctores de errores se utilizan en una amplia variedad de aplicaciones, como en la transmisión de datos digitales en redes de computadoras, en sistemas de almacenamiento de información, y en comunicaciones satelitales, entre otras. Por otro lado, la criptografía es el estudio de técnicas para proteger la información mediante el cifrado y descifrado de mensajes. El objetivo de la criptografía es asegurar la confidencialidad, integridad y autenticidad de los datos. Las técnicas criptográficas se utilizan para proteger la información en una amplia variedad de aplicaciones, como en la banca electrónica, el comercio en línea, las comunicaciones militares, entre otras. Las líneas de este proyecto están basadas en la aplicación de métodos usuales de álgebra no conmutativa en el contexto de la Teoría de Códigos y la Criptografía. Cuando el cálculo exacto de la solución óptima de un problema no es posible realizarlo en un tiempo razonable, es usual tratar de conseguir una solución aproximada mediante el uso de funciones heurísticas. Este tipo de problemas son usuales en criptografía, por lo que este proyecto también plantea el diseño de algoritmos aproximados para su resolución efectiva.


## Descripción de líneas 


### Códigos de bloque cíclicos sesgados

Aunque la teoría de códigos tiene su origen en un problema de ingeniería, se ha convertido en una disciplina en la intersección de las Matemáticas y las Ciencias de la Computación con aplicaciones a casi todas las áreas de las tecnologías de información y las comunicaciones. De hecho, las técnicas matemáticas son cada vez más sofisticadas. Una estructura algebraica rica en un código, como la linealidad o la ciclicidad, por lo general, conduce a un mejor conocimiento de sus parámetros básicos, así como al diseño de algoritmos de decodificación más rápidos. Podemos ejemplificar esto
afirmación mencionando los conocidos códigos y algoritmos de decodificación propuestos por Reed,
Salomón, Bose, Chaudhuri, Hocquenghem, Goppa, Peterson, Gorenstein, Zierler, Sugiyama, entre otros, durante las décadas de 1950, 1960 y 1970. Más recientemente, se han introducido estructuras algebraicas no conmutativas para aumentar las familias de códigos con algoritmos de decodificación eficiente. Concretamente, con los precedentes de Gabidulin, Boucher, Ulmer y otros, se comenzó a establecer la teoría de los códigos de bloque cíclicos sesgados. Estos códigos presentan una estructura de ideal a izquierda sobre un álgebra cociente de un anillo de polinomios no conmutativos (polinomios de Ore).


### Códigos convolucionales cíclicos

Elias introdujo los códigos convolucionales en 1955. Estos utilizan un esquema de codificación que depende no solo del mensaje actual que se transmite, sino también de un cierto número de mensajes anteriores. Los códigos convolucionales pueden verse como transmisores de polinomios con n-tuplas como coeficientes o como n-tuplas de polinomios con coeficientes en un cuerpo finito F como alfabeto. En una visión,  la teoría algebraica de los códigos convolucionales considera un espacio vectorial sobre F(t), las funciones racionales sobre el cuerpo finito F, como contexto. En el otro, un módulo libre sobre el anillo de polinomios F[t]. La ventaja de esta primera visión es que se puede intentar imitar los resultados y las técnicas de los códigos de bloque. En particular, es posible dar una noción de ciclicidad que, al trabajar sobre un espacio vectorial, permite el construcción de códigos y algoritmos de decodificación eficientes sobre la distancia de Hamming. La segunda visión es operacionalmente más complicada, ya que se trabaja con módulos sobre el PID de polinomios F[t], pero los resultados permiten trabajar sobre la distancia libre, más adecuada para este tipo de códigos.


### Criptografía post-cuántica

El reciente desarrollo de los ordenadores cuánticos y la computación cuántica ha planteado cuestiones importantes en Criptografía. Debido al algoritmo de Shor (Peter W. Shor, “Polynomial-Time Algorithms for Prime Factorization and Discrete Logarithms on a Quantum Computer”, SIAM J. Sci. Statist. Comput. 41 (2): 303-332, 1999), la seguridad de algunos de las criptosistemas de clave pública más utilizados podría estar comprometida en un futuro no muy lejano. La criptografía post-cuántica es el área encargada del diseño de criptosistemas resistentes a los ataques utilizando ordenadores cuánticos.
Actualmente, existen cuatro metodologías de diseño principales: criptografía basada en códigos, en funciones hash, en retículos y en polinomios multivariados.

Criptografía basada en códigos. En 1978, poco después de la publicación del concepto de criptosistema de clave pública por Diffie y Hellman, McEliece propuso un criptosistema asimétrico basado en códigos correctores de errores. Su idea era la siguiente: Partimos de una familia de códigos dotados de algoritmos eficientes de decodificación. Alterando convenientemente cada uno de estos códigos obtendremos códigos equivalentes cuyas matrices generadoras los hacen indistinguibles de un código lineal genérico. Como el problema de decodificar un código lineal sin estructura adicional es NP-duro, esta estrategia permite diseñar una función unidireccional (one-way function), agregando un número controlado de errores al mensaje, cuya trampilla (trapdoor) consiste en utilizar el código inicial para decodificar el mensaje original a partir del modificado con los errores. McEliece utilizó códigos de Goppa binarios de longitud 1024 y capacidad de corrección 50. Aunque estos parámetros pueden considerarse rotos hoy en día, el uso de tamaños más grandes parece que continúa brindando seguridad a los criptosistemas. La criptografía basada en códigos estudia las familias de códigos susceptibles de ser insertadas en variaciones de este esquema.

### Calculo de la distancia mediante métodos heurísticos

La equivalencia entre el problema de decodificar códigos lineales y el problema de calcular la
la distancia mínima es bien conocida. Un método eficiente para calcular la distancia mínima proporcionaría entonces un algoritmo de decodificación eficiente y, en consecuencia, un método
para romper, por ejemplo, el criptosistema clásico de McEliece. Sin embargo, Vardy demostró que calcular la distancia mínima de un código lineal arbitrario es un problema NP-difícil. 
Por lo tanto, se asume la hipótesis de que no es posible diseñar un algoritmo exacto para resolver este problema en un tiempo razonable. A pesar de esto, la seguridad de los criptosistemas basados en códigos puede verse comprometida por algoritmos heurísticos, que se han utilizado para resolver ciertos problemas NP-difíciles en la práctica. Una metaheurística es un procedimiento iterativo guiado por una heurística que combina diferentes conceptos para explorar y explotar adecuadamente el espacio de búsqueda. Con respecto al problema de calcular la distancia, uno puede encontrar en la literatura intentos considerando enfriamiento simulado, búsqueda tabú, optimización por colonias de hormigas y algoritmos genéticos.


## Bibliografía

- D. J. Bernstein, J. Buchmann, E. Dahmen, Editors. Post-Quantum Cryptography. Springer, 2010.
- M. P. Cuéllar, J. Gómez-Torrecillas, F. J. Lobillo and Gabriel Navarro, Genetic algorithms with permutation-based representation for computing the distance of linear codes, Swarm and Evolutionary Computation 60 (2021), 100797.
- M.P. Cuéllar, J. Lobillo and Gabriel Navarro, Fast parallel computation of reduced row echelon form to find the minimum distance of linear codes, Expert Systems with Applications 224 (2023), article 119955.
- J. Gómez-Torrecillas, F.J. Lobillo, and Gabriel Navarro, Peterson-Gorenstein-Zierler algorithm for skew RS codes, Linear and Multilinear Algebra 66 (2018), 469-487.
- J. Gómez-Torrecillas, F.J. Lobillo, and G. Navarro, A new perspective of cyclicity in convolutional codes, IEEE Transactions on Information Theory 62 (5) (2016), 2702-2706.
- W. C. Huffman, V. Pless. Fundamentals of error-correcting codes, 2003. 
- SageMath, the Sage Mathematics Software System (Version 9.8), The Sage Developers, 2023, http://www.sagemath.org 
