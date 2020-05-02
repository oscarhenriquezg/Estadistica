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

PAÍS | AÑO DE ADHESIÓN
-----------------------
ALEMANIA | 1961
AUSTRALIA | 1971
AUSTRIA | 1961
BÉLGICA | 1961
CANADÁ | 1961
CHILE | 2010

COLOMBIA | 2020

COREA | 1996

DINAMARCA | 1961

ESLOVENIA | 2010

ESPAÑA | 1961

ESTADOS UNIDOS | 1961

ESTONIA | 2010

FINLANDIA | 1969

FRANCIA | 1961

GRECIA | 1961

HUNGRÍA | 1996

IRLANDA | 1961

ISLANDIA | 1961

ISRAEL | 2010

ITALIA | 1962

JAPÓN | 1964

LETONIA | 2016

LITUANIA | 2018

LUXEMBURGO | 1961

MÉXICO | 1994

NORUEGA | 1961

NUEVA ZELANDA | 1973

PAÍSES BAJOS | 1961

POLONIA | 1996

PORTUGAL | 1961

REINO UNIDO | 1961

REPÚBLICA CHECA | 1995

REPÚBLICA ESLOVACA | 2000

SUECIA | 1961

SUIZA | 1961

TURQUÍA | 1961





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