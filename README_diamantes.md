# Proyecto de Predicción de Precios de Diamantes

Este proyecto tiene como objetivo predecir los precios de diamantes utilizando un modelo de aprendizaje automático previamente entrenado. El proceso se divide en dos partes principales: preprocesamiento de datos de prueba (Test) y predicción de precios.

1. **Parte 1: Preprocesamiento de Datos de Prueba** 

En primer lugar, hay que importar las librerias necesarias para la realización del proyecto.

**Conexión y Extracción de Datos**

**Carga del Dataset**: El dataset de prueba se carga desde un archivo CSV utilizando pandas.

**Eliminación de la columna 'id'**: Se elimina la columna id ya que no es necesaria para el modelo.

**Codificación One-Hot**: Las columnas categóricas (cut, color, clarity, city) se convierten a variables dummy utilizando One-Hot Encoding.

**Escalado de Datos**: Los datos se escalan utilizando MinMaxScaler para normalizarlos.

**Entrenamiento del Modelo**: Se utiliza RandomForestRegressor para entrenar el modelo con los datos preprocesados.


2. **Parte 2: Predicción de Precios

**Carga del Modelo**: El modelo entrenado se carga desde un archivo utilizando pickle.

**Predicción**: El modelo se utiliza para predecir los precios de los diamantes basándose en los datos preprocesados.

**Guardar Predicciones**: Las predicciones se guardan en un archivo CSV que luego se analiza**


3. **Archivos**

preprocessing.py: Script para preprocesar los datos y entrenar el modelo.
prediction.py: Script para predecir los precios de los diamantes.
diamonds.csv: Dataset completo de entrenamiento.
diamonds_test.csv: Dataset de prueba.
test_1.sav: Modelo entrenado guardado.
intento_2.csv: Archivo CSV con las predicciones finales.

4. **Requisitos**

Bibliotecas: 
pandas, 
numpy, 
scikit-learn, 
pickle

# Conclusiones

Un proyecto muy interesante para aprender y predecir datos, en este caso, el precio del diamante. 


