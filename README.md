# Twitter-Sentiment-Analysis-Using-Python

This script can tell you the sentiments of people regarding to any events happening in the world by analyzing tweets related to that event. It will search for tweets about any topic and analyze each tweet to see how positive or negative it's emotion is. You might want to check out this complete text and video based detailed tutorial link

# What is sentiment analysis?

Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker.

# Why sentiment analysis?

>Business: In marketing field companies use it to develop their strategies, to understand customers’ feelings towards products or brand, how people respond to their campaigns or product launches and why consumers don’t buy some products.

>Politics: In political field, it is used to keep track of political view, to detect consistency and inconsistency between statements and actions at the government level. It can be used to predict election results as well!

>Public Actions: Sentiment analysis also is used to monitor and analyse social phenomena, for the spotting of potentially dangerous situations and determining the general mood of the blogosphere.

# Getting Started

First of all login from your Twitter account and goto Twitter Apps. Create a new app (How to create twitter app) and goto Keys and access tokens and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later.

# Installation

Download or Clone the repo, Navigate to the directory containing the files and run

      python setup.py install
      
or if you have different versions of python installed then

      python3 setup.py install 
      
to install the dependencies.


# Usage

Once you have created an app on twitter and installed all the dependencies by running setup.py, open main.py and paste your Consumer Key, Consumer Secret, Access Token and Access Token Secret. After that save and run the script. You will be prompted to enter the keyword/hashtag you want to analyze and the number of tweets you want to analyze. Once the analysis is completed, a pie chart will be generated disclosing the results of analysis.


# Built With

 -Python 2.7
 
 -tweepy
 
 -textblob
 
 -re

# Contributing
1.Fork it

2.Create your feature branch: git checkout -b my-new-feature

3.Commit your changes: git commit -am 'Add some feature'

4.Push to the branch: git push origin my-new-feature

5.Submit a pull request

# Authentication:

In order to fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps for the same:
    .Open this link and click the button: ‘Create New App’
    .Fill the application details. You can leave the callback url field empty.
    .Once the app is created, you will be redirected to the app page.
    .Open the ‘Keys and Access Tokens’ tab.
    .Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.
