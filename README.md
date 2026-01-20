# ds-siniestros-vivienda
Análisis y modelación de siniestros de vivienda a partir de datos históricos, enfocado en estimación de riesgo por sector mediante métricas de frecuencia, severidad y primas indicativas.

Executive Summary
Este proyecto presenta un análisis de datos históricos de siniestros de vivienda con el objetivo de estimar el nivel de riesgo por sector, combinando métricas de frecuencia, severidad y una prima indicativa por vivienda. El análisis está orientado a mostrar cómo los datos pueden apoyar la toma de decisiones en contextos actuariales y de gestión de riesgos.
Objetivo del proyecto
Analizar el comportamiento de los siniestros de vivienda y evaluar el riesgo relativo entre distintos sectores, utilizando información histórica de siniestros y estimaciones del número de viviendas expuestas.
En particular, el proyecto busca:
Identificar diferencias en frecuencia y costo de siniestros entre sectores.
Calcular métricas agregadas relevantes para análisis de riesgo.
Proponer una prima indicativa por vivienda como ejercicio analítico.
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
Metodología
El flujo de trabajo del proyecto es el siguiente:
Carga y limpieza de datos
Lectura de las hojas del archivo Excel.
Normalización y validación de nombres de columnas.
Verificación de consistencia entre tablas antes de realizar uniones.
Análisis exploratorio de datos (EDA)
Revisión de la distribución de siniestros.
Análisis del costo de siniestros por sector.
Exploración de variables relevantes como antigüedad de la vivienda.
Agregación por sector
Cálculo de frecuencia de siniestros.
Cálculo de costo total y costo promedio.
Integración de la información de viviendas estimadas.
Estimación de riesgo
Cálculo de métricas de riesgo por sector.
Obtención de una prima indicativa por vivienda como ejercicio analítico.
Conclusiones
Interpretación de resultados.
Identificación de sectores con mayor y menor nivel de riesgo relativo.
