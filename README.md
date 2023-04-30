# Analysis-of-AMLO-s-speeches

# Repository structure

The objective of this repository is to implement good practices according to the paper ["Good Enough Practices in Scientific Computing"](https://arxiv.org/abs/1609.00037) by Greg Wilson, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, Tracy K. Teal.

The structure that we want this repository to have is the following:

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


# Data

### **1st report on the Fourth Transformation of Mexico**

This report presents the advances and achievements of the Fourth Transformation of public life in Mexico, since the inauguration of the President of the Republic in December of 2018. Three main aspects stand out:

- **Separation of political power from economic power**: An effective separation between economic power and political power has been achieved. The current government represents all Mexicans, regardless of their ideology, sexual orientation, culture, language, place of origin, educational level, or socioeconomic position. An authentic rule of law has been established and the ideal of "Nothing outside the law and no one above the law" is sought.

- **Towards a participatory democracy**: Progress is being made towards a true democracy, with fair and free elections and the elimination of electoral fraud. It has been proposed to establish the mandate revocation mechanism as an effective form of citizen control over rulers. The Legislative Power is urged to eliminate the legal obstacles to popular consultation and to cancel the privileges of public servants, starting with the President of the Republic. Respect for the freedoms and freedom of choice of citizens in all aspects is promoted.

- **Foreign Policy**: Cooperation, friendship and respect are offered to all the countries of the world, especially to the sister nations of Latin America and the Caribbean, with special attention to the Central American nations. A bilateral relationship with the United States is sought based on mutual respect, cooperation for development, and a negotiated solution to common problems, such as the migratory phenomenon, the situation of Mexicans in that country, and transnational crime.

This report shows how politics for transformation is becoming a daily practice and progress is being made in building a fairer, freer and more prosperous Mexico for all its citizens.

![](https://media.giphy.com/media/yhpdLJxBUJTVQIhu3w/giphy.gif)


### **2nd report on the Fourth Transformation of Mexico**

- **The main problem in Mexico** is corruption and the current crisis originated from this problem. The government's goal is to completely eradicate corruption in order to transform and moralize the country.

- **The current government focuses on purifying the public life of Mexico**, without undertaking factious persecutions or allowing impunity. The "robbery" of politicians has been eliminated, but there is still work to be done to banish official banditry.

- **Republican austerity** is a reality and the government has been able to save around 560 billion pesos during his administration by not allowing corruption and having an austere government. Everything that is saved is used to achieve the well-being of the people.

- **Mexico is facing two crises**, the health and the economic one, but the government relies on a team of professionals with extensive experience and the ability to make decisions on the matter. The coronavirus has left pain, sadness, and hardship, but it has also strengthened love in families, has demonstrated the humanism and dedication of health workers, and has highlighted the well-known fraternity of our people.

- **The government received the country with 401 abandoned**, looted, or half-built hospitals, and with a deficit of more than 200,000 medical professionals. In a few months, 969 hospitals have been converted to care for patients with Covid-19, 32,203 beds have been installed and 10,612 with ventilators, and 47,000 general practitioners, specialists, nurses, and other health workers have been hired.


![](https://media.giphy.com/media/26xBMNOQjSdNTWgsU/giphy.gif)


### **3rd report on the Fourth Transformation of Mexico**

The President addresses his message to Mexican men and women, referring to the "transformation" that is underway in the country.

- He mentions the importance of banishing vices and dishonest practices in the government, as well as the need to change the mentality of the people.
The decisive measure to stop the privatization trend in Mexico is highlighted, and various sectors are mentioned in which concessions to individuals have ceased to be granted.

- The importance of the new energy policy is highlighted, which seeks to produce in Mexico the gasolines that the country consumes and stop importing them, allocating resources to the modernization of existing refineries and the construction of a new one.

- Reference is made to Pemex's association with Shell to share a refinery in Houston, Texas, and the recent purchase of the part of the foreign oil company is highlighted, becoming wholly owned by Pemex.

- Emphasis is placed on the idea of not extracting more oil than is essential to cover the demand for fuels in the domestic market, in order to fulfill the commitment to replenish 100% of proven reserves and reduce the excessive use of fossil fuels.

- The initiative for a constitutional reform in the electricity industry is mentioned, to repair the serious damage caused by privatization and modernize hydroelectric plants, reducing the use of fuel oil and coal in the production of electricity.

- The goal of having a sufficient public supply of electrical energy stands out, without blackouts and without domestic consumers paying for electricity with higher rates than business corporations and large commercial chains.

- Mention is made of the construction of various infrastructures in the country, without expensive public-private partnerships or the Pidiregas program, financed by the federal budget.

Finally, a long list of the various infrastructures that are being built in Mexico with this federal budget is presented, including roads, hospitals, schools, treatment plants, refineries, stadiums, among others.

<p align="center">
  <img src="https://media.giphy.com/media/3oEjI7WC5d4IFLcKfS/giphy.gif">
</p>


### **4th report on the Fourth Transformation of Mexico**

- A pesar de la pandemia y la guerra en Ucrania, México está mejorando económicamente gracias a la estrategia de apoyo a los más pobres y el tratado comercial con Estados Unidos y Canadá.

- México es considerado uno de los países con más potencial para invertir y hacer negocios.

<p style="text-align: justify;">En el gobierno actual, se han logrado varios avances, entre ellos: la prioridad a los pobres, la eliminación de la corrupción e impunidad, la distribución más justa de la riqueza, la elevación de derechos constitucionales para adultos mayores, discapacitados y estudiantes pobres, el fortalecimiento de la educación y la salud como derechos del pueblo, la reducción de la delincuencia, la garantía de la libertad de expresión y el derecho a disentir, la independencia de la Fiscalía General de la República y los poderes Legislativo y Judicial, la estabilidad del peso y el aumento de las reservas del Banco de México, la libertad religiosa y el Estado laico, la demostración de la riqueza cultural de México.</p>


![](https://media.giphy.com/media/gaZ01zvjkcS7zH3ulH/giphy.gif)
