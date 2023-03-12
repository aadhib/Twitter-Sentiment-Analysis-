# Twitter-Sentiment-Analysis
Twitter sentiment analysis is a natural language processing project that involves the analysis of the sentiment of tweets posted on Twitter. The project is implemented using Python and various libraries such as scikit-learn, tweepy, textblob, and NLTK corpora.

The sentiment analysis process involves the collection of Twitter data using the tweepy library, which provides an API for accessing Twitter data. Once the data is collected, it is preprocessed using NLTK corpora, which involves tasks such as tokenization, stop word removal, and stemming. The textblob library is then used to perform sentiment analysis on the preprocessed data, which involves the classification of tweets as positive, negative, or neutral based on the sentiment expressed in the tweet.

To improve the accuracy of the sentiment analysis, machine learning techniques are employed using scikit-learn. The scikit-learn library provides various algorithms for machine learning, including classification algorithms such as support vector machines, Naive Bayes, and decision trees. These algorithms are used to train a model on a labeled dataset of tweets to accurately classify new tweets based on their sentiment.

Overall, the Twitter sentiment analysis project provides a powerful tool for businesses and individuals to analyze the sentiment of tweets related to their brand or area of interest. By analyzing the sentiment of tweets, businesses can gain insights into customer opinions and preferences, while individuals can stay up to date on the sentiment of their favorite topics.

## Requirements
* Python
* Scikit-Lear
* Tweepy
* Tect blob
* NTLK Corpora

## Installation:
Note: You may need to run these commands as superuser.  
```
pip install scikit-learn 
```
Tweepy: tweepy is the python client for the official Twitter API.  
Install it using following pip command:  
```
pip install tweepy
```
TextBlob: textblob is the python library for processing textual data.  
Install it using following pip command:  
```
pip install textblob
```
Also, we need to install some NLTK corpora using following command:  
```
python -m textblob.download_corpora
```
Corpora is nothing but a large and structured set of texts. 

## Authentication:
In order to fetch tweets through Twitter API, one needs to register an App through their twitter account.  
Follow these steps for the same:  
* Open this [link](https://apps.twitter.com/) and click the button: 'Create New App'  
* Fill the application details. You can leave the callback url field empty.  
* Once the app is created, you will be redirected to the app page.  
* Open the 'Keys and Access Tokens' tab.  
* Copy 'Consumer Key', 'Consumer Secret', 'Access token' and 'Access Token Secret'.  
  
## To run:
```
python twitter_analysis.py
```
