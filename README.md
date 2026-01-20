# Análisis de Siniestros de Vivienda por Sector

## Resumen Ejecutivo
Este proyecto analiza datos históricos de siniestros de vivienda con el objetivo de estimar el nivel de riesgo por sector. A partir de métricas de frecuencia, severidad y una prima indicativa por vivienda, se muestra cómo los datos pueden apoyar procesos de análisis actuarial y de gestión de riesgos.

---

## Objetivo del proyecto
Evaluar el comportamiento de los siniestros de vivienda y comparar el riesgo relativo entre sectores, utilizando información histórica de siniestros y estimaciones de viviendas expuestas.

---

## Datos utilizados
El análisis se basa en un archivo de Excel con dos hojas principales:

### Base de siniestros (DB_SINIESTRO)
Contiene información histórica de siniestros de vivienda, incluyendo:
- Identificador de siniestro
- Sector
- Año de ocurrencia
- Antigüedad de la vivienda
- Costo del siniestro

### Viviendas estimadas (VIVIENDAS_ESTIMADAS)
Incluye el número estimado de viviendas por sector, utilizado como aproximación de la exposición al riesgo.

El archivo esperado se encuentra en la carpeta data/.

---

## Metodología
1. Carga y limpieza de datos.
2. Análisis exploratorio de los siniestros.
3. Agregación de métricas por sector.
4. Integración de la información de viviendas estimadas.
5. Cálculo de métricas de riesgo y prima indicativa.
6. Análisis e interpretación de resultados.

---

## Resultados principales
- Existen diferencias significativas en la frecuencia y el costo de los siniestros entre sectores.
- Algunos sectores presentan mayor costo agregado, mientras que otros muestran mayor frecuencia relativa.
- La prima indicativa por vivienda permite comparar el riesgo relativo entre sectores de forma sencilla.

---

## Estructura del repositorio
ds-siniestros-vivienda/ ├── README.md ├── notebooks/ │   └── Proyecto_Viviendas_portfolio.ipynb ├── data/ │   ├── README.md │   └── Siniestros_vivienda_proyecto_final.xlsx └── outputs/

---

## Cómo ejecutar el proyecto
1. Clonar o descargar el repositorio.
2. Colocar el archivo de datos en la carpeta data/.
3. Abrir el notebook ubicado en notebooks/.
4. Ejecutar las celdas en orden.

---

## Tecnologías utilizadas
- Python
- pandas
- numpy
- matplotlib
- seaborn
- openpyxl

---

## Notas
Este proyecto tiene fines demostrativos y educativos. Los resultados no deben interpretarse como recomendaciones reales de tarificación o gestión de riesgo.
