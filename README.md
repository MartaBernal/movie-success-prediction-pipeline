
End-to-end data pipeline and machine learning model to predict movie success, including ETL, API development and AWS deployment

**PROBLEMA DE NEGOCIO**

Las productoras invierten grandes presupuestos sin una estimación clara del éxito comercial de una película.
Esto implica alto riesgo financiero y decisiones poco optimizadas.

**OBJETIVO**

Desarrollar una solución de datos end-to-end que permita:

Predecir el éxito de una película 
Analizar tendencias del mercado 
Facilitar la toma de decisiones basada en datos 

**ARQUITECTURA**

Pipeline completo de datos:

1. **Extracción**
- API de TMDB
- Ingesta automatizada
  
2. **Transformación**
- Limpieza de datos
- Feature engineering
  
3. **Carga**
- Base de datos PostgreSQL

4. **Machine Learning**
- Modelo de clasificación

5. **API**
- FastAPI con endpoints:
  - /predict
  - /ask-text
  - /ask-visual

6. **Despliegue**
- AWS (S3, Lambda, RDS, EC2)
