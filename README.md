# 🍷 Wine Quality Prediction: Modelado de Regresión Multivariante
### Comparativa de Algoritmos: Random Forest, XGBoost, KNN y Árboles de Decisión

Este proyecto tiene como objetivo predecir la calidad percibida del vino (escala 0-10) a partir de sus propiedades fisicoquímicas. Se implementa un flujo completo de Machine Learning, desde la exploración y limpieza hasta la optimización avanzada de hiperparámetros, identificando los factores químicos que más influyen en la excelencia del producto.

---

## 🛡️ Visión de Gobierno de Datos y Model Governance
Como especialista en **Data Governance**, este proyecto de regresión no solo busca precisión, sino solidez y explicabilidad en el proceso de decisión:

1. **Gobernanza del Modelo (Model Selection):** Evaluación sistemática de cuatro familias de algoritmos bajo métricas de RMSE y R². La selección de **Random Forest** como modelo final responde a un proceso de auditoría técnica que garantiza la mejor generalización frente a datos no vistos.
2. **Integridad de Variables Químicas:** Validación de la consistencia de los atributos (alcohol, acidez, pH, etc.). Se asegura que el tratamiento de valores extremos no distorsione la realidad química del producto, manteniendo el linaje del dato desde el archivo de origen `vinos.csv`.
3. **Explicabilidad (Feature Importance):** Identificación de las variables críticas para el negocio. La gobernanza aquí asegura que los "drivers" de calidad identificados por el modelo sean consistentes con el conocimiento de dominio enológico.
4. **Visión Ética (Human-in-the-loop):** El modelo está diseñado como una herramienta de apoyo al control de calidad, no como reemplazo de los catadores expertos, promoviendo un uso responsable y complementario de la Inteligencia Artificial.

---

## 🎯 Capacidades Técnicas
- **Comparativa Multimodelo:** Implementación y evaluación de Árboles de Decisión, KNN, Random Forest y XGBoost.
- **Optimización de Hiperparámetros:** Uso de **Grid Search** y validación cruzada para maximizar el rendimiento de los algoritmos.
- **Análisis de Importancia:** Extracción de las características fisicoquímicas con mayor impacto predictivo.
- **Evaluación Rigurosa:** Uso de métricas de error cuadrático (RMSE) y coeficiente de determinación (R²) para garantizar la precisión del pronóstico.

---

## 📊 Fuente de los Datos
- **Archivo de datos:** `vinos.csv` (o el formato correspondiente que contenga el dataset).
- **Contenido:** Atributos fisicoquímicos de muestras de vino y su respectiva calificación de calidad por expertos.

---

## 🛠️ Stack Tecnológico
- **Lenguaje:** Python 3.10+
- **Machine Learning:** `Scikit-learn` (Random Forest, KNN, DecisionTree), `XGBoost`.
- **Optimización:** `GridSearchCV`.
- **Análisis de Datos:** `Pandas`, `Numpy`.
- **Visualización:** `Matplotlib`, `Seaborn`.

---

## 🚀 Cómo utilizar este proyecto
1. Clona el repositorio.
2. Asegúrate de que el archivo de datos `vinos.csv` esté en la carpeta raíz del proyecto.
3. Instala las dependencias:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn
4. Ejecuta el notebook wine_quality_prediction.ipynb para visualizar la comparativa de modelos y los resultados de la predicción.
