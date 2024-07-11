# Vino
Predecir el precio de la botella y su calidad a partir de los datos del vino

### Proyecto de Predicción de Precios y Calificaciones de Vino
Este proyecto tiene como objetivo predecir el precio y la calificación de una botella de vino utilizando diferentes técnicas de Machine Learning. A continuación se describen los pasos realizados desde la preparación de los datos hasta la construcción y evaluación de los modelos.

1. Preparación de Datos
1.1. Carga de Datos
El conjunto de datos original fue cargado desde el archivo DatosVino(in).csv.

1.2. Limpieza y Transformación de Datos
Se realizaron las siguientes acciones para limpiar y preparar los datos:

Imputación de valores faltantes: Se completaron los valores faltantes utilizando técnicas adecuadas (media, mediana, moda, etc.).
Conversión de variables categóricas a numéricas: Las variables categóricas se transformaron en variables numéricas mediante técnicas como one-hot encoding o label encoding.
Tratamiento de anomalías: Se identificaron y trataron los valores atípicos o anomalías en los datos.
Normalización y estandarización: Las características numéricas se normalizaron / estandarizaron.
1.3. Caracterización de Datos
Se exploraron y visualizaron las características del conjunto de datos para entender mejor la distribución y relaciones entre variables.

2. Modelado
Se construyeron y evaluaron diferentes modelos para dos objetivos principales:

Predicción del precio del vino
Predicción de la calificación del vino
2.1. Predicción del Precio del Vino
Modelos Utilizados
Regresión Lineal
Árboles de Decisión
Random Forest
Gradient Boosting
Evaluación de Modelos
Se utilizaron métricas como el RMSE (Root Mean Squared Error) y el R² para evaluar el desempeño de los modelos.

2.2. Predicción de la Calificación del Vino
Modelos Utilizados
Clasificación Logística
K-Nearest Neighbors
Support Vector Machine
Random Forest
Evaluación de Modelos
Se emplearon métricas como la exactitud, precisión, recall y F1-score para evaluar el desempeño de los modelos de clasificación.

3. Resultados
3.1. Mejor Modelo para Predicción de Precios
El modelo que mejor se desempeñó para la predicción de precios fue [nombre del modelo], con un RMSE de [valor] y un R² de [valor].

3.2. Mejor Modelo para Predicción de Calificaciones
El modelo que mejor se desempeñó para la predicción de calificaciones fue [nombre del modelo], con una exactitud de [valor] y un F1-score de [valor].

4. Conclusiones
Resumen de los hallazgos: Resumen breve de los hallazgos más importantes.
Mejoras futuras: Sugerencias para posibles mejoras en el análisis y modelado.
Aplicaciones prácticas: Cómo pueden ser utilizados estos modelos en el mundo real.
5. Requisitos
Python 3.x
Bibliotecas: pandas, numpy, scikit-learn, matplotlib, seaborn
6. Instrucciones para Reproducción
Clonar el repositorio
Instalar las bibliotecas necesarias
Ejecutar el script de preparación de datos
Ejecutar los notebooks de modelado y evaluación