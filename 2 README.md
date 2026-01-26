# Optimización de Hiperparámetros con SVM

Este repositorio contiene el desarrollo completo de un ejercicio de clasificación
utilizando Support Vector Machine (SVM), donde se aplican técnicas de optimización
de hiperparámetros mediante GridSearch y RandomizedSearch

## Contenido del repositorio
- Optimizacion_Hiperparametros.ipynb  
  Cuaderno de Google Colab con todo el proceso: carga de datos, preprocesamiento,
  selección del modelo, optimización de hiperparámetros, entrenamiento final y
  guardado del modelo.

- svm_country_income_model.pkl  
  Modelo SVM entrenado con los mejores hiperparámetros obtenidos.

- LICENSE  
  Licencia MIT del proyecto.

## Datos utilizados

Se utilizó el conjunto de datos Country-data.csv, que contiene información
socioeconómica y demográfica de distintos países.

La variable objetivo fue creada a partir de la variable "income", clasificando
los países en tres categorías: ingreso bajo, medio y alto.

## Metodología

1. Exploración y análisis de los datos.
2. Escalado de variables con StandardScaler.
3. Selección del modelo SVM.
4. Optimización de hiperparámetros con GridSearchCV.
5. Optimización de hiperparámetros con RandomizedSearchCV.
6. Reentrenamiento del modelo con los mejores parámetros.
7. Guardado del modelo entrenado.

## Resultados

El mejor modelo obtenido corresponde a un SVM con kernel lineal, logrando una
precisión promedio cercana al 92.79% en validación cruzada.

## Licencia

Este proyecto se distribuye bajo la licencia MIT.
