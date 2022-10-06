# Proyecto-Final-Ironhack


Para el proyecto final, la idea fue hacer un clasificador que a través de ciertas variables, nos dice si una persona tiene o no una enfermedad cardiovascular. 




La causa de muerte más común en el mundo es por algún tipo de enfermendad cardiovascular. Tan solo en el 2019, 18millones de personas fallecieron por algún problema relacionado al corazón. 

Todavía existen muchos casos donde los diagnosticos de los médicos son incorrectos. En Estados Unidos 12millones de personas reciben un diagnóstico equivocado por parte del médico. 


La pregunta para el proyecto fue: ¿Puede un clasificador predecir si una persona tiene una enfermedad cardiovascular?. Después de formular esa pregunta se siguieron los pasos para poder constestarla.


1.- Definir problema (la pregunta que hicimos)

2.- Conseguir datos (estos datos provienen de la clinica de Cleeveland)

3.- EDA de los datos (analisis exploratorio para entender las variables y sus relaciones entre si)

4.- Modelos de clasificación (Para este proyecto usamos el modelo de Regresión Logística, el KNeighbors y el random forest)

5.- Resultados (los resultados fueron medidos a través de las métricas de evalucación)

6.- Experimentación (Se pueden hacer diferentes experimentos como tunear los hiperparametros o el cross validation para ver si mejoran las métricas)

7.- Conclusiones ( hay muchas preguntas que nos podemos hacer para las conclusiones. ¿Que nos dicen las métricas?, ¿el modelo es lo suficientemente bueno para tema de salúd?, ¿como están los errores  del tipo 1 y del tipo 2?)






![descarga](https://user-images.githubusercontent.com/110119199/194411676-6dcf8ab8-ffb7-4eaa-a702-e862fd783dd1.png)




La otra pregunta es como medir el éxito? Esto llega a ser un poco más complejo ya que es un asunto delicado que trata sobre la salud de las personas. 
Para poder medir el éxito usamos diferentes métricas de evaluación como el accuracy, la precision, el reacall y el f1 score, basadas en la matriz de confusión.

![me](https://user-images.githubusercontent.com/110119199/194412192-e8d2b348-aea3-4bdf-839d-9fa387fbc796.jpeg)





En este repositorio se puede encontrar una carpeta llamada 'data' que es donde vienen los datos.
Los datos originales vienen de la clinica Cleveland pero fueron extraídos a través de la página de Machine Learning Repository

https://archive.ics.uci.edu/ml/datasets/heart+Disease



También se puede encontrar una carpeta llamada 'código' que es donde viene el jupiter notebook con el código del proyecto. 


