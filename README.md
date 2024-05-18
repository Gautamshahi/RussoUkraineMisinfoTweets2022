# Misinformation tweets around the Russo-Ukrainian war

## Misinformation tweets

File: [misinformation_tweets_info_annotated.csv](https://github.com/Gautamshahi/UkraineWarTwitter_anonymized/blob/main/misinformation_tweets_info_annotated.csv), some of the columns are described below.

- id: tweet ID
- twitter_link: link to the tweet
- text: text of a tweet
- favorite_count:	likes count of tweet
- retweet_count: retweet count of a tweet
- user_id: user id who posted the tweet
- tweet_link_decision: any error messages Twitter gives for the tweet (checked in the beginning of May 2024); empty means it's available
- twitter_profile_link_decision: any error messages Twitter gives for the user (checked in the beginning of May 2024); empty means the user exists
- botometer_score: Bot score fetched from the [Botometer](https://botometer.osome.iu.edu/) and the date up to which data was available for it
