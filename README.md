# Árboles de Regresión con Scikit-learn

Este proyecto implementa un modelo de árbol de regresión para predecir el valor de viviendas en California, utilizando el conjunto de datos `cal_housing`.

## Objetivo

Entrenar y evaluar un modelo de árbol de regresión para estimar precios de vivienda, y analizar la importancia de cada variable predictora.

## Tecnologías utilizadas

- Python 3
- Bibliotecas:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn
- Jupyter Notebook

## Dataset

- Nombre: California Housing
- Fuente: archivo `cal_housing.data`
- Variables:
  - Longitude, Latitude, Age, Rooms, Bedrooms, Population, Households, Income, Value

## Proceso de desarrollo

1. Carga y exploración del dataset.
2. Limpieza y separación en variables predictoras (X) y objetivo (y).
3. División en conjuntos de entrenamiento y prueba.
4. Entrenamiento de un árbol de regresión (`DecisionTreeRegressor`).
5. Evaluación del modelo con MSE y Score R².
6. Visualización de la importancia de las características.

## Resultados esperados

- Obtener una predicción aproximada del valor de las viviendas.
- Evaluar el desempeño del modelo con métricas como el Error Cuadrático Medio (MSE).
- Identificar qué variables tienen mayor impacto en la predicción.
