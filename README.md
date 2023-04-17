# Capstone : Twitter NLP & Crypto Coin Recommender
**Nicholas Nguyen**

---
 
 ## The objective of this project is to utilize NLP to identify undervalued coins on Twitter based on who you're following.
 

---

+ **Data** : `tweets_following.csv` , `tweets_entire.csv`, `sentiment.csv` | `df3`
  + Source : [Twitter]('https://twitter.com/GemsofRa')
  + Size : 7226 rows × 12 columns | 86,712 elements
  + Columns : `['id', 'date', 'username', 'content', 'hashtags', 'Likes', 'cleaned_tweets', 'followers', 'coin4', 'cleaned_tweets_pp', 'sentiment', 'sentiment_rank']`
  
| **Name**   | **Description** | **dtype** |
| ----------- | ----------- | ------- |
|`id`|_ID of the tweet_| int |
|`date`|_date_|datetime[64]|
|`username`|_Twitter username_|object|
|`Content`|_Original Tweet_|object|
|`hashtags`|_Hashtags involved with the tweet_|object|
|`Likes`|_Amount of likes_|int64|
|`cleaned_tweets`|_Original Tweets without special characters, tags, links_|object|
|`followers`|_Amount of followers_|int|
|`coin4`|_Coin involved with tweet_|object|
|`cleaned_tweets_pp`|_Cleaned_Tweets preprocessed with stopwords_|object|
|`sentiment`|_Sentiment Number based on cleaned_tweets_pp_|float|
|`sentiment_rank`|_Sentiment * (0.1 * log(# of followers))_|float|

---

**Primary Findings**
+ 

**Recommendations**
+ 

**Conlusions**
+ 

**Next Steps**
+ 

---

**In this Repository**
- `code` : this folder contains all notebooks associated with the project
  - `00_Problem_Statement`
  - `01_Data_Collection & Cleaning`
  - `02_Preprocessing_Modeling`
  - `03_Conclusion_Recommendations`

- `data` : this folder contains all csvs collected or created throughout the project
  - `tweets.csv`