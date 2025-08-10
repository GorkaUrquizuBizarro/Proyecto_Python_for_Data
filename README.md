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

**Sesión 3:**
- Gestión de nulos para los archivos de datos bank_additional y customer-detail.

**Sesión 4:**
- Análisis descriptivo de los datos.

**Sesión 5:**

**Sesión 6:**
- Conclusiones del estudio.

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

## 8. Conclusiones

**Archivo bank_aditional:**

Las conclusiones generales del análisis se detallan a continuación. Para entender mejor el resumen de los datos vamos a 
separarlos en dos campos:
- Tipo de cliente que acaba realizando la suscripción.

- Que variables son las que afectan a la suscripción.

    - **Tipo de Cliente**:
        - El mayor número de clientes que acaban suscritos son aquellos que se encuentran entre los rangos de 18-25 años y los mayores de 66.
        - Por ocupación estos clientes son "Retired" y "Student".
        - En su gran mayoria "Singels".
        - Con un nivel de estudios "Illiterate"
        - Han sido contactados por "Celular"
        - No disponen de otros prestamos.

    - **Variables clave**:
        - Las llamadas más largas se asocian con suscripción.
        - Clientes contactados recientemente son más propensos a suscribirse.
        - Más contactos previos = más probabilidad de suscripción.
        - En peores contextos laborales (emp.var.rate negativa) hubo más suscripciones.
        - Tasas más bajas (euribor negativo), más conversiones (época de crisis)

**Archivo customer_detail:**

Conclusiones del Análisis Descriptivo

- **Income Clientes:**
    - La mayoría de los clientes se concentran en rangos "Medio" a "Alto". 
    - Los clientes del grupo de ingreso muy alto presentan una mayor actividad web promedio, lo que sugiere un mayor involucramiento con la plataforma. Sin embargo, también se detectan clientes de ingresos bajos con comportamientos digitales intensivos, lo que representa un nicho potencial para campañas personalizadas.

- **Visitas Web:**
    - No existe una relación lineal entre el nivel de ingreso y las visitas web, 
    - No se observa un patrón claro; clientes nuevos y antiguos tienen comportamientos digitales similares.
    - No se encuentra una correlación significativa con ninguna variable.
    - Los clientes visitan el sitio web en promedio 16.6 veces al mes, con un rango de 1 a 32 visitas.
    - La desviación estándar de 9.24 indica diferencias significativas en el comportamiento digital de los usuarios; algunos interactúan mucho más con la web que otros

- **Número de clientes:**
    - El numero de clientes adquiridos a lo largo del tiempo a ido en clara disminución aunque hemos observado un repunte en el último año.  
    - En promedio, los clientes llevan alrededor de 4,472 días con la empresa (aproximadamente 12 años), lo que sugiere una base consolidada y posiblemente leal.
    - El rango va desde 3,874 hasta 4,969 días, lo que representa una antigüedad de entre 10.6 y 13.6 años, mostrando una base de datos bastante homogénea en términos de tiempo de permanencia. 
    
- **Tipo de familia:**
    - La gran mayoria de nuestros clientes tienen hijos casi un 90%
    - En su gran mayoria tienen dos hijos por familia.
    - En promedio, los hogares tienen aproximadamente 1 hijo y 1 adolescente, con valores que varían entre 0 y 2 para ambas variables.
    - La baja desviación estándar (≈0.82) sugiere que la mayoría de los hogares tienen una estructura familiar similar, con pocas variaciones.