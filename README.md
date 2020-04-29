---
title: "Base de datos Banco Mundial - Chile"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```


## Sobre la Base de Datos

Esta base de datos fue obtenida de las estadisticas historicas (1960 a 2018) que guarda el banco mundial sobre Chile desde la sigueinte URL: <https://datos.bancomundial.org/pais/chile>.

En el archivo API_CHL_DS2_es_csv_v2_1006027.csv se encuentra valores separados por comas, que nos permitiran realizar estudios estadisticos acerca de distintas areas del pais, en ambitos de desarrollo economico y social, abarcando temas como salud, tecnología, comercio, etc.

Algunos de los campos conn los que cuenta la BD son los sigueintes:

```
Deuda del gobierno central, total (% del PIB)
Deuda del gobierno central, total (UMN a precios actuales)
Adquisición neta de activos financieros (% del PIB)
Adquisición neta de activos financieros (UMN actual)
Gasto en investigación y desarrollo (% del PIB)
.
.
.
```
En el archivo: Metadata_Indicator_API_CHL_DS2_es_csv_v2_1006027.csv se encuentran todas las areas que existe informacion historica, su descripcion y el tipo de medida utilizada.

## Preguntas
Crecimiento del PIB por gobierno?
Crecimiento del desarrollo Tecnologico por decada?

AL tener muchas variables esta BD pueden realizarse muchas preguntas acerca de la misma 