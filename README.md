# TitanicClassification

## Solución propuesta
El proyecto se centró en abordar el desafío de determinar si una persona a bordo del Titanic sobrevivió o no, utilizando un conjunto de datos descargado de Kaggle [Titanic Dataset](https://www.kaggle.com/competitions/titanic). Los pasos principales fueron los siguientes:

### 1) Exploración y preprocesamiento de datos:

* Se verificó el equilibrio de las clases y se analizó la distribución de datos categóricos en relación con la clase "survived" para identificar características relevantes.
* Se identificaron y visualizaron los datos faltantes. Se determinaron las características que requerían imputaciones y se aplicaron técnicas de imputación.
* Se realizó un análisis de correlación para decidir qué características debían mantenerse y cuáles descartarse.
* Se transformaron los datos categóricos en numéricos utilizando encoders 
* Se aplicó estandarización para mejorar el rendimiento del modelo.

### 2) Clasificación:

* Se seleccionaron 4 algoritmos de clasificación: RandomForest, Logistic regression, knn, y Gaussian Naive Bayes, justificando la elección de cada uno.
* Se utilizó k-cross validation para la clasificación, seleccionando el valor de "k" y justificando la elección.
* Se calcularon métricas de evaluación para evaluar el rendimiento de los modelos.
* Con base en estas métricas, se determinó que el modelo knn era el mejor clasificador.


## Dificultades

## Links
* Colab: <https://drive.google.com/file/d/14RQj_DcD2TvGeH9jWBl0395bwrEk5mCl/view?usp=share_link>
* Carpeta a Drive: <https://drive.google.com/drive/folders/1WrkYZCzqcsVjTeQZKk7aRx4-BrmwKnH6?usp=share_link>
