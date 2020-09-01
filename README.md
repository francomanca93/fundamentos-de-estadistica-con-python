
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
  - [Aplicar conceptos de probabilidad a eventos aleatorios](#aplicar-conceptos-de-probabilidad-a-eventos-aleatorios)
  - [Construir conceptos estadísticos analíticos](#construir-conceptos-estadísticos-analíticos)
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

## Aplicar conceptos de probabilidad a eventos aleatorios

## Construir conceptos estadísticos analíticos

## Realizar inferencias estadisticas a partir de una muestra

## Usar modelos estadísticos para exploración y predicción
