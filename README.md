# twitter_sentiment_challenge

##Overview

This is the code for the Twitter Sentiment Analyzer challenge for 'Learn Python for Data Science #2' by @Sirajology on [YouTube](https://youtu.be/o_OZdbCzHUA). The code uses the [tweepy](http://www.tweepy.org/)  library to access the Twitter API and the [TextBlob](https://textblob.readthedocs.io/en/dev/) library to perform Sentiment Analysis on each Tweet. We'll be able to see how positive or negative each tweet is about whatever topic we choose. 

##Dependencies

* tweepy (http://www.tweepy.org/)
* textblob (https://textblob.readthedocs.io/en/dev/)

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

##Usage

Once you have your dependencies installed via pip, run the script in terminal via

```
python demo.py
```

##Challenge

Last week, there was the french Republicans Primary debate on television.
I tried to apply Siraj's sentiment analysis to this night of debate in order to compare the seven different candidates.
Here is the result of the analysis : 

Mean Sentiment Polarity in descending order :
Le Maire : 0.048
Kosciusko : 0.021
Poisson : 0.019
Sarkozy : 0.010
Cope : 0.005
Fillon : -0.005
Juppe : -0.017

##Credits

This code is forked from Siraj
