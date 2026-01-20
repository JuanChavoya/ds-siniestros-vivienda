# ds-siniestros-vivienda
Análisis y modelación de siniestros de vivienda a partir de datos históricos, enfocado en estimación de riesgo por sector mediante métricas de frecuencia, severidad y primas indicativas.

Descripción de los datos

El análisis se basa en un archivo de Excel que contiene dos conjuntos de información:

1. Base de siniestros (DB_SINIESTRO)

Contiene información histórica de siniestros de vivienda, incluyendo:

Identificador de siniestro

Sector

Año de ocurrencia

Indicador de siniestro

Antigüedad de la vivienda

Costo del siniestro


2. Viviendas estimadas (VIVIENDAS_ESTIMADAS)

Incluye el número estimado de viviendas por sector, utilizado como aproximación de la exposición al riesgo.


---

Metodología

El flujo de trabajo del proyecto es el siguiente:

1. Carga y limpieza de datos

Lectura de las hojas del archivo Excel.

Normalización y validación de nombres de columnas.

Verificación de consistencia entre tablas antes de realizar uniones.



2. Análisis exploratorio de datos (EDA)

Revisión de la distribución de siniestros.

Análisis del costo de siniestros por sector.

Exploración de variables relevantes como antigüedad de la vivienda.



3. Agregación por sector

Cálculo de frecuencia de siniestros.

Cálculo de costo total y costo promedio.

Integración de la información de viviendas estimadas.



4. Estimación de riesgo

Cálculo de métricas de riesgo por sector.

Obtención de una prima indicativa por vivienda como ejercicio analítico.



5. Conclusiones

Interpretación de resultados.

Identificación de sectores con mayor y menor nivel de riesgo relativo.

