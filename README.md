📱 Proyecto – Clasificación de Planes Móviles en Megaline

Objetivo del proyecto:
Construir un modelo de machine learning que prediga el plan óptimo (Smart o Ultra) para los clientes de Megaline, en función de su comportamiento mensual (llamadas, mensajes y uso de datos). El objetivo era alcanzar una exactitud ≥ 0.75 para recomendar el plan correcto.

Procedimientos:

Exploración inicial y carga de los datos de comportamiento de los usuarios.
Segmentación del dataset en entrenamiento, validación y prueba.
Entrenamiento de distintos modelos de clasificación, incluyendo árboles de decisión, Random Forest y regresión logística, ajustando hiperparámetros para optimizar resultados.
Comparación de modelos con base en la métrica de exactitud (accuracy).
Realización de una prueba de cordura para verificar la estabilidad del modelo en datos más complejos.

Conclusiones:

El mejor modelo logró superar el umbral de 0.75 de exactitud, cumpliendo con los criterios establecidos.
Se demostró que el comportamiento de los clientes (uso de datos, llamadas y mensajes) es un predictor confiable para recomendar planes.
El proyecto se implementó con Python, pandas, scikit-learn, matplotlib y seaborn.
