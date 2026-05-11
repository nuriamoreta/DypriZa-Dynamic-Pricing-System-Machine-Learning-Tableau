# DyPriZa — Informe de Proyecto

---

## 📑 Índice

1. Resumen ejecutivo  
2. Objetivos del proyecto  
3. Alcance y restricciones  
4. Fuentes de datos  
5. Metodología  
   - Ingesta y almacenamiento  
   - Limpieza y QA  
   - Ingeniería de features  
   - Modelado y evaluación  
   - Pipeline de producción  
6. Resultados clave  
7. Dashboard & Visualización  
8. Conclusiones y recomendaciones  
9. Roadmap y siguientes pasos  
10. Riesgos y consideraciones legales / de privacidad  
11. Anexos  

---

## 1. Resumen ejecutivo

Se ha desarrollado un producto mínimo viable (MPV). El proyecto definitivo contempla un modelo sólido y robusto, orientado a maximizar los ingresos mediante la proyección de escenarios y la recomendación de precios.

DyPriZa es una prueba de concepto orientada a ayudar a gestores y propietarios de alojamientos vacacionales a maximizar ingresos (ADR y RevPAR) y reducir vacantes.

El proyecto integra datos de Airbnb, Booking y AirDNA para cuatro ciudades españolas (Madrid, Barcelona, Sevilla y Valencia).

---

### Estado de esta fase

- Dashboard ejecutivo en Tableau con KPIs (ADR, ocupación, RevPAR)  
- Análisis exploratorio y preparación de datos  
- Modelado y automatización pendientes  

---

## 2. Objetivos del proyecto

### Objetivo general
Diseñar una solución reproducible de dynamic pricing para optimizar precios diarios de alojamientos turísticos.

### Objetivos específicos
- Integración y normalización de datos  
- Ingeniería de variables (temporales, propiedad, externas)  
- Modelado predictivo y validación  
- Reglas de negocio para pricing  
- Visualización en Tableau  
- API básica (futuro)  

---

## 3. Alcance y restricciones

### Incluye
- Datos históricos de reservas  
- KPIs de mercado  
- Dashboard en Tableau  
- Limpieza y control de calidad  

### Excluye
- Integración con PMS en tiempo real  
- Automatización completa de pricing  
- Web scraping avanzado (fase futura)  

---

## 4. Fuentes de datos

- AirDNA  
- Kaggle datasets  
- INE (España)  
- OpenWeather API  
- AllTheRooms  
- PriceLabs  

---

## 5. Metodología

### 1. Ingesta y almacenamiento
Unificación de datos en estructura común.

### 2. Limpieza y QA
- Eliminación de duplicados  
- Tratamiento de outliers  
- Validación temporal  

### 3. Ingeniería de variables
- Variables temporales  
- Variables de propiedad  
- Variables externas  

### 4. Modelado
- Modelo base: regresión lineal  
- Modelos avanzados: boosting  
- Métricas: MAE, RMSE, MAPE  

### 5. Pipeline
- Reglas de negocio  
- Predicción de ADR  
- Simulación de escenarios  

---

## 6. Resultados clave

- MAE ≈ 2.3  
- RMSE ≈ 2.9  
- Alta precisión Within5% (~95%)  
- Modelo estable en baseline lineal  

---

## 7. Dashboard & Visualización

Visualizaciones en Tableau:

- ADR por ciudad  
- Ocupación por temporada  
- RevPAR  
- Comparación real vs predicho  
- Distribución de residuales  

---

## 8. Conclusiones

- Modelo baseline sólido  
- Mayor error en temporada alta (Barcelona)  
- Potencial alto de mejora con elasticidad y reglas dinámicas  

---

## 9. Roadmap

- Elasticidad precio-demanda  
- API de predicción  
- Web scraping de competencia  
- Expansión a cobertura anual  
- Piloto A/B testing  

---

## 10. Riesgos y privacidad

- Cumplimiento GDPR  
- Minimización de datos  
- Pseudonimización  
- Seguridad y cifrado  
- Auditoría de modelos  

---

## 11. Anexos

### KPI
- ADR = Revenue / Noches vendidas  
- RevPAR = Revenue / Unidades disponibles  
- Ocupación = Noches ocupadas / disponibles  

### Entorno
- Python 3.11  
- Scikit-learn, Pandas, XGBoost  

---
