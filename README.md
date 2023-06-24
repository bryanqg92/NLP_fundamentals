# NLP_fundamentals

En este repositorio encontrarás una variedad de temas relacionados con:

Procesamiento de Lenguaje Natural (NLP)
Aprendizaje Automático (Machine Learning)
Redes Neuronales
Proyectos y Desafíos de NLP
Explora el código fuente, tutoriales y ejemplos prácticos para adentrarte en el emocionante mundo del NLP y el aprendizaje automático.

¡Diviértete explorando y aprendiendo!

# Requisitos
Python 3.x
Bibliotecas de Python: numpy

##  Instrucciones de Uso para todas las notebooks
Ejecuta el código en un entorno Python compatible.
Asegúrate de tener instaladas las bibliotecas de Python mencionadas en los requisitos.
Modifica el corpus de textos en la sección "Datos" si deseas trabajar con un conjunto de documentos diferente.

# Primer desafío (1st Challenge)
En este notebook, se implementan diferentes técnicas de vectorización de texto, incluyendo one-hot encoding, vectores de frecuencia y TF-IDF. Estas técnicas permiten representar documentos de texto como vectores numéricos, lo que facilita su procesamiento en algoritmos de aprendizaje automático.

## ¿Qué encontrarás?
cosine_similarity(a, b):Esta función calcula la similitud del coseno entre dos vectores, a y b.

![Cosine](https://datascientest.com/es/wp-content/uploads/sites/7/2020/09/word2vec.png.webp)


get_vocab(corpus): obtiene el vocabulario único de un conjunto de documentos corpus.

oneHot(corpus, vocab):realiza la codificación one-hot de los documentos en un corpus.

frequency_vectors(corpus, vocab): genera una matriz que representa la frecuencia de los términos en los documentos.

tfidf_representation(corpus):
Descripción: Esta función calcula la representación TF-IDF de un conjunto de documentos.

document_similarity(corpus, doc_index):
Descripción: Esta función calcula la similitud coseno entre un documento específico y los demás documentos en el corpus.

# Segundo desafío (2nd challenge) Deep Learning Bot

Este proyecto consiste en un modelo de bot basado en reglas que utiliza la biblioteca SpaCy para realizar procesamiento de lenguaje natural y proporcionar sinónimos de frases de entrada. El bot es capaz de encontrar ciertos patrones en una frase y generar una respuesta correspondiente.

## Características principales
Utiliza deep learning para realizar tareas de procesamiento de lenguaje natural.
Implementa reglas y patrones para encontrar correspondencias y generar respuestas.
Aplica técnicas de vectorización y preprocesamiento de texto para mejorar la comprensión y respuesta del bot.

# Desafío 3: Word Embeddings y Similaridad de Palabras
En este tercer desafío, trabajaremos con el mismo conjunto de datos utilizado en el segundo desafío, que consiste en instrucciones de seguimiento de pared para un robot. Sin embargo, en esta ocasión, nos enfocaremos en utilizar y entrenar modelos de Word Embeddings utilizando el algoritmo Word2Vec. Además, exploraremos la similaridad entre palabras presentes en el dataset.
![Word2Vec](https://datascientest.com/es/wp-content/uploads/sites/7/2020/09/word2vec-1024x404.jpg.webp)

## Características principales
Utilizaremos el algoritmo Word2Vec para entrenar Word Embeddings.
Analizaremos la similaridad entre palabras en el conjunto de datos.
Mejoraremos el entendimiento de las instrucciones de seguimiento de pared mediante la representación vectorial de palabras.

# Desafío 4 Deep Learning para NLP: Redes Neuronales Recurrentes con Celdas de Elman
En este proyecto, nos aventuraremos en el mundo del Deep Learning aplicado al Procesamiento del Lenguaje Natural (NLP, por sus siglas en inglés). Utilizaremos modelos de Redes Neuronales Recurrentes (RNN) con celdas de Elman, que son una de las formas más básicas de RNN. Nuestro objetivo será predecir la siguiente palabra en un texto utilizando un conjunto de cuentos cortos como conjunto de datos. Para lograrlo, utilizaremos técnicas de preprocesamiento de datos con el Tokenizer de Keras.

## Características principales
Utilizaremos modelos de Redes Neuronales Recurrentes con celdas de Elman para realizar predicciones de texto.
Implementaremos preprocesamiento de datos utilizando el Tokenizer de Keras.
Utilizaremos un conjunto de cuentos cortos como conjunto de datos de entrenamiento.

# Desafío 5: Análisis de Sentimientos de Reviews de Prendas de Vestir

En este desafío, analizaremos los sentimientos expresados en las reviews de usuarios sobre prendas de vestir.
Utilizaremos un conjunto de datos desbalanceado que contiene opiniones positivas y negativas.
Implementaremos modelos de encoder-decoder con embeddings FastText y embeddings sin preentrenar para abordar este problema.

## Características principales:
- Preprocesamiento de datos: Limpiaremos y prepararemos las reviews utilizando técnicas como eliminación de stopwords y lematización.
- Modelos de encoder-decoder: Utilizaremos dos enfoques, uno con embeddings FastText preentrenados y otro con embeddings sin preentrenar que entrenaremos durante el proceso de entrenamiento del modelo.
- Manejo del desbalanceo de clases: Abordaremos el desbalanceo de clases mediante técnicas de re-muestreo, como submuestreo o sobremuestreo.
- Evaluación de resultados: Utilizaremos métricas de clasificación más adecuadas que la exactitud (ACC) debido al desbalanceo del conjunto de datos. Analizaremos precision, recall y puntuación F1, entre otras métricas.

Este desafío proporcionará experiencia práctica en el análisis de sentimientos de texto, manejo de conjuntos de datos desbalanceados y utilización de modelos de encoder-decoder con diferentes enfoques de embeddings.
Al finalizar, obtendrás una mejor comprensión de cómo realizar análisis de sentimientos en el contexto de reviews de productos.

# Desafío 6: Modelo Preentrenado con FastText para un Bot de Preguntas y Respuestas

En este desafío, trabajaremos en la creación de un modelo de preguntas y respuestas basado en un bot.
Utilizaremos un modelo preentrenado con embeddings FastText para comprender y responder preguntas de los usuarios.
El conjunto de datos utilizado se encuentra en formato JSON y el preprocesamiento adecuado de los datos será clave para el entrenamiento del modelo.

## Características principales:
- Preprocesamiento de datos: Realizaremos un preprocesamiento exhaustivo de los datos, incluyendo la tokenización, eliminación de stopwords y lematización, para preparar las preguntas y respuestas antes de entrenar el modelo.
- Uso de embeddings FastText preentrenados: Utilizaremos embeddings FastText preentrenados para capturar la semántica de las palabras y mejorar la comprensión del modelo.
- Entrenamiento del modelo: Implementaremos un modelo de preguntas y respuestas basado en un bot utilizando el modelo preentrenado con FastText. El objetivo será entrenar al bot para que pueda entender las preguntas de los usuarios y proporcionar respuestas relevantes.
