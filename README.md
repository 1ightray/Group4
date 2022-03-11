# Group4
# Team 4 Project 2 Solving a Fintech problem with Machine Learning

Libraries used: News API, Vader Sentiment Analysis of Crypto, Dogecoin based on using getdummies on Title sentiments for features
Analysis Period: 1 Month due to limitations of data

# Project Goal
To analyze the impact of Newsapi word analysis on Crypto Prices based on Sentiment Analysis of hashtags and specific infleuncers

Description
The first notebook gathers crypto prices and saves it into a csv file in order to be careful of the news api limits.
Logistic regression notebook uses sklearn to fit dataframe made from the csv where the x features are volume,close, and sentiment values
and the y target is the trending. This notebook is used to predict the trend, with additional analysis using confusion matrix and
classification report from sklearn metrics.

random forest notebook starts off the same as the logistic regression notebook, and then scales the data into a random forest classifier
with a random state of 78, after fitted predictions are made and confusion matrix and classification report is called 
also a feeatures importance chart is then plotted to show which feature has more weight

sentiment analysis notebook

This project is based on several machine learning libraries and techniques using python. The three models we will use for analysis include Logistic
regression, random forest, and LSTM.


Requirements -  minimum 2 machine learning libraries: scikit-learn for sentiment analysis, logistic regression, randomforest and tensorflow for LSTM



# Presentation Link
https://docs.google.com/presentation/d/1Ci1CHYfLTzEaeCxrYW0VAeGIs-QD0tbjeiqpC1wj7Zw/edit?usp=sharing

# References
https://github.com/MartinBeckUT/TwitterScraper/blob/master/snscrape/python-wrapper/snscrape-python-wrapper.ipynb



Project 2 (which notebooks used)
Code Snippets

//
