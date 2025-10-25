# Proyecto de Producción Agrícola con Machine Learning

Este proyecto fue desarrollado como parte de mi formación en un curso de **Data Science y Machine Learning**.  
El objetivo es analizar la relación entre **variables climáticas** y el **rendimiento agrícola** de diferentes cultivos en Europa, usando datos de **Meteostat** y **FAOSTAT**.

---

## 📂 Contenido del repositorio

- `Agricola.ipynb`  
  Notebook principal donde se realiza todo el flujo de trabajo:  
  - Obtención de datos de Meteostat (temperaturas y precipitaciones)  
  - Limpieza y normalización de los datos  
  - Merge con datos de rendimiento de FAOSTAT  
  - Entrenamiento y evaluación de modelos de Machine Learning (Random Forest)  
  - Validaciones con `TimeSeriesSplit` y `GroupKFold`  
  - Análisis de métricas, visualizaciones y explicación de modelos (SHAP)  

- `FAOSTAT_data_en_10-19-2025.csv`  
  Datos históricos de rendimiento agrícola por país y cultivo descargados de FAOSTAT.

---

## 🛠 Tecnologías y librerías

El proyecto está desarrollado en **Anaconda** utilizando **Jupyter Notebook**, y utiliza las siguientes librerías principales:

- `pandas`, `numpy` → manipulación y análisis de datos  
- `matplotlib`, `seaborn` → visualización de datos  
- `scikit-learn` → Machine Learning (Random Forest, validación cruzada, métricas)  
- `meteostat` → obtención de datos climáticos históricos  
- `shap` (opcional) → interpretabilidad del modelo  

Instalación de librerías (ejemplo):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn meteostat shap
