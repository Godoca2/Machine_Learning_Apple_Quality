# Predicción de la Calidad de Manzanas 🍎

Este proyecto aplica técnicas de Machine Learning para predecir la calidad de manzanas, utilizando diferentes algoritmos supervisados y no supervisados. A través de un flujo de trabajo estructurado que abarca desde la exploración de datos hasta la selección de modelos, el análisis proporciona una metodología integral para problemas de clasificación en el ámbito agroindustrial.

## Descripción del Proyecto

El objetivo de este laboratorio es investigar y aplicar un enfoque de Machine Learning para clasificar la calidad de manzanas en dos categorías: **Buena** y **Mala**. El dataset proviene de [UCI Repository/Kaggle] y contiene variables independientes relacionadas con las características físicas y químicas de las manzanas.

## Etapas del Análisis

1. **Exploración de Datos**: Inspección inicial de las características del dataset, identificación de valores faltantes y análisis de la distribución de variables.
2. **Ingeniería de Características**: Imputación de valores nulos, transformación de datos y codificación de variables categóricas.
3. **Análisis Exploratorio de Datos (EDA)**: Estadísticas descriptivas y visualización de distribuciones de variables.
4. **Modelos de Aprendizaje No Supervisado**: Uso de **KMeans** y **PCA** para analizar la estructura de los datos sin una variable objetivo.
5. **Modelos de Aprendizaje Supervisado**: Implementación de algoritmos como **Regresión Logística**, **Árboles de Decisión** y **XGBoost** para la clasificación de la calidad.
6. **Comparación de Modelos**: Evaluación de los modelos usando métricas como precisión, recall, matriz de confusión y AUC-ROC.
7. **Uso de DataRobot**: Automatización de procesos de machine learning, incluyendo selección de características y optimización de hiperparámetros.

## Resultados y Conclusiones

- **Modelos Superiores**: **XGBoost** demostró ser el modelo con mejor rendimiento en términos de precisión y recall.
- **Insights Clave**: La calidad de la predicción depende en gran medida de un preprocesamiento adecuado y una selección cuidadosa de características.
- 
- **Automatización con DataRobot**: DataRobot ayudó a optimizar el flujo de trabajo, mejorando la eficiencia y reduciendo la intervención manual.

## Requisitos

- Python 3.x
- Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn
- DataRobot (opcional)

