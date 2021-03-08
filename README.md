# Crude_Oil_Sentiment_Analysis
Scrape data from OilPrice.com and use it to build a market sentiment analyzer for Crude Oil

A Gaussian Naive Bayes classifier has been used
The process will be divided into 3 phases:
1. Obtaining data from OilPrice.com
2. Calculating the actual NLP score using Vader and classifying into positive, negative, and netural
3. Creating a Naive Bayes Classifier and training the model using 90% of the data, with the Vader sentiment taken as the correct predicted sentiment, and then testing the model with the remaining 10% data to test its accuracy
