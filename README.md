# 2023NigerianElections

How I Analysed Twitter Data for the 2023 Nigerian Presidential Election using Machine Learning

Group of people mostly youths protested against the outcome of the 2023 Presidential election, as Former Lagos governor Bola Tinubu was declared the winner of Nigeria's 2023 presidential election. The defeated Nigerian candidates also vowed legal challenge.

However, in this article, I will discuss an experiment I conducted on the 2023 Nigerian Presidential election using Twitter data and machine learning.

I first obtained an academic license for the Twitter developer account and scrapped tweets in Abuja location, specifically the Twitter handle of the Independent National Electoral Commission (INEC) Nigeria, during the Presidential election results declaration on 2023-03-01. I imported libraries such as Tweepy, Textblob, and Word Cloud to analyze the tweets.

Next, I cleaned the tweets by removing web links, emojis, symbols, and alphanumeric characters. I then converted the tweets into a dataframe containing the tweet text, date, and location. To evaluate the sentiment of the tweets, I used polarity check to classify them into positive, negative, and neutral tweets. Finally, I used two machine learning classifiers - KNN (59%) and Lgb (63%) - to classify the tweets and obtain their accuracy and classification efficiency.

The results showed that neutral tweets were the highest at 58%, followed by positive tweets at 24%, and negative tweets at 17%. However, the classification task failed to correctly predict the sentiment of the tweets, as major citizens were not happy with the election outcome. This could be attributed to some Nigerian slangs and words falsely predicted by the machine learning classifiers.

Many social media platforms like Twitter have become a vital tool for political engagement, especially during elections. The use of machine learning classifiers in analysing Twitter data provides a useful way of gaining insights into public opinion. However, as demonstrated in this experiment, I didn’t consider local context and language peculiarities when analysing social media data using machine learning.

Please follow me on LinkedIn: https://www.linkedin.com/in/nkoro-ebuka-40b9a2160/ email: nkorochinaechetam@gmail.com
