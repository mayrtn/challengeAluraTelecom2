# challengeAluraTelecom2Challenge Telecom X – Parte 2: Predicción de Evasión de Clientes (Churn)
Descripción

En este proyecto se construyen modelos predictivos para anticipar la evasión de clientes (Churn) de una empresa de telecomunicaciones, utilizando el dataset previamente tratado en el Challenge 1.

Objetivo

Identificar clientes con mayor riesgo de evasión y las variables más influyentes para ayudar a la empresa a implementar estrategias de retención personalizadas.

Contenido del Notebook

El notebook está organizado en bloques:

Preparación de Datos: carga, limpieza, aplanado de columnas tipo dict, codificación de variables y manejo de valores faltantes.

Selección de Features y Preparación: eliminación de columnas irrelevantes, one-hot encoding y revisión de proporción de clases.

Train/Test y Escalado: división de datos, escalado de variables numéricas y aseguramiento de datos completos.

Modelado Predictivo: entrenamiento de Logistic Regression y Random Forest, con imputación de valores faltantes.

Evaluación de Modelos: métricas de desempeño, matriz de confusión y ROC-AUC.

Importancia de Variables: análisis de variables más influyentes según Random Forest.

Conclusiones y Recomendaciones: perfil de clientes con mayor riesgo, variables clave y acciones estratégicas sugeridas.

Herramientas utilizadas

Python 3

Pandas

Scikit-learn

Matplotlib

Seaborn

Resultado

Se construyeron modelos capaces de predecir la evasión de clientes y se identificaron las variables más importantes para retención: tenure, tipo de contrato, servicios adicionales y facturación mensual. Las recomendaciones permiten implementar estrategias enfocadas en los clientes con mayor riesgo de Churn.
