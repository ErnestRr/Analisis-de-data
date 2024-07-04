Neural Network
Fake news or Real news

Carga de Datos: El código carga un conjunto de datos de noticias desde un archivo CSV que contiene noticias etiquetadas como "FAKE" o "REAL".

Análisis Exploratorio de Datos (EDA): Realiza un análisis inicial de los datos, mostrando las primeras filas del conjunto de datos y visualizando la distribución de las etiquetas (noticias reales y falsas) en un gráfico de barras.

Preprocesamiento de Texto: Procesa el texto de las noticias mediante el uso de la función preprocess_text. Este paso es fundamental para limpiar y preparar el texto antes de la vectorización.

Word2Vec y Vectorización de Texto: Entrena un modelo Word2Vec en el texto preprocesado y utiliza este modelo para convertir las noticias en vectores numéricos. Cada noticia se representa como un vector numérico basado en la semántica de las palabras en el texto.

División de Datos y Creación del Modelo: Divide los datos en conjuntos de entrenamiento y prueba. Luego, crea un modelo de red neuronal con una capa oculta y una capa de salida, utilizando los vectores de las noticias como entrada.

Entrenamiento del Modelo: El modelo se entrena utilizando el conjunto de entrenamiento.

Matriz de Confusión y Gráficos: Calcula la matriz de confusión en el conjunto de prueba para evaluar el rendimiento del modelo. También genera un gráfico que muestra la matriz de confusión con detalles sobre las predicciones correctas e incorrectas.

Predicciones de Noticias de Prueba: Finalmente, se realizan predicciones en dos noticias de prueba. Cada noticia se vectoriza y se pasa al modelo para predecir si es verdadera o falsa.