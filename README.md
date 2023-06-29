# Twitter_Sentiment_Analysis
Twitter Sentiment Analysis using Natural Language Processing

# Introduction
This project is to design a model which can classify tweets present on social media as racist and non-racist with the help of Natural Language Processing.

# Implementation Details

## Data Cleaning:
Here in our data no columns containing nan values and duplicate data values are present so data cleaning not required.

## Data Preprocessing:
1. Remove shortwords, punctuations,numbers,special characters and twitter handles from the text. 
2. Tokenize the text data.
3. Apply stemming on the data to convert into root form.
4. Combine the tokenized words into a single sentence.

## Data Analysis:
1. Perform analysis on the number of +ve tweets(non-racist) and -ve tweets(racist) by plotting a pie chart.
2. Perform analysis on number of frequent words in +ve tweets and -ve tweets.

## Model Building:
1. Vectorize the transformed data using tf-idf(Term Frequency-Inverse Document Frequency) algorithm and remove the stopwords.
2. Train model using different classifier algorithms like Gaussian Naive Bayes,Multinomial Naive Bayes,Bernoulli Naive Bayes,Logistic Regression and compare the accuracy and precision score.
3. Choose model based on higher accuracy and precision score.

Here we can see the accuracy and precision scores for various models which include Gaussian Naive Bayes,Multinomial Naive Bayes,Bernoulli Naive Bayes and Logistic Regression.
![twitter_sentiment_analysis - Jupyter Notebook - Opera 29-06-2023 23_08_02](https://github.com/ayanb2000kgpian/Twitter_Sentiment_Analysis/assets/138036625/15e053a1-53b6-4813-86c9-fd493112aa93)


Here we will use the multinomial Naive Bayes classifier since it has higher accuracy and higher precision as well. We are considering the precision since our data is imbalanced.
