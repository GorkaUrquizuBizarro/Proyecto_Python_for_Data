# Proyecto_Python_for_Data

## 1. Objetivo del proyecto.
Realizar un análisis exploratorio de los datos que puedes encontrar que te aportamos. Para realizar este análisis es obligatorio realizarlo con Python.

## 2. Requisitos del proyecto.
A lo largo del proyecto tienes que cubrir los siguientes puntos:

- Transformación y limpieza de los datos.
- Análisis descriptivo de los datos.
- Visualización de los datos.
- Informe explicativo del análisis.

## 3. Herramientas para realizar el proyecto.
Tendrás que realizar el proyecto usando estás herramientas:
- Python
- Pandas
- Visual Studio Code

## 4. Estructura del repo

## 5. Recap Sesiones
**Sesión 1:**
- Creación de repositorio.
- Creación de archivo Readme.
- Lectura del informe proporcionado.
- Creación del sistema de carpetas del repositorio.
- Se añadio conjunto de datos originales: 'bank_additional' y 'customer-detail' 

**Sesión 2:**
- EDA preliminar de los conjuntos de datos con los archivos 'bank_additional.ipynb' y 'customer_detail.ipynb'
- Transformación y limpieza de los conjuntos de datos antes del análisis de gestión de nulos.


## 6. Datos
Los datos con los que vas a trabajar son los que te aportamos en este link.
Estos conjuntos de datos están relacionados con campañas de marketing directo de una institución bancaria portuguesa. Las campañas de marketing se basaron en llamadas telefónicas. A menudo, se requería más de un contacto con el mismo cliente para determinar si el producto (depósito a plazo bancario) sería suscrito o no. Las columnas que tenemos en el primer dataset ('bank-additional.csv') son:

-	**age:** La edad del cliente.
-   **job:** La ocupación o profesión del cliente.
-	**marital:** El estado civil del cliente.
-	**education:** El nivel educativo del cliente.
-	**default:** Indica si el cliente tiene algún historial de incumplimiento de pagos (1: Sí, 0: No).
-	**housing:** Indica si el cliente tiene un préstamo hipotecario (1: Sí, 0: No).
-	**loan:** Indica si el cliente tiene algún otro tipo de préstamo (1: Sí, 0: No).
-	**contact:** El método de contacto utilizado para comunicarse con el cliente.
-	**duration:** La duración en segundos de la última interacción con el cliente.
-	**campaign:** El número de contactos realizados durante esta campaña para este cliente.
-	**pdays:** Número de días que han pasado desde la última vez que se contactó con el cliente durante esta campaña.
-	**previous:** Número de veces que se ha contactado con el cliente antes de esta campaña.
-	**poutcome:** Resultado de la campaña de marketing anterior.
-	**emp.var.rate:** La tasa de variación del empleo.
-	**cons.price.idx:** El índice de precios al consumidor.
-	**cons.conf.idx:** El índice de confianza del consumidor.
-	**euribor3m:** La tasa de interés de referencia a tres meses.
-	**nr.employed:** El número de empleados.
-	**y:** Indica si el cliente ha suscrito un producto o servicio (Sí/No).
-	**date:** La fecha en la que se realizó la interacción con el cliente.
-	**contact_month:** Mes en el que se realizó la interacción con el cliente durante la campaña de marketing.
-	**contact_year:** Año en el que se realizó la interacción con el cliente durante la campaña de marketing.
-	**id_:** Un identificador único para cada registro en el dataset.

El segundo set de datos ('customer-details.xlsx') es un archivo Excel que nos da información sobre las características demográficas y comportamiento de compra de los clientes del banco. Este Excel consta de 3 hojas de trabajo diferentes, en cada una de ellas tenemos los clientes que entraron en el banco en diferentes años. Sus columnas son:

-	**Income:** Representa el ingreso anual del cliente en términos monetarios.
-	**Kidhome:** Indica el número de niños en el hogar del cliente.
-	**Teenhome:** Indica el número de adolescentes en el hogar del cliente.
-	**Dt_Customer:** Representa la fecha en que el cliente se convirtió en cliente de la empresa.
-	**NumWebVisitsMonth:** Indica la cantidad de visitas mensuales del cliente al sitio web de la empresa.
-	**ID:** Identificador único del cliente.

## 7. Método de entrega.
La entrega del proyecto se hará a través de GitHub. Para entregarlo tendrás que copiar la url del repositorio de GitHub, asegurate que el repositorio está publicado como público hasta la finalización del curso, requisito indispensable para poder realizar la corrección. Tu repositorio tiene que constar, al menos, de los siguientes archivos/carpetas:
- **Archivo README.md**, que recoja los pasos seguidos durante el proyecto y el informe de tú análisis.
- **Una carpeta de datos** donde guardes los archivos en bruto, asociados a este proyecto, y los datos guardados después de las transformaciones.
- **Una carpeta con los notebooks o archivos py** donde hayas realizado todos los pasos pedidos en el proyecto


