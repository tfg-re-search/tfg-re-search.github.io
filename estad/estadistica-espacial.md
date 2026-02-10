---
layout: page
title: ""
---
# Estadística Espacial y Aplicaciones

## Profesores implicados

-   José Luis Romero Béjar, Departamento de Estadística e Investigación
    Operativa (<https://www.ugr.es/personal/jose-luis-romero-bejar>).

-   Francisco Javier Esquivel Sánchez, Departamento de Estadística e
    Investigación Operativa
    (<https://www.ugr.es/personal/francisco-javier-esquivel-sanchez> ).

## Tipologías posibles

-   Complemento de profundización.

-   Herramientas informáticas

-   Iniciación a la investigación.

## Breve descripción

A lo largo de las últimas tres décadas se ha llevado a cabo el
desarrollo de toda una **teoría de medidas de riesgo**, que de hecho se
ha convertido en una nueva disciplina científica, principalmente
motivada e impulsada por áreas de aplicación tales como Finanzas y
Seguros, aunque con un creciente interés en otras muchas áreas del
conocimiento debido a su potencial aplicabilidad. Entre la diversidad de
familias de medidas de riesgo introducidas en estos ámbitos, las medidas
de riesgo basadas en cuantiles tales como el Valor en Riesgo o Value-at-
Risk (VaR) y el Déficit Esperado o Average Value-at-Risk (AVaR) han
recibido especial atención dado lo directo de su interpretación y fácil
implementación computacional, además del cumplimiento de ciertos axiomas
con interpretaciones significativas en este contexto.

Dado su origen, eminentemente financiero, esta teoría ha estado centrada
principalmente en el análisis de riesgos de variables aleatorias que
representan ganancias o pérdidas monetarias, para las que las
características espaciales donde se producen estas pérdidas o ganancias
no necesitan ser tenidas en cuenta. En los últimos tiempos hay un
creciente interés en el desarrollo de una teoría fundamentada de medidas
de riesgo espaciales que permita aplicaciones en campos tan diversos
como el del medioambiente, la geoestadística, ciencias ómicas, etc.
Entre los distintos enfoques en la literatura para abordar este problema
destacan aquellos que hacen interactuar la teoría de medidas de riesgo
con el análisis de características estructurales de conjuntos de
excursión de **campos aleatorios**, en los que la **teoría de valores
extremos** juega un rol fundamental en determinados contextos. Si bien,
desde un punto de vista computacional esta interacción es posible y
funciona de forma adecuada para la valoración de riesgos tanto en un
sentido global como local, con un mapeo local del riesgo, uno de los
grandes desafíos en este sentido es la definición formal de riesgo en un
dominio espacial, así como la derivación de una axiomática adecuada al
contexto en que se sitúa el problema bajo estudio.

## Descripción de líneas

### Línea 1: Introducción a la estadística espacial y aplicaciones

Muchos fenómenos físicos que se estudian en disciplinas como las
ciencias ambientales, la hidrología o la epidemiología presentan un
comportamiento que varía en el espacio y el tiempo. Para describir esta
dinámica de manera adecuada, resulta especialmente útil el uso de
modelos basados en campos aleatorios. Estos modelos permiten capturar y
analizar cómo se relacionan los valores de una variable en distintas
ubicaciones y momentos, revelando así patrones de dependencia espacial o
temporal en los datos. Dentro de este ámbito, la geoestadística se ha
consolidado como una rama específica de la estadística que se ocupa del
estudio y modelización de fenómenos con una clara dimensión espacial. Su
objetivo es analizar la variabilidad de una característica medida en
distintas localizaciones geográficas, aprovechando la información sobre
las coordenadas de los puntos de observación para hacer predicciones y
mapas de riesgo o distribución. Además, en muchos casos es fundamental
estudiar los comportamientos extremos de estos fenómenos, es decir,
eventos poco frecuentes, pero de gran impacto, como inundaciones,
sequías o brotes epidémicos intensos.

Este trabajo propone que el estudiante se adentre en los principales
desafíos y enfoques metodológicos que plantea la geoestadística,
comenzando con una introducción general al campo y una revisión de los
aspectos formales de las técnicas más consolidadas en la literatura. A
lo largo del estudio, se espera que analice en profundidad distintos
tipos de procesos espaciales ---como los procesos geoestadísticos
clásicos, los procesos regionalizados y los procesos puntuales---,
integrando además la perspectiva del análisis de riesgos extremos
mediante medidas específicas, con el objetivo de construir una visión
clara, actual y fundamentada tanto de los aspectos teóricos como de las
herramientas prácticas que permiten implementar y aplicar estos modelos
en contextos reales.

**Actividades que desarrollar**

-   Revisión bibliográfica exhaustiva sobre campos aleatorios y
    geoestadística, identificando las principales metodologías y
    enfoques utilizados en la literatura, con especial referencia a su
    estado actual, y exposición sintética del conocimiento desde una
    perspectiva global.

-   Selección de los distintos tipos de procesos espaciales más
    relevantes y aplicables en la en la práctica.

-   Profundización en uno o varios de ellos con una clara identificación
    de los elementos conceptuales inherentes, y exposición de sus
    fundamentos matemáticos y aspectos metodológicos.

-   Realización de experimentos y simulaciones mediante el uso y
    desarrollo eventual de procedimientos computacionales con R.

## Línea 2: Gestión cuantitativa del riesgo: aplicaciones en finanzas y sistemas complejos

La gestión del riesgo se ha convertido en un componente esencial del
análisis cuantitativo en disciplinas como las finanzas, la estadística
aplicada y la física de sistemas complejos. En entornos marcados por la
incertidumbre y la presencia de eventos extremos, la simple estimación
de promedios o desviaciones estándar resulta insuficiente. Es en este
contexto donde la Gestión Cuantitativa del Riesgo (Quantitative Risk
Management, QRM) surge como una disciplina clave, proporcionando un
marco matemático riguroso para la identificación, cuantificación y
control de riesgos. Uno de los pilares fundamentales de QRM es el
concepto de medida del riesgo, que permite traducir incertidumbre en
variables cuantificables mediante funciones matemáticas que capturan el
comportamiento adverso de distribuciones de probabilidad. Entre las
medidas más utilizadas se encuentran el Valor en Riesgo (VaR) y el Valor
en Riesgo Condicional (CVaR), que permiten estimar el impacto potencial
de eventos financieros extremos. Sin embargo, estas medidas tienen
limitaciones teóricas y prácticas que requieren enfoques más
sofisticados, como las medidas coherentes de riesgo y el uso de
herramientas de la Teoría de Valores Extremos (EVT). Por otro lado, la
presencia de eventos extremos no es exclusiva del ámbito financiero. En
la física, por ejemplo, especialmente en áreas como la teoría del caos,
la mecánica estadística y los sistemas complejos, también se observan
fenómenos de baja probabilidad, pero gran impacto. Ejemplos incluyen
fluctuaciones críticas en sistemas termodinámicos, turbulencias en
dinámica de fluidos, o eventos extremos en redes naturales o
artificiales. Estos paralelismos permiten aplicar las mismas
herramientas de análisis del riesgo ---como EVT, simulaciones Monte
Carlo y modelos estocásticos---en ambos dominios, enriqueciendo así la
comprensión multidisciplinar del riesgo. Este Trabajo de Fin de Grado se
propone estudiar de manera rigurosa y aplicada los conceptos
fundamentales de la teoría de medida del riesgo, haciendo énfasis en su
implementación cuantitativa dentro del enfoque del QRM. A través de
análisis matemático, simulaciones numéricas y estudios empíricos, se
evaluará la eficacia de distintas metodologías en contextos financieros
y físicos, con especial atención al comportamiento de las colas de
distribución y a la modelización de eventos raros. La naturaleza
aplicada del trabajo permitirá no solo un desarrollo teórico sólido,
sino también una conexión directa con problemas reales, desde la gestión
de carteras hasta el estudio de eventos críticos en sistemas naturales.

**Actividades que desarrollar**

-   Comprender e identificar los principios conceptuales clave que
    definen el concepto de medida de riesgo, así como su formalización
    rigurosa dentro del marco matemático.

-   Analizar en profundidad los fundamentos matemáticos que sustentan
    las metodologías de valoración del riesgo utilizadas en contextos
    financieros, evaluando también su adaptabilidad y aplicación a otros
    sistema complejos.

-   Estudiar las principales medidas de riesgo utilizadas en QRM: VaR,
    CVaR, medidas coherentes de riesgo.

-   Analizar la Teoría de Valores Extremos y su aplicabilidad a series
    temporales financieras.

-   Aplicar modelos QRM a datos reales financieros (acciones, índices,
    tipos de interés) y comparar resultados bajo distintos supuestos.

## Línea 3: Análisis de valores extremos en contextos espaciales

Este trabajo se centrará en el estudio profundo de dos ramas avanzadas
de la probabilidad y la estadística: la teoría de valores extremos y el
modelado mediante campos aleatorios. Ambas se presentan como
herramientas esenciales para comprender y cuantificar eventos raros,
pero de alto impacto, especialmente cuando dichos eventos están
distribuidos en el espacio o el tiempo. Desde el punto de vista teórico,
se desarrollará una revisión y posterior implementación del marco
clásico de la teoría de valores extremos, tanto en su versión univariada
como en su extensión al caso multivariante y espacial. Se abordarán
formalmente los principales resultados asintóticos que justifican el uso
de las distribuciones generalizadas de valores extremos (GEV) y la
distribución generalizada de Pareto (GPD), así como los métodos de
estimación más habituales, incluyendo la técnica de máximos por bloques
y el enfoque de excedencias de umbrales. Una parte esencial del análisis
será la evaluación de cuantiles extremos y niveles de retorno, que
permiten una interpretación clara en contextos aplicados.
Simultáneamente, se estudiarán los campos aleatorios como herramientas
para representar variables aleatorias distribuidas en el espacio. Se
pondrá especial atención en los campos gaussianos y en cómo su
estructura de covarianza permite modelar dependencias espaciales. Se
explorarán también campos no gaussianos y modelos extremos espaciales,
en los que la dependencia entre extremos no se comporta de forma lineal.
La interacción entre estos dos marcos ---valores extremos y campos
aleatorios--- permitirá construir modelos que no solo caractericen la
magnitud de eventos extremos, sino también su distribución geográfica y
correlación espacial. De forma opcional, todo este enfoque se
complementará con el estudio de medidas de riesgo, como el Value-at-Risk
(VaR) o el Expected Shortfall (ES), adaptadas al contexto de fenómenos
espaciales. Estas medidas permitirán cuantificar el impacto esperado de
eventos extremos bajo distintos niveles de severidad, y evaluar el
riesgo agregado sobre una región o sistema.

**Actividades que desarrollar**

-   Revisión bibliográfica sobre conceptos, elementos y técnicas
    relacionadas con el análisis de valores extremos.

-   Revisión bibliográfica sobre conceptos, elementos y técnicas
    relacionadas con la teoría de campos aleatorios.

-   Profundización en las distintas metodologías y estrategias
    inherentes al análisis de valores extremos.

-   Profundización en los aspectos formales de la teoría de campos
    aleatorios.

-   Ilustración con datos reales del uso de algunas de las
    metodologías/estrategias y desarrollo de procedimientos
    computacionales relacionados.

## Línea 4: Enfoques multivariante y espacial para el análisis de datos genómicos

Este trabajo se enmarca en el estudio y aplicación de técnicas
estadísticas avanzadas, principalmente desde la estadística
multivariante y la estadística espacial, con el fin de analizar la
estructura y distribución de datos genómicos complejos. Desde la
perspectiva matemática, el objetivo principal será caracterizar la
variabilidad y la organización espacial de los datos de expresión génica
obtenidos mediante transcriptómica espacial, una tecnología emergente
que permite medir la actividad de genes conservando la información sobre
la localización física de cada observación dentro del tejido biológico.
En primer lugar, se abordará el análisis mediante técnicas
multivariantes como el Análisis de Componentes Principales (PCA)
adaptado al contexto espacial. Se considerará la versión espacial del
PCA (sPCA), que permite tener en cuenta la correlación geográfica de la
expresión génica y ayuda a detectar patrones espaciales de variabilidad
en los datos. Esta técnica facilitará la reducción de la
dimensionalidad, preservando las estructuras espaciales más relevantes.
Posteriormente, se incorporará el análisis de clúster espacial para
identificar regiones dentro del tejido que compartan perfiles de
expresión similares, lo que puede reflejar organización funcional,
identidad celular o procesos biológicos subyacentes. Se utilizarán
métodos como k-means espacialmente ponderado o clustering jerárquico con
restricción geográfica, y se analizará la estabilidad y la
interpretabilidad biológica de los resultados. Además, se explorará el
uso del kriging como técnica geoestadística para interpolar y visualizar
niveles de expresión génica en regiones no muestreadas del tejido,
permitiendo una representación continua del fenómeno biológico y
facilitando su análisis global. A lo largo del trabajo se discutirán los
fundamentos matemáticos de estas técnicas, su aplicabilidad en datos de
alta dimensión y su comportamiento en presencia de ruido, correlación
espacial y otras características propias de los datos genómicos. Desde
una perspectiva más computacional, el trabajo se centrará en la
implementación y automatización del flujo completo de análisis espacial
de datos genómicos utilizando herramientas computacionales y entornos de
programación científica. Se utilizarán Python y/o Lenguaje R como
lenguaje base, haciendo uso de bibliotecas especializadas como Scanpy,
GeoPandas, Scikit-learn, Scikit-GStat y PyKrige, entre otras. Se
desarrollará un pipeline reproducible que abarque desde el
preprocesamiento de los datos (normalización, filtrado, selección de
genes informativos) hasta el análisis multivariante y la visualización
interactiva de los resultados. Una parte importante del trabajo será la
integración entre datos genómicos y datos espaciales, que requiere
combinar formatos de datos biológicos (como matrices de expresión) con
estructuras espaciales (coordenadas de spots o regiones del tejido).
Para ello se establecerán representaciones adecuadas y estructuras de
datos eficientes, permitiendo una exploración fluida tanto cuantitativa
como visual. El resultado final incluirá la creación de una aplicación o
conjunto de notebooks que permitan visualizar los resultados de los
análisis en forma de mapas espaciales interactivos, gráficos de
componentes principales, mapas de clústeres y superficies interpoladas
mediante kriging. Este desarrollo buscará no solo facilitar la
interpretación biológica de los datos, sino también poner a disposición
de herramientas reutilizables para análisis similares en otros tejidos u
organismos. Finalmente, se discutirá el potencial de estas técnicas en
contextos biomédicos, como la identificación de regiones genómicas
implicadas en enfermedades, el estudio de la heterogeneidad celular en
cáncer, etc., destacando el valor del enfoque estadístico espacial en la
era de la biología de datos.

**Actividades que desarrollar**

-   Revisión bibliográfica sobre conceptos, técnicas y estructuras de
    datos genómicos.

-   Revisión bibliográfica sobre conceptos, elementos y técnicas de la
    estadística multivariante.

-   Profundización en las distintas metodologías y estrategias
    inherentes al análisis multivariante.

-   Revisión bibliográfica sobre conceptos, elementos y técnicas
    relacionadas con la estadística espacial.

-   Profundización en los aspectos formales de la estadística espacial:
    semivariograma, función de covarianza, estacionariedad, isotropía,
    kriging, etc.

-   Ilustración con datos reales, en el contexto aplicado de los datos
    genómicos, del uso de algunas de las metodologías/estrategias y
    desarrollo de procedimientos computacionales relacionados.

#### Bibliografía general

1.  Adler, R. J., Taylor, J. E. (2007) Random Fields and Geometry,
    Springer.

2.  Ansari, M. Y., Ahmad, A., Khan, S. S., Mainuddin, G. (2020)
    Spatiotemporal clustering: a review, Artificial Intelligence Review,
    53, 2381-2423.

3.  Artzner, P., Delbaen, F., Eber, J.M., Heath, D. (1999) Coherent
    measures of risk. Mathematical Finance 9:203--228.

4.  Ayala, G. (2023) Análisis Estadístico de Datos Ómicos. Universidad
    de Valencia.

5.  Beirlant, J., Goegebeur, Y., Segers, J., Teugels, J. (2004)
    Statistics of Extremes. Theory and Applications. Wiley.

6.  Boxiang, L.; Yanjun, L.; Liang, Z. (2022) Analysis and Visualization
    of Spatial Transcriptomic Data. Frontiers in Genetics (12).

7.  Brezis, H. (1984) Análisis Funcional. Teoría y Aplicaciones. Alianza
    Editorial.

8.  Castillo, E., Hadi, A.S., Balakrishnan, N., Sarabia, J.M. (2005)
    Extreme Value and Related Models with Applications in Engineering
    and Science. Wiley.

9.  Chiu, S. N., Stoyan, D., Kendall, W. S., Mecke, J. (2013) Stochastic
    Geometry and its Applications, Wiley.

10. Christakos, G. (2017) Spatiotemporal Random Fields, Elsevier.

11. Coles, S. (2001) An Introduction to Statistical Modeling of Extreme
    Values. Springer.

12. Cressie, N. (1991) Statistics for Spatial Data, Wiley.

13. Follmer, H., Schied, A. (2016) Stochastic Finance. An Introduction
    in Discrete Time. Walter de Gruyter GmbH & Co. KG.

14. Fujikoshi, Y., Ulyanov, V.V. y Shimizu, R. (2010). Multivariate
    Statistics. High-Dimensional and Large-Sample Approximations. John
    Wiley & Sons.

15. Gneiting, T; Schlather, M. (2004) Stochastic models that separate
    fractal dimension and the Hurst effect. SIAM Review(46) 269-282.

16. Härdle, W.K. y Simar, L. (2015, 4ª ed.). Applied Multivariate
    Statistical Analysis. Springer.

17. Izenman, A.J. (2008). Modern Multivariate Statistical Techniques.
    Regression, Classification, and Manifold Learning. Springer.

18. Kent, J. T., Mardia, K. V. (2022) Spatial Analysis, Wiley.

19. Koch, E. (2019) Spatial risk measures and rate of spatial
    diversification. Risks 52:1--26.

20. Kriele, M., Wolf, J. (2014) Value-Oriented Risk Management of
    Insurance Companies. Springer.

21. Liese, F., Miescke, K.-J. (2009) Statistical Decision Theory:
    Estimation, Testing and Selection. Springer.

22. Malevergne, Y., Sornette, D. (2006) Extreme Financial Risks. From
    Dependence to Risk Management. Springer.

23. McNeil, A. J., Frey, R., Embrechts, P. (2005) Quantitative Risk
    Management. Concepts, Techniques and Tools. Princeton University
    Press.

24. Pekalska, E. y Duin, R.P.W. (2005). The Dissimilarity Representation
    for Pattern Recognition. Foundations and Applications. World
    Scientific.

25. Rencher, A.C. y Christensen, W.F. (2012, 3ª ed.). Methods of
    Multivariate Analysis. John Wiley & Sons.

26. Romero J. L., Madrid A. E., Angulo J. M. (2018) Quantile-based
    spatiotemporal risk assessment of exceedances. Stochastic
    Environmental Research and Risk Assessment, Vol. 32 (8), 2275-2291.

27. Timm, N. H. (2002). Applied Multivariate Analysis. Springer.

28. Zelterman, D. (2015). Applied Multivariate Statistics with R.
    Springer.
