# Diplodatos2021

## Título del Proyecto: Ciencia de Datos aplicada en la distribución de Energía Eléctrica
### Descripción del dataset, problemas interesantes asociados
El dataset contiene las informaciones geográficas, consumidores y activos, de la empresa EBO de la ciudad de Campina Grande, en el estado de Paraíba, Brasil. El documento Módulo10_Revisão0.pdf tiene una descripción detallada del contenido del dataset.

Uno de los mayores desafíos de esta industria es conocer los impulsores de la Calidad de Servicio que permitan la toma de decisiones eficientes sobre los costos operativos e inversiones.
El objetivo de este proyecto es que el estudiante a lo largo de las materias de la diplomatura identifique y aplique diferentes técnicas de análisis/procesamiento de los datos que generen información relevantes para la toma de decisiones.



## Objetivos generales para cada materia:

### Análisis y Visualización
* Configuración del environment para el proyecto.

* Presentación del dataset. 

* Presentación del software Qgis.

* Presentación  de la librería geopandas

* Introducción a las bases de datos georreferenciadas, sistemas de coordenadas y proyecciones.

* Generación de features a partir de variables georeferenciadas (1):

  -  Distancia Euclideana a objetos geográficos

*  Vinculación de las diferentes tablas relevantes (UCBT, UNTRD, PONNOT, UNSE).

* Correlación entre variables/análisis de independencia. A través de este análisis se debe identificar el impacto de cada variable sobre la calidad de servicio.

  

### Análisis y Curación
Para análisis y curación podrán aplicarse sobre el dataset los siguientes puntos:

* Chequeo  de claves únicas.
* Normalización de los nombres de las columnas en los dataframes.
* Tratamiento de valores faltantes.
* Codificación de variables categóricas.
* Análisis de valores atípicos.
* Persistencia de los resultados.
* Ordenamiento de las columnas.
* Vinculación de la tablas a través de las llaves de las tablas
* Eliminar columnas que no aporten información.
* Crear un dataset único a partir de las tablas provistas incluyendo toda la información útil en una misma tabla.

- Generación de features a partir de Grafos (2)
  - Cálculo de features por métricas del grafo
  - Cálculo de features por rutas de conexión

<u>**Preparación del video de presentación del proyecto**</u> 

### Introducción al ML
El dataset está compuesto por muchas tablas con información geográfica y variables sobre las cuales se puede aplicar análisis y procesamiento. 
El objetivo en este punto es que los estudiantes aprendan a dividir el dataset, a seleccionar el modelo y evaluar las métricas.
Se propone un sistema predictivo sencillo (regresión lineal) utilizando los features trabajados en los prácticos anteriores. Con esto podrá aplicarse:

* Carga de datos.
* División en conjuntos de entrenamiento y evaluación.
* Elección de un modelo.
* Selección de hyperparámetros.
* Métricas sobre el conjunto de evaluación.

### Aprendizaje Supervisado
A partir del modelo seleccionado en el práctico anterior, que utilizaremos como baseline e ir complejizando el modelo con la adición de diferentes variables y modelos mas complejos. El objetivo es implementar en este caso un sistema predictivo de calidad de servicio (FEC) en base a la información geográfica.  

### Aprendizaje No Supervisado
Para la aplicación de aprendizaje no supervisado sería interesante realizar una Segmentación de la calidad de servicio mediante técnicas de clusterización con las diferentes variables disponibles.
Hacer un análisis de los grupos obtenidos que nos permita evaluar cuales son las variables que mejor explican la calidad de servicio. Estas variables podemos utilizarlas en los algoritmos de aprendizaje supervisado para mejorar su calidad de predicción. Podría utilizarse un algoritmo como K Means con algún método de optimización de número de clusters como elbow method.

<u>**Preparación del video de presentación de la mentoría**</u> 



### Cronograma

| Fecha                 |Item| Práctico                                |
| --------------------- | ----|--------------------------------------- |
| 06/06                 |Práctico 1 | análisis y visualización         |
| 04/07                 |Práctico 2 |análisis y curación               |
| 04/07                 |Presentación 1 | video de presentación del proyecto  |
| 17/07                 |Jornada 1| jornada de discusión de propuestas de proyectos |
| 15/08                 |Práctico 3|  introducción al aprendizaje automático |
| 12/09                 |Práctico 4 | práctico de aprendizaje supervisado             |
| 02/10                 |Práctico 5 | práctico de aprendizaje no supervisado             |
| 04/07                 |Presentación 2 | video de presentación de la mentoría  |
| 12/11/2020 – 13/11/2020 | Jornada 2    |jornada de presentación de mentorías|
