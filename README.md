
<div align="center">
    <h1>Fundamentos de Estadística y Análisis de Datos con Python</h1>
    <img src="readme_img/fundamentos-de-estadistica.png" width="">
</div>

## Introducción al documento

El contenido de este documento son **apuntes teoricos** del [Curso de Fundamentos de Estadística y Análisis de Datos con Python](https://platzi.com/cursos/estadistica-python/) y busca ser una guía para futuros trabajos personales. El mismo está dictado por Katherine Briceño Guerrero, Ingenieria y analista de datos. El curso es de [Platzi](https://platzi.com).

Con el curso se trata de comprender los conceptos estadísticos básicos e incrementar las habilidades de análisis de datos. Se buscar utilizar estimadores, distribuciones muestrales e intervalos de confianza, interpretando resultados y aplicando los conocimientos en Python.

## Objetivos del documento

- Utilizar Python en estadistica.
- Introducir conceptos básicos de estadística.
- Caracterizar información a través del análisis exploratorio.
- Aplicar conceptos de probabilidad a eventos aleatorios.
- Construir conceptos estadísticos analíticos.
- Realizar inferencias estadisticas a partir de una muestra.
- Usar modelos estadísticos para exploración y predicción.
- Introducir conceptos de analítica avanzada.

## Tabla de contenido

- [Fundamentos de Estadística y Análisis de Datos con Python](#fundamentos-de-estadística-y-análisis-de-datos-con-python)
  - [Introducción a conceptos básicos del curso](#introducción-a-conceptos-básicos-del-curso)
    - [Pensamiento estadístico para programadores](#pensamiento-estadístico-para-programadores)
    - [Conceptos clave sobre estadística](#conceptos-clave-sobre-estadística)
  - [Caracterizar información a traves del análisis exploratorio](#caracterizar-información-a-traves-del-análisis-exploratorio)
    - [Medidas de tendencia central](#medidas-de-tendencia-central)
    - [Diagramas de frecuencias para variables continuas y discretas](#diagramas-de-frecuencias-para-variables-continuas-y-discretas)
    - [Visualización de datos usando Python](#visualización-de-datos-usando-python)
  - [Aplicar conceptos de probabilidad a eventos aleatorios](#aplicar-conceptos-de-probabilidad-a-eventos-aleatorios)
    - [Probabilidad condicional - Teorema de Bayes](#probabilidad-condicional---teorema-de-bayes)
    - [Funciones de distribución discreta y continua](#funciones-de-distribución-discreta-y-continua)
    - [Distribuciones de mayor aplicación discretas](#distribuciones-de-mayor-aplicación-discretas)
    - [Distribuciones de mayor aplicación continuas](#distribuciones-de-mayor-aplicación-continuas)
    - [Estandarización, covarianza y correlación - Data set iris species](#estandarización-covarianza-y-correlación---data-set-iris-species)
  - [Construir conceptos estadísticos analíticos](#construir-conceptos-estadísticos-analíticos)
    - [Estimadores](#estimadores)
    - [Distribuciones muestrales](#distribuciones-muestrales)
    - [Teorema del Límite Central](#teorema-del-límite-central)
  - [Realizar inferencias estadisticas a partir de una muestra](#realizar-inferencias-estadisticas-a-partir-de-una-muestra)
  - [Usar modelos estadísticos para exploración y predicción](#usar-modelos-estadísticos-para-exploración-y-predicción)

# Fundamentos de Estadística y Análisis de Datos con Python

## Introducción a conceptos básicos del curso

### Pensamiento estadístico para programadores

Realiza una predicción de la probabilidad de salvarse en el Titanic con las herramientas aprendidas en este curso!.

**¿Que es Python?**

Python es un lenguaje interpretado, dinámico, y es un lenguaje que posee una escalabilidad muy buena.

Python puede funcionar como una versión Script. Para este curso se usará Collab, la version Jupyter de Google.

**Python y la estadística: ¿Porqué usar python y no R para estadística?**

R es un lenguaje dedicado a la estadística, python es un lenguaje de propósito general con módulos estadísticos.

R está especializado para estadística y tiene más features que python. Pero cuando se trata de construir complejos **piplines** para el análisis que mezcla estadística con análisis de imágenes, minería de texto la riqueza de python es invaluable.

La estadística actual requiere una gran cantidad de procesamiento y almacenamiento de información. Aquí entran los **ambientes virtuales**.

Los ambientes virtuales como Collabs, Jupyter, facilitan el trabajo en estas variables de volumen y procesamiento, así como el uso de librerías.

En esta sección se verán conceptos básicos para empezar a trabajar con librerias, desde interactuar con el sistema operativo desde nuestra Notebook hasta importar algunas bases de datos como ejemplo.

El trabajo lo podremos ver en el siguiente link [Notebook](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/basico/Conceptos%20b%C3%A1sicos%20del%20curso/1_Conceptos_b%C3%A1sicos.ipynb).

### Conceptos clave sobre estadística

[Notebook de la sección](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/basico/Conceptos%20b%C3%A1sicos%20del%20curso/2_Conceptos_clave_sobre_estad%C3%ADstica.ipynb)

En esta sección se estudian:

Los tipos de datos y como estos pueden ser a grandes rasgos numericos y categoricos.

Tambien las variables deterministicas y las variables aleatorias y como entre estas variables tenemos incertidumbre. Se asume que la estadística estudia fenomenos aleatorios y no deterministicos.

Vemos el cálculo de probabilidades en variables y distribución de Bernoulli. Para terminar estudiamos la distribución binomial y su estrecha relación con Bernoulli.

## Caracterizar información a traves del análisis exploratorio

En esta sección veremos una serie de herramientas, tanto visuales como numéricas que nos van a permitir caracterizar y describir perfectamente las variables aleatorias.

### Medidas de tendencia central

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/analisis-exploratorio/2.%20Caracterizar%20informaci%C3%B3n%20a%20traves%20del%20an%C3%A1lisis%20exploratorio/3_Medidas_de_tendencia_central.ipynb)

Las [medidas de tendencia central](https://es.wikipedia.org/wiki/Medidas_de_tendencia_central) son valores principales para caracterizar variables aleatorias.

La medida de tendencia central es un número situado hacia el centro de la distribución de los valores de una serie de observaciones (medidas), en la que se encuentra ubicado el conjunto de los datos.

Es importante que no todas las medidas de tendencia son aplicables a los dos tipos de variables, numéricas y categóricas, y que también algunas de ellas son más susceptibles a los valores extremos (outliers)

**Medidas de tendencia**

- Media
  - [Aritmética]((https://es.wikipedia.org/wiki/Media_aritm%C3%A9tica))
  - [Geométrica](https://es.wikipedia.org/wiki/Media_geom%C3%A9trica)
  - [Armónica](https://es.wikipedia.org/wiki/Media_arm%C3%B3nica)
  - [Ponderada](https://es.wikipedia.org/wiki/Media_ponderada)
- [Mediana](https://es.wikipedia.org/wiki/Mediana_(estad%C3%ADstica))
- [Moda](https://es.wikipedia.org/wiki/Moda_(estad%C3%ADstica))
- [Error típico o desviación estándar](https://es.wikipedia.org/wiki/Desviaci%C3%B3n_t%C3%ADpica)

**Criterios de aplicación**

- No todas las medidas de tendencia central son aplicables a las variables numericas y categoricas, o sea, hay que tener en cuenta el tipo de variable a la hora de utilizarlas.

- Alguna de ellas son mas suceptibles que otras a los valores extremos.

### Diagramas de frecuencias para variables continuas y discretas

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/analisis-exploratorio/2.%20Caracterizar%20informaci%C3%B3n%20a%20traves%20del%20an%C3%A1lisis%20exploratorio/4_Diagrama_de_frecuencias.ipynb)

En estadistica descriptiva tenemos los diagramas de frecuencia o [histogramas](https://es.wikipedia.org/wiki/Histograma), estos es una representación gráfica de una variable en forma de barras, donde la superficie de cada barra es proporcional a la frecuencia de los valores representados.

Sirven para obtener una "primera vista" general, o panorama, de la distribución de la población, o de la muestra, respecto a una característica, cuantitativa y continua.

En resuemn son una representación categórica y numérica de la distribución de los datos.

Los que haremos en este notebook será estudiar las variables principales para hacer este estudio, y en las siguiente sección los gráficos.

Las variables que podemos representar son:

- **Variables categóricas**: Tablas de frecuencia.
- **Variables numéricas**: percentiles, deciles, quintiles y quartiles, outliers o valores extremos.

### Visualización de datos usando Python

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/analisis-exploratorio/2.%20Caracterizar%20informaci%C3%B3n%20a%20traves%20del%20an%C3%A1lisis%20exploratorio/5_Visualizaci%C3%B3n_de_datos_usando_Python.ipynb)

En esta sección la visualización de los datos.

La visualización de datos es de suma importancia en la actualidad ya que los mismos crecen a ritmos agigantados, el emplear un modo visual que presente la información incluso cuando el volumen de datos es bastante considerable, permite ahorrar tiempo y costes, debido a que la información se puede visualizar de forma **clara, rápida y sencilla** permitiendo la **toma de buenas decisiones**.

En esta sección veremos los tipos de gráficos mas utilizados y simples.

- Para variables categoricas
  - Gráfico de barras
  - Gráfico circular.

- Para variables numericas:
  - Una variable:
    - Histogramas
  - Dos variables:
    - Boxplot
    - Scatterplot

Estos ultimos dos gráficos, para dos variables y numericas son continuamente utilizados en el analisis estadistico porque nos permiten visualizar la relacion entre dos variables conjuntamente. Si vemoas una distribucion aleatoria donde no haya ningun patron, podemos decir que las variables no estan correlacionadas, pero si llegamos a identicarlo, podemos llegar a conclusiones mucho mas profundas, estadisticamente hablando entre las 2 variables.

## Aplicar conceptos de probabilidad a eventos aleatorios

### Probabilidad condicional - Teorema de Bayes

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/eventos-aleatorios/3.%20Aplicar%20conceptos%20de%20probabilidad%20a%20eventos%20aleatorios/6_Probabilidad_condicional_Teorema_de_Bayes.ipynb)

En esta sección vemos la de conocer los tipos de probabilidades y como se relacionan estas con el Teorema de Bayes.

Los tipos de probabilidades claves que debemos tener en cuenta 3 son:

- Probabilidad univariada
- Probabilidad conjunta bivariada
- Probabilidad condicional

Una vez entendido estos conceptos se estudia en con mayor profundidad el Teorema de Bayes aplicando Python en el Notebook.

Basicamente el teorema de bayes nos permite inferir la probabilidad de un evento A cuando tenemos informacion parcial de este evento y condicionado a un evento B cuando tenemos información total de este.

### Funciones de distribución discreta y continua

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/eventos-aleatorios/3.%20Aplicar%20conceptos%20de%20probabilidad%20a%20eventos%20aleatorios/7_Funciones_de_distribuci%C3%B3n_discreta_y_continua.ipynb)

Las **distribuciones de probabilidad continuas**, como la distribución normal, describen valores en un rango o escala y se muestran como figuras sólidas en la galería de distribuciones. Las distribuciones continuas son en realidad abstracciones matemáticas, ya que suponen la existencia de cada valor intermedio posible entre dos números. Es decir, una distribución continua asume que hay un número infinito de valores entre dos puntos de la distribución.

Las **distribuciones de probabilidad discretas** describen valores distintos, normalmente números enteros, sin valores intermedios, y se muestran como una serie de columnas verticales.Una distribución discreta, por ejemplo, puede describir como 0, 1, 2, 3 o 4 el número de veces que aparece “cara” al tirar una moneda a cara o cruz.

[Distribución de probabilidades mas comunes](https://es.qwe.wiki/wiki/Probability_distribution#Common_probability_distributions)

### Distribuciones de mayor aplicación discretas

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/eventos-aleatorios/3.%20Aplicar%20conceptos%20de%20probabilidad%20a%20eventos%20aleatorios/8_Distribuciones_de_mayor_aplicaci%C3%B3n_discretas.ipynb)

Las distribuciones de probabilidad discretas mas comunes son:

- [Distribucion de Bernoulli](https://es.wikipedia.org/wiki/Distribuci%C3%B3n_de_Bernoulli)
- [Distribucion de Binomial](https://es.wikipedia.org/wiki/Distribuci%C3%B3n_binomial)
- [Distribucion de Geometrica](https://es.qwe.wiki/wiki/Geometric_distribution)
- [Distribucion de Binomial negativa](https://es.qwe.wiki/wiki/Negative_binomial_distribution)
- [Distribucion de Poisson](https://es.qwe.wiki/wiki/Poisson_distribution)

### Distribuciones de mayor aplicación continuas

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/eventos-aleatorios/9_Distribuciones_de_mayor_aplicaci%C3%B3n_continuas.ipynb)

- [Distribucion de Exponencial](https://es.qwe.wiki/wiki/Exponential_distribution): Es el caso inverso de la distribucion de Poisson. En Poisson contabamos numero de eventos en unidad de tiempo. En esta distribucion contamos el tiempo que no tardamos en llegar a uno de esos eventos. Es utilizada generalmente para análisis de fiabilidad, p.e: probabilidad de que un componente falle transcurrido una cierta cantidad de tiempo. 
- [Distribucion de Normal](https://es.qwe.wiki/wiki/Normal_distribution): Tambien llamada de campana. Se caracteriza por estar centrada en una media de 0 y tener el 99% de los valores en +-3 desviaciones estandar. Se utiliza para inferencia estadística, es decir, estimar/evaluar parámetros de toda una población, basados en una muestra.
- [Distribucion de Uniforme](https://es.qwe.wiki/wiki/Uniform_distribution_(continuous)): Asume que cada evento esta distribuido con una misma probabilidad. Se utiliza generalmente en el ámbito de simulación, por ejemplo “creación” de escenarios aleatorios, números aleatorios, etc.

En general cuando tienes un dataset y te enfocas en alguna variable numérica además de ver si hay outliers con boxplots, entre otros estudiso. Puede ser interesante analizar la distribución de esa variable y querer generar un modelo para ver que tan probable es que dicha variable tome cierto valor, es decir, P(x=a). Luego piensas ¿será que esa variable se distribuye de acuerdo a una dsitribución normal, uniforme, binomial, ..., etc?. y ahí comienza el análisis.

### Estandarización, covarianza y correlación - Data set iris species

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/eventos-aleatorios/3.%20Aplicar%20conceptos%20de%20probabilidad%20a%20eventos%20aleatorios/10_Estandarizaci%C3%B3n%2C_covarianza_y_correlaci%C3%B3n.ipynb)

En esta sección se estudian 3 conceptos muy importantes. Para estudiar estos conceptos se utilizo el [datasets de iris](https://www.kaggle.com/uciml/iris)

Dos de los conceptos importantes son la **correlacion** y la **covarianza**, son dos medidas que nos van a permitir entender la relacion entre dos variables aleatorias, **x** e **y**. Pero para hablar de ellas debemos entender el concepto de estandarizacion, el primer conceptos.

Estandarizar una variable consiste en transformar una distribución N(µ, σ) en otra normal N(0, 1).

Los detalles de los conceptos aplicados en Python se encuentran en el notebook.

## Construir conceptos estadísticos analíticos

### Estimadores

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/estadistica-analitica/4.%20Construir%20conceptos%20estad%C3%ADsticos%20anal%C3%ADticos/11_Estimadores.ipynb)

Una población o una variable aleatoria que viene de una población puede ser muestreada y calculada utilizando una pequeña porción de la misma. Sobre la muestra quisieramos encontrar algunos parametros poblacionales que la describan perfectamente. Recordemos una variable aleatoria normal que puede ser descripta con la media (µ) y su desviación estandar (σ), esto se simboliza --> N(µ, σ).

Lo que queremos es inferir o extraer una conclusión de la población a través de la muestra tomada de la población y obteniendo sus parámetros descriptivos.

A partir de lo dicho, queremos encontrar los mejores estimadores de los parámetros poblaciones, ¿cuales serán estos? Para saber esto debemos saber que es un [estimador](https://es.wikipedia.org/wiki/Estimador) y cuales serán los de [máxima verosimilitud](https://es.wikipedia.org/wiki/M%C3%A1xima_verosimilitud).

- Un estimador es un estadístico (esto es, una función de la muestra) usado para estimar un parámetro desconocido de la población.
- Los estimadores por máxima verosimilitud (conocida también como EMV y, en ocasiones, MLE por sus siglas en inglés) es un método habitual para ajustar un modelo y estimar sus parámetros.

### Distribuciones muestrales

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/estadistica-analitica/4.%20Construir%20conceptos%20estad%C3%ADsticos%20anal%C3%ADticos/12_Distribuciones_muestrales.ipynb)

En la siguiente sección estudiamos las distribuciones muestrales mas importantes.

Con estas funciones podemos aproximar o estimar parámetros poblacionales de la siguiente manera:

1. Usamos la media muestral como mejor estimador cuando queremos estimar:

- Media.
- Proporción de una función de Bernoulli.
- Lambda de una distribución Poisson o Exponencial.

Pueden pasar 2 casos:

- Usamos la **función Normal** estandar si conocemos la varianza.
- Usamos la **función t-student** si NO conocemos la varianza. Debemos entender que son los [grados de libertad](https://www.webyempresas.com/grados-de-libertad-en-estadistica/)

2. Usamos la varianza muestral como mejor estimador si queremos estimar:

- La varianza

Pueden pasar 2 casos:

- Usamos la **función Chi-cuadrada** si vamos a hacer inferencia de una sola varianza.
- Usamos la **F Fisher-Snedecor** para el cociente de 2 varianzas, varianza de X sobre varianza de Y.

### Teorema del Límite Central

[Notebook del contenido](https://github.com/francomanca93/fundamentos-de-estadistica-con-python/blob/estadistica-analitica/4.%20Construir%20conceptos%20estad%C3%ADsticos%20anal%C3%ADticos/13_Teorema_del_limite_central.ipynb)

En esta sección aplicamos el teorema del Límite central con dos distribuciones, una exponencial y otra uniforme y vemos como aplicar el teorema a estas.

Este concepto nos permitirá aproximar la función de distribución de una variable aleatoria de la cual no conocemos previamente su distribución.

El teorema de limite central indica que si sumamos **n** variables aleatorias independientes con un **n > 30** podemos aproximar la función utilizando la curva de la función Normal o la curva de la campana de Gauss. Incluso si las variables aleatorias originales no se distribuyen como una normal.

## Realizar inferencias estadisticas a partir de una muestra

## Usar modelos estadísticos para exploración y predicción
