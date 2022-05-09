# ununsupervised-classifier-of-news-stories

### Limpieza de datos

Se desarrollo una funcion para preprocesar el texto del contenido de la notas periodisticas y el titulo, se removió: texto html, puntuaciones, numeros, emojies, stopwords, ascents y frase "icon", asimismo se puso en minuscula y se hizo la lematizacion.

### K means clustering 
TFID Vectorizer: para crear una matriz dispersa de palabras ponderadas según su importancia en el conjunto de datos.
Análisis Semántico Latente (LSA): método de reducción de matriz
“Elbow Curve”: para encontrar el número de "k".
Algoritmo k-means: aplicado finalmente con la matriz optimizada y el numero de clusteres.
