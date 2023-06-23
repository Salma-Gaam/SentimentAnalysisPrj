# E-Commerce Sentiment Analysis Project
## Problem
The problem is to determine the level of client satisfaction based on the reviews or comments provided on products.  
The challenge lies in extracting meaningful insights and sentiments from these reviews and accurately assessing the overall satisfaction of clients without explicit satisfaction scores. By leveraging natural language processing techniques and sentiment analysis, the goal is to develop a reliable and accurate model that can interpret the textual feedback from clients and estimate their satisfaction levels effectively. 

## Solution
The problem at hand is to develop a sentiment analysis model that can accurately predict the sentiment or score assigned by customers in their reviews of Amazon products.

## Implementation
1- Data import and Exploratory data analysis  
2- Splitting the data,cleaning & preprocessing (Tokenize sentences, Remove capital letters, Remove stopwords, Remove non-alphanumeric characters, Lemmatize the tokens)  
3- Visualization with WordClouds  
4- Vectorizing data using TfidfVectorizer and train&test the four models (SVM, KNN, Logistic Regression and Random Forest)  
5- Vertorizing data using CountVectorizer and train&test the four models (SVM, KNN, Logistic Regression and Random Forest)  
6- Comparison of machine learning models with the two methods of vectorizing data  

## Conclusion
After the evaluation, it has been observed that the Logistic Regression model outperforms the other three models in terms of predicting sentiment accurately. It showed the ability to effectively capture patterns and relationships within the review texts, resulting in more accurate sentiment predictions. Additionally, the tf-idf (Term Frequency-Inverse Document Frequency) feature extraction technique has shown superior performance compared to the count vectorizer in this particular case.
