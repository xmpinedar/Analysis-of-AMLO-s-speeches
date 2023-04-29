# Carpeta con bases de datos limpias y analizadas

¡Bienvenidos a nuestro proyecto de análisis de los 4 informes de gobierno del Presidente Andrés Manuel López Obrador (AMLO) en México!

En esta carpeta de GitHub encontrarás una selección de resultados obtenidos a través de nuestro análisis de los informes de gobierno del presidente AMLO.

Los resultados presentados aquí incluyen visualizaciones, tablas y otros recursos que te permitirán entender mejor los logros y desafíos del gobierno durante los primeros cuatro años de su mandato.

Para este proyecto, hemos utilizado diferentes herramientas y técnicas de análisis de datos, incluyendo:

- El modelo de lenguaje de Spacy para español, cargado con la línea nlp = spacy.load("es_core_news_sm").
- Las bibliotecas de procesamiento de texto NLTK, cargadas con las líneas from nltk.tokenize import word_tokenize y from nltk.corpus import stopwords.
- El analizador de sentimientos NLTK, cargado con la línea from nltk.sentiment import SentimentIntensityAnalyzer.
- La biblioteca de generación de nubes de palabras WordCloud, cargada con la línea from wordcloud import WordCloud.
- La biblioteca de visualización de gráficos Matplotlib, cargada con la línea import matplotlib.pyplot as plt.
- La biblioteca de sistema operativo OS, cargada con la línea import os.
