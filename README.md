# Homework7NewsMood
This project used Twitter's API in a Python script to perform a sentiment analysis of the Twitter activity of various news oulets, and to present the findings visually.
The final output provides a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: BBC, CBS, CNN, Fox, and New York times.

Technologies used: tweepy, Seaborn, Pandas, python, Vader Sentiment Analyzer, Textblob analyzer.


Observations:
1) Sentiment varies significantly depending on the current news. I ran this on several days and got fairly different results each time. So it's hard to make generalizations.
2) The majority of compound sentiment is within -0.75 and 0.75. There are few points outside that range.
3) Textblob is more optimistic than Vader in analyzing sentiment. Textblob's sentiments are much more positive than Vader's composite sentiments.
