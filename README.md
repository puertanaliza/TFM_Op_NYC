## 🚦 Clasificación del tráfico urbano en Manhattan mediante Big Data y Deep Learning en Databricks
📌 Descripción del proyecto
Este repositorio contiene el Trabajo de Fin de Máster (TFM) del Máster Universitario en Big Data & Visual Analytics, evaluado con una calificación de 9/10.

El objetivo principal es el desarrollo de un modelo de clasificación del tráfico urbano (por niveles de congestión) utilizando datos reales de movilidad en Manhattan, integrando técnicas de procesamiento masivo de datos, ingeniería de características y modelos de Deep Learning, todo ello desplegado en un entorno Databricks sobre Spark.

🧠 Tecnologías utilizadas
Python (Pandas, NumPy, Scikit-learn, PyTorch, NewtWorkX, Seaborn, Matplotlib)

Databricks (PySpark)

🔍 Enfoque metodológico
Ingesta y limpieza de datos

Datos de movilidad urbana (Uber and Taxi Movement (Taxi $ Limosine Comission) + otras fuentes públicas de NYC)

Tratamiento de valores nulos, gestión de valores atípicos, integración de datos 

Feature engineering

Extracción de variables relacionadas con congestión, espacio-tiempo, eventos y clima

Agregaciones y transformaciones para obtener granularidad útil

Modelado de clasificación

Modelos entrenados: Random Forest, Redes Neuronales (PyTorch)

Evaluación con métricas de clasificación: Precision, Recall, F1-score, Accuracy

Automatización y trazabilidad

Comparativa entre modelos y elección del óptimo

📈 Resultados destacados
Clasificación del tráfico en distintos niveles con precisión (F1 > 0.75)

Identificación de variables clave en la congestión urbana

Validación cruzada y robustez del modelo en distintos horarios y zonas de Manhattan

