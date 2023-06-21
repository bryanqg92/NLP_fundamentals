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

# Segundo desafío (2nd challenge)

Aquí puedes encontrar las primeras nociones de deep learning en un modelo de bot basado en reglas utilizando la librería spacy. El bot es capaz de encontrar ciertos patrones en una frase de entrada para entregarte un sinónimo de esta frase, como por ejemplo.
Q: cuando estés lento a la medio estás te ni alejando despacito de ella tu rueda derecha muy delante hacia pared y gira tu rueda muy delante más hacia pared
bot:si te estás acercando a la pared pero aún estás lejos, gira tu rueda izquierda más o menos rápido hacia adelante y la derecha muy lento adelante.

Se aplicaron conceptos de vectorización y preprocesado de texto.
