TWITTER SENTIMENT ANALYSIS
--------------------------


INTRODUCTION
------------

This assignment has three modules, namely, 
 
* Data Collection
* Preprocessing
* Sentiment Analysis


DATA COLLECTION
---------------

There are three parts to this module. 

- In this section, the tweets have been gathered using 
  Twitter Search API that retrieves tweets for a given 
  hashtag.

- The gathered tweets have been stored in a MongoDB 
  MongoDB database 'SearchAPITweetsDB' in collections
  'midtermelection' and 'thalapathyking' for hashtags
  #MidtermElection2018 and #ThalapathyKingOfBoxOffice
  respectively.

- These tweets from the database are then saved in a
  .csv file. 


PREPROCESSING
-------------

The following preprocessing tasks have been performed 
on all the collected tweets.

* Exploratory Data 
* Text Preprocessing
* Visualization

SENTIMENT ANALYSIS
------------------

Two approaches have been followed to analyze sentiment
of the given tweets.

* Utilizing in-built Python Package TextBlob
* Building a Classification Model using Logistic Regression Algorithm


NOTE:
-----

* To begin viewing the code, go to "Twitter Data Analysis.ipynb".
* To view the preprocessing and analysis of tweets, go to "Analysis of Tweets.ipynb"

