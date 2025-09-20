# Sentiment Analysis on Spanish Movie Reviews

[Full project version here](

## Overview
This project performs **sentiment analysis** on Spanish movie reviews using both **lexicon-based approaches** and **supervised machine learning models**.  
It explores the relationship between textual sentiment expressed in reviews and numerical movie ratings, analyzing how sentiment varies across different film genres.  
The project combines **natural language processing (NLP)** techniques with **statistical analysis** to extract meaningful insights from unstructured text data.

---

## Objective
The primary goal is to apply **opinion mining techniques in Spanish** to analyze movie reviews, examining the relationship between review polarity and factors such as:
- Film genre  
- Average movie rating  

The project compares **lexicon-based methods** with **supervised learning approaches** (Naïve Bayes and Logistic Regression) to determine the most effective classification strategy for **Spanish sentiment analysis**.

---

## Data 
The dataset was provided in an **academic context** during my degree coursework.  
Due to intellectual property restrictions, the raw data and access link are **not publicly available**.  
The dataset consists of these variables:
- Review text content  
- Movie titles and genres  
- Individual review titles  
- Average film ratings  
- Gender classification of films  

The data was processed to extract **sentiment polarity** at both **individual review** and **movie aggregate** levels.

---

## Techniques

- **Text Preprocessing**: Tokenization, lowercase conversion, punctuation removal, stopword elimination  
- **Lexicon-Based Analysis**: NRC sentiment dictionary for Spanish with positive/negative classification  
- **Feature Engineering**: Term-Document Matrix creation with dimensionality reduction  
- **Supervised Models**: Naïve Bayes and Logistic Regression   
- **Visualization**: Word clouds, correlation plots and sentiment distribution histograms  

---

## Evaluation Metrics
Models were evaluated using:
- **Accuracy** → Overall classification correctness  
- **F1-score** → Harmonic mean of precision and recall  
- **Kappa** → Agreement coefficient correcting for random chance  

---

## Major Findings
- **Weak Correlation**: Minimal linear relationship (-0.1) between sentiment polarity and numerical ratings  
- **Genre Dependencies**: Sentiment-rating correlation varies significantly by genre (positive in adventure/romance, negative in drama/thriller)  
- **Model Performance**: Logistic Regression achieved superior performance (**91.6% accuracy, Kappa = 0.807**) compared to Naïve Bayes (**77.3% accuracy, Kappa = 0.555**)  
- **Lexicon Limitations**: Dictionary-based approach performed worse than random (**52.5% accuracy, negative Kappa**)  

---

## Some Key Visual Takeaways 
### Models evaluation metrics
_Comparision between all models:_
![Models evaluation metrics]()

### Polarization histogram:
_Comparasion between all film genres:
![Polarization histogram]()
---

## 🛠️ Skills and Tools
- **Programming**: R  
- **Libraries**: tidyverse, tidytext, tm, syuzhet, caret, glmnet, wordcloud, ggplot2  
- **NLP Techniques**: Tokenization, sentiment analysis, term-document matrices  
- **Machine Learning**: Naïve Bayes, Logistic Regression, model evaluation  
- **Data Visualization**: Histograms, scatter plots, word clouds, comparative metrics charts  
- **Data Processing**: Text cleaning, feature engineering, correlation analysis  

---
**Note**: HTML in Spanish; description here is in English for international visibility and portfolio presentation. The graphics shown are all own-elaborated.
