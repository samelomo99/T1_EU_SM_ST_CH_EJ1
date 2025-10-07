###### \# 🏙️ Taller 1 - Economía Urbana  

###### \## 📊 Ejercicio 1: Modelos de precios de vivienda

###### 

Este repositorio contiene el desarrollo del \*\*Ejercicio 1\*\* del Taller 1 del curso de \*\*Economía Urbana\*\*.  

El objetivo es estimar y comparar distintos modelos de precios de vivienda utilizando información del \*\*Cook County (Illinois)\*\*.

###### 

###### ---

###### 

###### \## 📁 Estructura del repositorio

###### 

###### \### 🧠 `code/`

Contiene el código en \*\*R\*\* con todas las rutinas empleadas en el ejercicio:

\- Limpieza y preparación de datos.  

\- Especificación y estimación de los modelos.  

\- Generación de tablas y gráficas de resultados.

###### 

###### \### 🗂️ `data/`

Incluye la base de datos utilizada en el análisis, con información de transacciones inmobiliarias, características estructurales y variables de control.

###### 

###### \### 📈 `export/`

Almacena los productos finales del ejercicio:

\- Gráficas de evolución de precios.  

\- Tablas resumen de resultados econométricos.  

###### 

###### ---

###### 

###### \## ⚙️ Desarrollo del ejercicio

###### 

El trabajo se estructuró en tres etapas principales:



1\. \*\*Preparación y limpieza de datos\*\* 🧹  

&nbsp;  Se realizó una descripción del conjunto de datos, eliminando observaciones con valores faltantes (\*NA\*) y seleccionando las variables de control relevantes para las regresiones.



2\. \*\*Estimación de modelos\*\* 📉  

&nbsp;  Se implementaron tres enfoques de modelación del precio de la vivienda:  

&nbsp;  - Modelo \*\*Hedónico simple\*\*.  

&nbsp;  - Modelo \*\*Hedónico con efectos fijos y clúster a nivel de propiedad\*\*.  

&nbsp;  - Modelo \*\*de Ventas Repetidas\*\* (\*Repeat Sales\*).  



3\. \*\*Comparación de resultados\*\* 🔍  

&nbsp;  Se compararon los modelos en términos de número de observaciones, poder explicativo y comportamiento temporal del índice de precios, evaluando la coherencia entre metodologías.





