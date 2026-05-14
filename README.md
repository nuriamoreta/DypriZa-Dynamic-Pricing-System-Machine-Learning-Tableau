🇪🇸 DyPriZa | Dynamic Pricing Intelligence for Hospitality
## 📌 Resumen ejecutivo

DyPriZa es un proyecto de Dynamic Pricing aplicado al sector de alojamientos turísticos, orientado a optimizar estrategias de pricing mediante análisis de datos, machine learning y visualización ejecutiva.

El proyecto nace como un MVP (Minimum Viable Product) enfocado en demostrar cómo un sistema basado en datos puede ayudar a maximizar ingresos (ADR y RevPAR), mejorar la ocupación y facilitar la toma de decisiones en Revenue Management.

La solución integra análisis exploratorio, modelado predictivo y dashboards ejecutivos en Tableau para transformar datos de mercado en insights accionables.

## 🧩 Business Problem

En el sector hospitality, muchas decisiones de pricing siguen dependiendo de procesos manuales, reglas estáticas o análisis poco escalables.

DyPriZa busca abordar retos como:

- Optimización de precios en función de demanda y estacionalidad
- Detección de patrones de comportamiento del mercado
- Reducción de vacantes
- Mejora del RevPAR y ADR
- Centralización y visualización de KPIs clave
- Soporte a decisiones basadas en datos


## 🎯 Objetivo del proyecto

Desarrollar una solución reproducible capaz de recomendar precios óptimos para alojamientos turísticos mediante técnicas de análisis de datos y machine learning.


## 🧠 Metodología

**1. Ingesta y preparación de datos**

Integración de datos procedentes de Airbnb, AirDNA y datasets públicos
Normalización de formatos y validación de calidad
Limpieza de duplicados y tratamiento de valores atípicos

**2. Ingeniería de variables**

Creación de variables relacionadas con:
- Temporalidad
- Estacionalidad
- Lead time
- Segmentación geográfica
- Comportamiento de demanda

**3. Modelado predictivo**

Evaluación de modelos de Machine Learning para predicción de precios:
- Linear Regression
- GridSearch
- Comparativas de precisión y estabilidad

**4. Evaluación del rendimiento**

Métricas utilizadas:
- MAE
- RMSE
- Within5%
- Within10%
- Distribución de residuales
- Estabilidad temporal

**5. Visualización y reporting**

Desarrollo de dashboards ejecutivos en Tableau orientados a negocio y Revenue Management.


## 📊 Resultados principales
**KPIs globales del modelo**

- MAE ≈ 2.3
- RMSE ≈ 2.9
- Within5% ≈ 95%
- Within10% ≈ 99.17%

**Insights detectados**

Linear Regression mostró mayor estabilidad y menor dispersión de error
Barcelona presentó mayor volatilidad en temporada alta
Madrid mostró mayor error en temporada media
Junio y septiembre reflejaron mayor estabilidad predictiva



## 📈 Dashboard & Visualización

El proyecto incluye dashboards desarrollados en Tableau para el análisis ejecutivo y seguimiento del rendimiento del modelo.

**Visualizaciones implementadas**

- KPIs generales
- Real vs Predicho
- Dispersión Real vs Predicho
- Distribución de residuales
- Evolución temporal del error
- Comparativas entre modelos
- Análisis segmentado por ciudad y temporada

**Capturas del dashboard**

KPIs generales y predicción
<img width="1351" height="756" alt="image" src="https://github.com/user-attachments/assets/006bdc07-9968-47e7-a837-98a4aebd934e" />

Evolución de errores y segmentación
<img width="1348" height="748" alt="image" src="https://github.com/user-attachments/assets/e91c5402-f3dd-40b5-8ad1-df04a868b475" />


Comparativa entre modelos

<img width="1348" height="748" alt="image" src="https://github.com/user-attachments/assets/52454f42-543e-4e97-8d41-9ff59fc43cd5" />



## 🛠️ Tecnologías utilizadas
**Lenguajes y librerías**

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

**Visualización**

Tableau
Entorno
Jupyter Notebook
Anaconda



## 💼 Skills demostradas
**Data Analytics**

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- KPI Analysis
- Business Intelligence

**Machine Learning**

- Model Evaluation
- Regression Models
- Error Analysis
- Predictive Analytics

**Revenue Management**

- Dynamic Pricing
- ADR / RevPAR Analysis
- Occupancy Optimization
- Demand Analysis

**Data Visualization**

- Executive Dashboards
- Tableau Reporting
- Business Storytelling



## 🚀 Roadmap / Próximos pasos
- Automatización de ingesta de datos
- Integración de benchmarking competitivo
- Desarrollo de forecast a 30 días
- Implementación de elasticidad precio-demanda
- API de recomendaciones
- Simulación de escenarios y alertas operativas



## 📁 Estructura del proyecto

DyPriZa/

│
├── notebooks/

├── src/

├── data/

├── dashboards/

├── assets/

└── README.md



## 📂 Dataset

La carpeta de datos no se comparte públicamente debido a restricciones de confidencialidad.

El proyecto se ha desarrollado utilizando datasets públicos y datos reales del sector hospitality.




## ⚠️ Licencia

Proyecto desarrollado con fines educativos y de portfolio.

No se permite la reutilización o distribución del código sin autorización.
