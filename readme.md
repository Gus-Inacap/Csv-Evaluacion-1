# Proyecto de Machine Learning - Evaluación 1

Este proyecto contiene la solución a varios problemas relacionados con el uso de algoritmos de aprendizaje automático para resolver diversas tareas, desde la predicción de precios de casas hasta la clasificación de correos electrónicos, recomendación de productos, detección de fraudes y clasificación con perceptrón.

## Tabla de Contenidos
- [Problema 1: Predicción de Precios de Casas](#problema-1-predicción-de-precios-de-casas)
- [Problema 2: Clasificación de Correos Spam](#problema-2-clasificación-de-correos-spam)
- [Problema 3: Recomendación de Películas](#problema-3-recomendación-de-películas)
- [Problema 4: Detección de Fraudes en Transacciones Bancarias](#problema-4-detección-de-fraudes-en-transacciones-bancarias)
- [Problema Extra: Clasificación con Perceptrón](#problema-extra-clasificación-con-perceptrón)
- [Instrucciones de Instalación](#instrucciones-de-instalación)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Problema 1: Predicción de Precios de Casas

**Descripción**: Utilizamos un modelo de regresión para predecir el precio de una casa en California en función de sus características.

- **Dataset**: [California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- **Preguntas**:
  - ¿Qué características influyen más en el valor de una casa?
  - ¿Cuál es la precisión del modelo?
- **Métricas de Evaluación**:
  - Error Absoluto Medio (MAE)
  - Error Cuadrático Medio (MSE)
  - Raíz del Error Cuadrático Medio (RMSE)
  - R²

### Resultados

El análisis de las características y las métricas del modelo se encuentran en el archivo `pregunta1.ipynb`.

## Problema 2: Clasificación de Correos Spam

**Descripción**: Clasificamos correos electrónicos en spam o no spam basándonos en su contenido utilizando modelos de clasificación.

- **Dataset**: [Spambase Data Set](https://archive.ics.uci.edu/dataset/94/spambase)
- **Preguntas**:
  - ¿Qué características afectan más a que un correo sea clasificado como spam?
  - Justificación del modelo utilizado.
- **Métricas de Evaluación**:
  - Tasa de Error
  - Exactitud
  - Matriz de Confusión
  - Tasa de Verdaderos Positivos
  - Tasa de Falsos Positivos
  - Precisión
  - F1-Score

### Resultados

La clasificación y las métricas se encuentran detalladas en el archivo `pregunta2.ipynb`.

## Problema 3: Recomendación de Películas

**Descripción**: Utilizamos técnicas de filtrado colaborativo para recomendar películas a usuarios en función de las similitudes con otros usuarios o productos.

- **Dataset**: [MovieLens 20M Dataset](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?select=movie.csv)
- **Preguntas**:
  - ¿Qué película recomendarían si se quiere ver una película de terror?
  - ¿Qué película recomendarían si la última película fue Toy Story?

### Resultados

Las recomendaciones de películas se encuentran en el archivo `pregunta3.ipynb`.

## Problema 4: Detección de Fraudes en Transacciones Bancarias

**Descripción**: Implementamos una máquina de soporte vectorial (SVM) para detectar transacciones fraudulentas.

- **Dataset**: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Preguntas**:
  - ¿Qué kernel sería más adecuado para abordar este problema?
  - Comparar las métricas de Precisión, F1-Score, Recall y Exactitud.
  
### Resultados

El modelo de SVM y las métricas comparativas están en el archivo `pregunta4.ipynb`.

## Problema Extra: Clasificación con Perceptrón

**Descripción**: Clasificación de dos tipos de flores usando un perceptrón simple con el dataset Iris de Scikit-learn, simplificado para dos clases y dos características.

- **Dataset**: Iris Dataset (incluido en `scikit-learn`)

### Resultados

Los resultados del perceptrón se encuentran en el archivo `perceptron.ipynb`.

## Instrucciones de Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/nombre-repositorio.git
