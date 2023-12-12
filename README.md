# Análisis descriptivo y exploratorio sobre un dataset del uso de EcoBicis
Trabajo Práctico 1 de la materia Laboratorio de Datos (2do cuatrimestre 2023) sobre el reporte de un dataset sobre el uso de EcoBicis, donde se hace un Análisis Descriptivo y Exploratorio para encontrar tendencias y patrones en los datos.

# Objetivo
El objetivo de este TP es que apliquen todo lo que aprendieron hasta ahora de decripción, visualización, exploración y manipulación de datos al análisis de dos datasets. Los dos son datasets públicos, uno contiene el registro de usos de bicicletas públicas de CABA y el otro datos climáticos diarios.

# Datasets
Dataset de uso de EcoBici: <br>
El dataset de uso del sistema Ecobici de la Ciudad de Buenos Aires está disponible acá. En particular, vamos a trabajar con datos del año 2022. El dataset que está en la página tiene casi 3 millones de registros, pero para este TP preparamos un dataset reducido de 10000 observaciones. Ese dataset reducido se encuentra acá.

Importación y preprocesado de datos en R: <br>
En primer lugar seleccionar solo los viajes de entre 5 minutos y 1 hora de duración. Luego reconozcan qué significa cada variable. En la página donde está el dataset original encontrarán parte de esta información. Verifiquen que las variables tienen sentido, que tengan datos para todos los días del 2023, piensen en qué unidades se miden las variables numéricas, etc.

Dataset de clima: <br>
Importen datos meteorológicos y climáticos de MeteoStat de esta página. En particular, consideren datos de la estación meteorológica de Aeroparque (ID 87582), desde el 1ro de enero de 2022 hasta el 31 de diciembre de 2022.

Importación y preprocesado de datos en R: <br>
Descarguen ese dataset en formato csv e importen los datos en R. Verifiquen que tienen datos de todos los días del 2023. ¿Qué representa cada variable?

# Análisis descriptivo
En esta etapa tienen que trabajar con cada dataset por separado. Tienen que hacer un análisis descriptivo de las variables para familiarizarse con los datos y reconocer sus características y variabilidad.

En cuanto al dataset de uso de bicicletas, ¿cómo se codifica el género de los usuaries? ¿lo usa más algún grupo? ¿cuáles son los viajes mas comunes (de dónde salen y dónde llegan?). Describan la variable que indica la duración de viaje (globalmente y por separado para los 5 viajes más frecuentes). En cuanto al dataset de datos climáticos, ¿qué variables tienen? ¿Cómo varía la temperatura a lo largo del año? ¿Tiene sentido? ¿Cómo es la cantidad de lluvias según el mes?

Estos son sólo algunas ideas, ustedes pueden tener otras. Para cada caso piensen cómo describirían lo que quieren mostrar (si una tabla, un gráfico, qué grafico, etc).

# Análisis Exploratorio
Supongan que quieren entender patrones de uso del sistema de Ecobici. Su variable de interés es el número de usos del sistema por día yquieren entender qué factores podrían explicar ese número. Algunas preguntas disparadoras para el análisis exploratorio son:

&nbsp;&nbsp;&nbsp;&nbsp; • ¿Cómo varía el uso de la EcoBici a lo largo del año? <br>
&nbsp;&nbsp;&nbsp;&nbsp; • ¿El uso es diferente en días de semana vs. fin de semana? (para crear esta variable, investiguen el uso de la función weekdays()). <br>
&nbsp;&nbsp;&nbsp;&nbsp; • ¿Hay algún día atípico en el uso de la EcoBici? ¿le pueden encontrar una explicación? <br>
&nbsp;&nbsp;&nbsp;&nbsp; • ¿Si hace mucho calor se usa más o se usa menos (o depende)? <br>
&nbsp;&nbsp;&nbsp;&nbsp; • ¿Y si llueve? <br>
Piensen más preguntas. Es libre, pueden explorar por dónde se les ocurra. Realicen visualizaciones pertinentes, muestren datos de resumen cuando les parezca adecuado, etc.
