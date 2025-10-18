Objetivo

El objetivo de este examen es que cada estudiante desarrolle un flujo completo del proceso de Machine Learning utilizando un dataset de 1500 tweets en español provenientes de Ecuador. Cada registro contiene texto, metadatos y una columna adicional de toxicidad (TOXICITY) que ha sido previamente calculada utilizando el API de Perspective.

El examen evalúa la capacidad para estructurar un pipeline de análisis de datos que incluya limpieza, codificación, clasificación, regresión y técnicas de clustering, con visualizaciones e interpretación de resultados.



Instrucciones Generales

1. Análisis Exploratorio de Datos (EDA):

	•	Analizar el dataset entregado con foco en:

		•	Tipo y cantidad de variables (numéricas, categóricas, texto).

		•	Estadísticas descriptivas (mínimos, máximos, media, mediana, distribución).

		•	Distribución de la variable TOXICITY.

		•	Detección de valores nulos, duplicados o atípicos.

	•	Incluir visualizaciones apropiadas al tipo de dato, por ejemplo:

		•	Histogramas o boxplots para variables numéricas.

		•	Gráficos de barras o conteo para variables categóricas.

		•	Nubes de palabras o frecuencias para texto.

		•	Gráficos de dispersión si aplica.

	•	Explicar de forma clara al menos 3 hallazgos clave del análisis.



2.	Preprocesamiento y codificación:

	•	Limpieza del texto y metadatos.

	•	Aplicación de técnicas como:

		•	Codificación de texto (TF-IDF, CountVectorizer, u otros).

		•	Codificación de variables categóricas (OneHotEncoder, OrdinalEncoder).

		•	Escalamiento de variables numéricas (MinMaxScaler, StandardScaler).

	•	Uso de ColumnTransformer y Pipeline para un flujo estructurado.



3. Clasificación:

	•	Transformar el valor de TOXICITY en una variable categórica binaria o multiclase, utilizando un umbral de corte o una estrategia de discretización, debidamente justificada.

	•	Seleccionar y aplicar al menos un algoritmo de clasificación supervisada.

	•	Evaluar el rendimiento del modelo utilizando métricas apropiadas (por ejemplo: Accuracy, Precision, Recall, F1-Score, ROC-AUC).

	•	Presentar los resultados mediante visualizaciones relevantes (matriz de confusión, curva ROC, etc.).



4. Regresión:

	•	Utilizar el valor continuo de TOXICITY como variable objetivo para un problema de regresión.

	•	Seleccionar y aplicar al menos un algoritmo de regresión supervisada.

	•	Evaluar el rendimiento del modelo utilizando métricas adecuadas (por ejemplo: MAE, RMSE, R²).

	•	Visualizar los resultados con gráficos interpretables (dispersión real vs predicho, errores residuales, etc.).



5. Clustering:

	•	Aplicar al menos un algoritmo de clustering (por ejemplo: K-Means, Agglomerative Clustering).

	•	Visualizar los clusters obtenidos

	•	Reflexionar sobre las diferencias o similitudes entre los clusters y las clases definidas en el target de clasificación.



6.	Conclusiones:

	•	Reflexionar sobre la calidad de los datos, la utilidad del target generado, el rendimiento de los modelos y los patrones encontrados.

	•	Proponer mejoras o pasos futuros.



Entrega (hasta las 14h00)

Cada estudiante deberá entregar su trabajo como un documento Quarto publicado en GitHub Pages. El documento debe estar completo, correctamente estructurado y contener código, visualizaciones, explicaciones y reflexiones según los apartados solicitados.



Criterios de Evaluación

	1.	Análisis Exploratorio de Datos (EDA) (15%)

	2.	Preprocesamiento y codificación (15%)

	3.	Clasificación (20%)

	4.	Regresión (20%)

	5.	Clustering (20%)

	6.	Conclusiones (5%)

	7.	Presentación del documento (Quarto + GitHub Pages) (5%)