![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

# **PROYECTO INDIVIDUAL Nº3**

# <h1 align="center">**`Accidentes aéreos`**</h1>

## **Contexto**
La **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, les solicita la elaboración de un informe y un dashboard interactivo que recopile tal información. 

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio.

## **Propuesta de trabajo**
A raíz de esta solicitud, nuestro Project Manager nos encarga una serie de tareas a cumplir: 

+ Realizar un EDA con el dataset provisto, junto con un reporte de calidad y diccionario de datos
+ Buscar y relacionar información relevante con los eventos
+ Crear una base de datos en un motor SQL e ingestar el csv procesado
+ Elaborar un dashboard e idear un storytelling con el objetivo de presentarlo ante la OACI
+ Adjuntar todo el trabajo en un repositorio de GitHub

# <h1 align="center">**`Análisis exploratorio de datos`**</h1>

## **Dataset Inicial(Henry)**
Reporte de calidad

![](https://github.com/BonfantiMatias/PI03-Henry/blob/main/images/Inicial_01.png)
![](https://github.com/BonfantiMatias/PI03-Henry/blob/main/images/Inicial_02.png)

Diccionario 


## **ETL**

Partiendo del dataset inicial, se realizo la limpienza y normalizacion. Tambien se agregaron nuevas columnas desde otro dataset con las coordenadas de los accidentes. Se renombraron las columnas con su respectiva traduccion.


## **Dataset Final**

![](https://github.com/BonfantiMatias/PI03-Henry/blob/main/images/Final_01.png)
![](https://github.com/BonfantiMatias/PI03-Henry/blob/main/images/Final_02.png)

Diccionario

## **Exportacion Dataframe a Postgres**

![](https://github.com/BonfantiMatias/PI03-Henry/blob/main/images/Postgres.png)
