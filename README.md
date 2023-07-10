# Group Members
1. Bless Ziamah - 10922782
2. Vera Achiaa Owusu - 10923847
3. Herbert Ansah Akrofi - 10923111

# Natural Language Processing with Disaster Tweets
## Documentation

## Overview
In this document, you will find the problem statement, approach, solution, results, and reflections of our Natural Language Processing with disaster tweets. The project aims to use Natural Language Processing (NLP) to determine which tweets talk about a disaster.

## Problem Definition
Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they are observing in real-time. But it is not always clear whether a person’s words are actually announcing a disaster. We will build a machine learning model that predicts which Tweets are about real disasters and which ones are not.

## Approach
The following steps were taken to tackle the problem:
1. Data Collection: The data was already provided by Kaggle in CSV format. We read the CSV file and converted it to a data frame.
2. Data Preprocessing: The data we collected went through various preprocessing stages to make them clean and uniform. The cleaning is done using regular expressions. Using regular expressions, hashtags, retweets, URLs, emojis, newlines, and stop words are removed.
3. Training Data: The data was passed through different models like Logistic Regression, Support Vector Classifier (SVC), and Multinomial NB.
4. Visualization: Here we visualize the performance of all the models to see how well they were able to predict if a tweet is talking about a disaster or not.

## Findings
Logistic Regression Outperforms Support Vector Classifier (SVC) and Multinomial Naive Bayes (NB)
The performance of each model was evaluated based on various metrics such as accuracy, precision, recall, and F1-score.
Based on these findings, it can be concluded that Logistic Regression is the most suitable model for this specific dataset and task.