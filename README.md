# Sentiment-Analysis
sentiment analysis of twitter data

Libraries used: 
nltk, tweepy, pandas, re, string, random, itertools, numpy, sklearn, collections, matplotlib

Motivation: 
The motivation of this project is to develop skills in data analysis, engineering, and data science. This is explored through a sentiment analysis exercise using twitter data. 

File descriptions: 
Sentiment_Analysis_Twitter.ipynb walks through data acquisition, exploration, engineering, modeling, and results.

link to blog post: https://nicollenavigos.wordpress.com/paris-airbnb-listings/sentiment-analysis-of-twitter-data/ 
Password: Udacity

Summary of Results: 
I used tweets that were prelabeled as positive or negative sentiment. I cleaned the data for urls, @ signs, and stop words. I one hot encoded the unique words as predictors and sentiments as y values. I used a multinomial naive bayes model which predicts sentiment with an accuracy of 99.6% accuracy in the testing data. Future work includes testing other models and predicting complex sentiments such as happiness, boredom, jealousy, indifference, etc. 

Acknowledgements:
https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html
https://developer.twitter.com/
https://towardsdatascience.com/multinomial-naive-bayes-classifier-for-text-analysis-python-8dd6825ece67
