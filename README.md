# TitanicClassification

## Solución propuesta
El proyecto se centró en abordar el desafío de determinar si una persona a bordo del Titanic sobrevivió o no, utilizando un conjunto de datos descargado de Kaggle [Titanic Dataset](https://www.kaggle.com/competitions/titanic). Los pasos principales fueron los siguientes:

### a) Exploración y preprocesamiento de datos:

* Se verificó el equilibrio de las clases y se analizó la distribución de datos categóricos en relación con la clase "survived" para identificar características relevantes.
* Se identificaron y visualizaron los datos faltantes. Se determinaron las características que requerían imputaciones y se aplicaron técnicas de imputación.
* Se realizó un análisis de correlación para decidir qué características debían mantenerse y cuáles descartarse.
* Se transformaron los datos categóricos en numéricos utilizando encoders 
* Se aplicó estandarización para mejorar el rendimiento del modelo.

### b) Clasificación:

* Se seleccionaron 4 algoritmos de clasificación: RandomForest, Logistic regression, knn, y Gaussian Naive Bayes, justificando la elección de cada uno.
* Se utilizó k-cross validation para la clasificación, seleccionando el valor de "k" y justificando la elección.
* Se calcularon métricas de evaluación para evaluar el rendimiento de los modelos.
* Con base en estas métricas, se determinó que el modelo knn era el mejor clasificador.


## Problemas y soluciones

A lo largo del presente proyecto, nos enfrentamos a diversos desafíos que requerían soluciones creativas y técnicas. En esta sección, detallamos los problemas que surgieron durante el proceso y cómo los abordamos de manera efectiva:

1. Datos Faltantes\
**_Problema_**: Al explorar el conjunto de datos del Titanic, identificamos la presencia de datos faltantes en varias características. Decidir qué características requerían imputaciones y cómo hacerlo fue un reto.\
**_Solución_**: Realizamos un análisis detallado de las características con datos faltantes y decidimos qué técnicas de imputación eran más apropiadas para cada caso (la media, la moda), según la naturaleza de la característica. Además, eliminamos columnas que tenían una cantidad significativa de datos faltantes y justificamos nuestras decisiones.

2. Selección de Características Relevantes\
**_Problema_**: Determinar qué características eran realmente relevantes para predecir la supervivencia en el Titanic. Queríamos evitar incluir características irrelevantes que pudieran afectar negativamente el rendimiento del modelo.\
**_Solución_**: Realizamos un análisis de correlación y evaluamos la importancia de las características. Esto nos permitió seleccionar un conjunto de características más significativas para la clasificación.

3. Evaluación de Modelos\
**_Problema_**: Evaluar y comparar el rendimiento de diferentes modelos de clasificación fue complicado debido a la variedad de métricas disponibles y la interpretación de sus resultados.\
**_Solución_**: Nos apoyamos de métricas de evaluación específicas para cada modelo (precisión, matriz de confusión, curva ROC y AUC). 

4. Gestión de Versiones y Colaboración\
**_Problema_**: Trabajar en colaborativamente en el Colab fue una situación delicada, puesto que trabajar simultáneamente no era una opción.\
**_Solución_**: Cada individuo tenía una copia del código en su Drive personal, de esta manera, disponíamos la libertad de poder contribuir sin ningún riesgo. En caso de generar un avance en la solución del reto, se comunicaba con el equipo y se compartía en el Colab grupal (código final).

## Links
* Colab: <https://drive.google.com/file/d/14RQj_DcD2TvGeH9jWBl0395bwrEk5mCl/view?usp=share_link>
* Carpeta a Drive: <https://drive.google.com/drive/folders/1WrkYZCzqcsVjTeQZKk7aRx4-BrmwKnH6?usp=share_link>
