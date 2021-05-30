<a name='inicio'></a>
# COBIFY

### Se tiene que hallar respuestas justificadas mediante los datos dados de qué combustible es más recomendable para la compañía.

![portada](https://github.com/as-Solo/Proyecto_Ubicacion/blob/main/img/portada_Readme.jpg)

### Contenido

1. [Información General](#Información)
2. [Desarrollo del proyecto](#Pasos)
3. [Librerías](#Librerías)
4. [Tecnología](#Tecnología)

<a name='Información'></a>
## Información general

La idea básica de este proyecto es averiguar si el tipo de gasolina utilizada en los coches de la flota afectará al consumo y al gasto. Además se pide que demos algún valor añadido a las conclusiones aportando más información de la dada al dataset. Así como almacernarlo todo en una base de datos y crear una API que permita la gestión adecuada de la información almacenada en la misma.



<a name='Pasos'></a>
## Desarrollo del proyecto

1. [Limpieza de datos](#limpieza)
1. [Visualización de datos](#visualizacion)
1. [Crear bases de datos](#bbdd)
1. [Creación de la API](#API)
1. [Story Telling](#storyTelling)

<a name = limpieza></a>
### 1. Limpieza de datos

Lo primero fue hacernos una idea de con qué datos contábamos en el csv ofrecido. Su estructura, su tipo, su heterogeneidad. No encontramos con esto:

![df_head_inicio](https://github.com/as-Solo/reto_data/blob/main/img/df_head_inicio.jpg)

La gran mayoría de los datos estaban limpios, y exceptuando un par de columnas no había demasiados valores vacíos. El mayor inconveniente con el que nos encontramos fue que en varios casos la columnas tenía un tipo de valor distinto al que necesitábamos para hacer las operaciones que necesitábamos y se tuvo que cambiar.

Añadimos varias columnas con los datos relativos al gasto y a la emisiones de Co2 ya que la empresa compartió con nosotros sus preocupaciones con respecto a la ecología.

<a name = visualizacion></a>
### 2. Visualización

Queríamos descartar que hubiese algún factor que fuese especialmente determinante para el consumo, por eso, hicimos todas las muestras posibles que se nos ocurrieron con respecto al consumo y al gasto. También sacamos un mapa de calor con las relaciones de todas las columnas. Llegados a este punto teníamos todo lo necesario para sacar unas primeras conclusiones y empezar a trabajar sobre los datos con las gráficas.

<a name = bbdd></a>
### 3. Creación de base de datos

Con toda la información que teníamos, filtramos el dataset para que no tuviese valores duplicados o redundantes y pasamos los datos a dos bases de datos, una en SQL y otra en MongoDB. En la carpeta data se encuentra tanto el .json correspondiente a la colección de MongoDB 'estadisticas_coche.json' como el sql necesario para crear la base de datos en MySQL 'EstadisticasCoche.sql'.

<a name = API></a>
### 4. API

Actualmente nos encontramos trabajando en este punto del proceso. La idea es crear una herramienta sencilla con Streamlit que permita al usuario pedir datos relacionados entre si a través de la base de datos de MongoDB.

<a name = storyTelling></a>
### 5. Story Telling

En el Jupyter Notebook 05_Story_Telling se desarrolla el proceso que se ha seguido, apoyado por las gráficas que hemos ido sacando de los datos proporcionados.


<a name = Librerías></a>
## Librerías:

***
Para este proyecto se han usado estas librerías y módulos. 
- [sys](https://docs.python.org/es/3.10/library/sys.html)
- [pandas](https://pandas.pydata.org/docs/)
- [numpy](https://numpy.org/doc/stable/)
- [pymongo](https://pypi.org/project/pymongo/)
- [json](https://docs.python.org/3/library/json.html)
- [dotenv](https://pypi.org/project/python-dotenv/)
- [os](https://docs.python.org/3/library/os.html)
- [functools](https://docs.python.org/es/3/library/functools.html)
- [operator](https://docs.python.org/3/library/operator.html)
***

<a name = Tecnología></a>
## Tecnología: 

Distinto programas y utilidades usados en este proyecto:
* [Jupyter Notebook](https://jupyter.org/)
* [Python](https://www.python.org/): Version 3.8
* [Visual Studio Code](https://code.visualstudio.com/)
* [plotly](https://plotly.com/graphing-libraries/)
* [MongoDBCompass](https://docs.mongodb.com/compass/master/)
* [MySQL Workbench](https://dev.mysql.com/doc/)

## Autor:

* [Alejandro S. del Solo](https://github.com/as-Solo)

[volver arriba](#inicio)