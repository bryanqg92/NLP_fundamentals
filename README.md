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
