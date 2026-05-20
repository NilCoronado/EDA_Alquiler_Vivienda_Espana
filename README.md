# 🏠 EDA — Referencia del Precio del Alquiler en España

## 📌 Descripción del Proyecto

Este proyecto consiste en la realización de un **Exploratory Data Analysis (EDA)** sobre el mercado del alquiler en España utilizando el dataset oficial:

> **“Referencia del Precio del Alquiler de Vivienda”**  
> Fuente: datos.gob.es

El objetivo principal del proyecto es analizar la evolución y distribución del precio del alquiler en España, identificando patrones territoriales, diferencias entre provincias y tendencias temporales.

---

# 🎯 Objetivos del EDA

## Objetivo General

Analizar cómo varía el precio del alquiler en España según:
- provincia,
- municipio,
- tipo de vivienda,
- y evolución temporal.

---

## Objetivos Específicos

- Detectar diferencias territoriales en el precio del alquiler.
- Analizar la evolución histórica del alquiler.
- Identificar provincias y municipios con precios más elevados.
- Detectar posibles desigualdades territoriales.
- Analizar tendencias y distribuciones del mercado inmobiliario.

---

# 🧠 Hipótesis del Proyecto

## H1
Las grandes provincias presentan precios de alquiler significativamente superiores.

## H2
Existe una desigualdad territorial clara entre comunidades autónomas.

## H3
El precio del alquiler ha aumentado progresivamente con el paso de los años.

## H4
El tipo de vivienda influye en el precio del alquiler.

---

# 📂 Dataset Utilizado

## Fuente Oficial
https://datos.gob.es/es/catalogo/e05233601-referencia-del-precio-del-alquiler-de-vivienda

## Dataset principal
`VDP001_01.csv`

---

# 📊 Variables Principales

| Variable | Descripción |
|---|---|
| PROVINCIA | Provincia española |
| NOMBRE_MUNICIPIO | Municipio |
| COD_POSTAL | Código postal |
| ELEMENTO | Tipo de métrica analizada |
| TIPO_VIVIENDA | Tipo de vivienda |
| TIPO_MEDIDA | Tipo estadístico |
| AÑO | Año de referencia |
| VALOR | Valor numérico del indicador |

---

# 👥 División del Trabajo

---

# 👤 Persona 1 — Data Acquisition & Data Cleaning

## Responsabilidades

- Carga y validación del dataset
- Limpieza de datos
- Conversión de tipos
- Tratamiento de valores nulos
- Eliminación de duplicados
- Estandarización de columnas
- Creación del Data Dictionary
- Exportación del dataset limpio

## Entregables

- Dataset limpio
- Notebook de limpieza
- Data Dictionary
- Documentación del proceso

---

# 👤 Persona 2 — Exploratory Data Analysis & Visualización

## Responsabilidades

- Análisis univariante
- Análisis bivariante
- Análisis multivariante
- Creación de visualizaciones
- Heatmaps
- Boxplots
- Scatterplots
- Rankings territoriales
- Evolución temporal

## Entregables

- Notebook de análisis
- Visualizaciones finales
- Gráficos para presentación

---

# 👤 Persona 3 — Business Insights & Storytelling

## Responsabilidades

- Definición del enfoque de negocio
- Interpretación de resultados
- Extracción de insights
- Conclusiones finales
- Storytelling
- Presentación del proyecto
- Memoria final
- README y documentación

## Entregables

- Presentación
- Memoria PDF
- README final
- Guion del vídeo

---

# 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

# 📁 Estructura del Proyecto

```text
EDA_Vivienda_Espana/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_visualizations.ipynb
│
├── reports/
│   └── figures/
│
├── docs/
│
├── src/
│
├── README.md
├── requirements.txt
└── .gitignore