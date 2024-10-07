# Film_Union
## Machine Learning for Texts: IMDB Movie Review Classification Models


### Descripción del Proyecto
En este sprint, se implementaron y evaluaron múltiples modelos avanzados de clasificación de texto, incluyendo LightGBM, Random Forest y Logistic Regression. El objetivo principal fue optimizar el rendimiento del modelo en la clasificación de reseñas, utilizando técnicas de procesamiento de texto con spaCy y TF-IDF.

### Objetivo
Desarrollar y evaluar modelos de clasificación de texto avanzados para mejorar el rendimiento en la clasificación de reseñas, con un enfoque en la precisión y capacidad de generalización del modelo. Se buscó alcanzar un F1 Score superior a 0.85 en el conjunto de prueba.

### Etapas del Proyecto
  - Preparación de los Datos y EDA
  - Preprocesamiento de Datos: Normalización y limpieza de reseñas utilizando modelo de Spacy, stopwords de NLTK y vectorización con TF-IDF.
  - Entrenamiento y Prueba de Modelos: Entrenamiento de modelos individuales como LightGBM, Random Forest, y Logistic Regression.
  - Evaluación: Evaluación del rendimiento de los modelos utilizando métricas como Exactitud, F1 Score y ROC AUC.
  - Pruebas Manuales : Comparación entre los resultados de las pruebas manuales y las pruebas de evaluación anteriores.

### Herramientas Tecnológicas Implementadas
  - LightGBM: Para capturar relaciones complejas y no lineales.
  - Random Forest Classifier: Robusto a sobreajuste y eficaz con datos de muchas características.
  - Logistic Regression: Modelo simple y efectivo para relaciones lineales.
  - spaCy: Procesamiento de texto para normalización.
  - TF-IDF: Vectorización de texto.

### Conclusiones
Podemos indicar que las métricas de rendimiento son importantes, pero también es crucial evaluar cómo los modelos se comportan con ejemplos reales y manuales, de manera de obtener una visión completa de su capacidad de generalización y precisión.

Con respecto a los resultados de los dintintos modelos utlizados, podemos indicar que:
  - Regresión Logística: Aunque tuvo menor rendimiento en algunas métricas comparado con los otros dos modelos, mostró una buena capacidad de generalización y consistencia en las pruebas manuales.
  - Bosque Aleatorio: Aunque mostró excelentes métricas de rendimiento, su desempeño en las pruebas manuales reveló posibles problemas de sobreajuste y sensibilidad a palabras específicas.
  - LightGBM: Mostró un buen equilibrio entre rendimiento y generalización, con una alta consistencia en las pruebas manuales y métricas robustas en las evaluaciones.





