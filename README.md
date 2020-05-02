---
title: "Base de datos Banco Mundial - Chile"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Sobre la Base de Datos

Esta base de datos fue obtenida de las estadisticas historicas (1960 a 2018) que guarda el banco mundial sobre los paises de la OCDE, incluido Chile desde la sigueinte URL: <https://datos.bancomundial.org/?locations=CL-DE-AU-AT-BE-CO-CA-KR-DK-SI-ES-US-EE-FI-FR-GR-HU-IE-IS-IL-IT-JP-LV-LT-LU-MX-NO-NZ-NL-PL-PT-GB-CZ-SK-SE-CH-TR>.

En el archivo *API_Download_DS2_es_csv_v2_1035831.csv* se encuentra valores separados por comas, que nos permitiran realizar estudios estadisticos acerca de distintas areas de los paises OCDE, en ambitos de desarrollo economico y social, abarcando temas como salud, tecnología, comercio, etc.

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
En el archivo: Metadata_Indicator_API_Download_DS2_es_csv_v2_1035831.csv se encuentran todas las areas que existe informacion historica, su descripcion y el tipo de medida utilizada.

## Preguntas
* ¿Cual es la evolucion del PIB de los paises OCDE con respecto a Chile?
* ¿Cual es la inversion en I+D de los paises OCDE con respecto a Chile?
* ¿Cual es el crecimiento del desarrollo Tecnologico de los paises OCDE con respecto a Chile?

AL tener muchas variables esta BD pueden realizarse muchas preguntas acerca de la misma 