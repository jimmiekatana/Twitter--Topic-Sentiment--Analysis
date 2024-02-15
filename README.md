# Twitter--Topic-Sentiment--Analysis
**Introduction**

The purpose of this project is to perform sentiment analysis on the tweets  scraped from the twitter platiform.
The data will be cleaned and preprocesed before performing the sentiment analysis .This involves using natural language processing (NLP) techniques to classify tweets as positive ,negative or neutral based on language used in the tweets .
Tools and algorithms used for sentiment analysis typically employ machine learning techniques to classify tweets accurately.
These algorithms may consider various factors, including the use of certain words or phrases, emoticons,hashtags, and context within the tweet.

**Tools and technologies** 

nlp

wordcloudn

nltk

tweepy

**Scraping**

Gather tweets related to the topic of intrest by first adding the Twitter API key and secret.

Create  a Helper function for handling pagination in our search and handle rate limits.

Define  the term we will be using for searching tweets and how many tweets to get from the Twitter API.

Then, Process  the results from the search using Tweepy.


**Analysis**

1.Set up the API call to the Inference API to do sentiment analysis.

2.Run the sentiment analysis on each tweet.

3.Load the data in a dataframe using pandas .

4.Show a tweet for each sentiment.

5.Visualize the sentiments using Wordcloud with positive tweets and Wordcloud with negative tweets.


**Conclusion**

Twitter sentiment analysis can be useful for businesses, marketers, and researchers to understand public opinion about their products, services, or events. It can also be used to track trends, monitor brand reputation, and identify potential issues or opportunities.



