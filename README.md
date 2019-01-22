# SocialAnalytics
Distinguishing Sentiments based on Twitter 

## Background

**Twitter** has become a wildly sprawling jungle of information—140 characters at a time. Somewhere between 350 million and 500 million tweets are estimated to be sent out _per day_. With such an explosion of data, on Twitter and elsewhere, it becomes more important than ever to tame it in some way, to concisely capture the essence of the data.


## News Mood

Create a Python script to perform a sentiment analysis of the Twitter activity of various news outlets, and to present findings visually.

Final output provides a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: **BBC, CBS, CNN, Fox, and New York times**.


The first plot will be and/or feature the following:

* Be a scatter plot of sentiments of the last **100** tweets sent out by each news organization, ranging from -1.0 to 1.0, where a score of 0 expresses a neutral sentiment, -1 the most negative sentiment possible, and +1 the most positive sentiment possible.
* Each plot point will reflect the _compound_ sentiment of a tweet.
* Sort each plot point by its relative timestamp.
![png](https://github.com/alphacart/SocialAnalytics/blob/master/Sentiment_Analysis_Tweets.png)


The second plot will be a bar plot visualizing the _overall_ sentiments of the last 100 tweets from each organization. For this plot, you will again aggregate the compound sentiments analyzed by VADER.
![png](https://github.com/alphacart/SocialAnalytics/blob/master/Overall_Media_Sentiment.png)

The tools of the trade needed for this task include the following: tweepy, pandas, matplotlib, and VADER.

Final Jupyter notebook contains:

* Pull last 100 tweets from each outlet.
* Perform a sentiment analysis with the compound, positive, neutral, and negative scoring for each tweet.
* Pull into a DataFrame the tweet's source account, its text, its date, and its compound, positive, neutral, and negative sentiment scores.
* Export the data in the DataFrame into a CSV file.
* Save PNG images for each plot.

* Complete analysis based on  Jupyter notebook.
* Used Matplotlib or Pandas plotting libraries.
* Included a written description of observable trends based on the data.
* Included proper labeling of plots, including plot titles (with date of analysis) and axes labels.
