<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO INDIVIDUAL Nº1 DATA SCIENCE MLOps** </h1>

## **DESARROLLO DEL PROYECTO**

Nos entregan 2 bases de datos no estructuradas de peliculas, a las cuales debiamos realizar el proceso ETL, EDA y luego un modelo de ML basado en contenido para la recomendación de peliculas. Se dispuso de todo este tratamiento en una API para se sea consumida por cualquier departamento de la compañia.


1. **Data Engineering**:

- **ETL (Extraction, Transformation and Loading)** (LINK AL PROCESO DE ETL [`ETL.ipynb`](./ETL.ipynb))
🌟Movies dataset
    * ANÁLISIS Y TRANSFORMACIÓN DE TIPOS DE DATOS
    * EXTRACCIÓN DE MES/AÑO, CREACIÓN DE COLUMNAS PARA CADA UNO.
    * REVISIÓN Y TRANSFORMACIÓN DE VALORES NULOS
    * ELIMINAMOS COLUMNAS QUE NO UTILIZAREMOS
    * CREAMOS COLUMNA RETURN A PARTIR DE REVENUE Y BUDGET
    * DESANIDAMOS 3 COLUMNAS ANIDADAS
   
🌟Credits dataset
    * ANÁLISIS Y TRANSFORMACIÓN DE TIPOS DE DATOS
    * DESANIDAMOS LAS 2 COLUMNAS ANIDADAS
    * GUARDAMOS AMBOS DATASET LIMPIOS POR SEPARADO

🌟Unimos los datasets (LINK AL PROCESO ['data.ipynb'](./data.ipynb))



