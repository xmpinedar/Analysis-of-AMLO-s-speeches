# Analysis-of-AMLO-s-speeches

# Estructura de repositorio

El objetivo de este repositorio es implementar las buenas prácticas de acuerdo al paper ["Good Enough Practices in Scientific Computing"](https://arxiv.org/abs/1609.00037) por Greg Wilson, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, Tracy K. Teal.

La estructura que queremos que tenga este repositorio es la siguiente:

    ├── LICENSE           <- MIT License.  
    |  
    ├── README.md         <- Main Readme file with the description of the project.  
    |  
    ├── CONTRIBUTING.md   <- Steps yo contribute to the project.  
    |  
    ├── CITATION.md       <- Way to cite the project.  
    |  
    ├── data              <- Original data bases.  
    |  
    ├── doc               <- Archivos de texto.  
    |  
    ├── results           <- Clean and analyzes data bases.  
    |  
    └── src               <- Coding files.  

# Introduction

Imagine you are a data scientist working in an organization that monitors the speeches of political leaders around the world. Your job is to analyze these speeches and extract valuable information that can be used to aid decision-making and better understand international politics.

One day, you receive a request to analyze the speeches of the president of Mexico over the past four years. Your first task is to collect the speeches and save them in text files for analysis.


![](https://media.giphy.com/media/5UEC2KURywThdh7dPS/giphy.gif)



# Libraries

In the project, several Python libraries were imported to analyze the speeches of the president of Mexico in his four government reports. 

-First, the "**os**" library was imported to access and read the speech files. 

-Then, the "**spacy**" library was imported to load the Spanish language model and other NLP libraries such as "**word_tokenize**" and "**stopwords**" from "**nltk**" to tokenize and filter common words.

In addition, the "**SentimentIntensityAnalyzer**" library from "**nltk**" was imported to analyze the sentiment of the speeches and the "**WordCloud**" library was imported to generate graphical visualizations of the most common words in the speeches. 

To load each speech file, a "**fo**r" loop was used and saved in a list called "**speeches**", which has four elements corresponding to the speeches of the four government reports of the president of Mexico.



