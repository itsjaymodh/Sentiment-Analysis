# US Airlines Tweets Sentiment Analysis
### Introduction

This project conducts sentiment analysis on tweets related to US airlines. By analyzing the sentiment expressed in tweets, we aim to gain insights into customer opinions and experiences with different airlines. This README provides an overview of the project, including the code snippets used for data preprocessing, exploratory data analysis (EDA), and sentiment analysis.

### Overview
In this project, I have performed the following tasks:

### Data Loading: loading the dataset containing tweets related to US airlines.

### Data Preprocessing: Preprocessing the data to make it suitable for analysis. This includes converting the 'tweet_created' column to datetime format, handling null values, and removing unnecessary columns.

### Exploratory Data Analysis (EDA): analyzing the data to gain insights into tweet frequencies, sentiments, and their distribution across different airlines. EDA helps us understand trends and patterns in the data.

### Sentiment Analysis: I have conducted sentiment analysis using both lexicon-based and machine learning approaches. For lexicon-based analysis, I've used the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon. For machine learning, I have vectorized the text data using CountVectorizer and TfidfVectorizer, and then train various models such as Logistic Regression, Random Forest, and Support Vector Machine (SVM) to classify sentiments.
