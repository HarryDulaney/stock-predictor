# stock-predictor
AI and ML in Finance Final Project 

### This Python application has two distinct parts:
#### _Part I:_
Applies Long Short-Term Memory (LSTM) neural network architecture in a deep learning model to analyze time-series data (MSFT Stock Prices). We then use the model to make predictions about future prices and to then graph the results against known values in order to illustrate the accuracy of the model.
#### _Part II:_ 
Performs sentiment analysis on business articles which are first web-scraped and then cleaned by parsing their HTML tags into Strings. We then programmed a custom implementation of Python’s popular sentiment scoring library for social media, VADER. By infusing VADER’s Lexicon with the Loughran / McDonald positive and negative words list, an academic lexicon of words for determining sentiment of financial documents, we used VADER to score the business articles and chart changing sentiment over time. 
