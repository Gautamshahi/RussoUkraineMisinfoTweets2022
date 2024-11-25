# Misinformation tweets around the Russo-Ukrainian war

## Misinformation tweets

File: [misinformation_tweets_info.tsv](https://github.com/Gautamshahi/RussoUkraine2022/blob/main/misinformation_tweets_info.tsv), some of the columns are described below.

- id: tweet ID
- twitter_link: link to the tweet
- text: text of a tweet
- favorite_count:	likes count of tweet
- retweet_count: retweet count of a tweet
- user_id: user id who posted the tweet
- tweet_link_decision: any error messages Twitter gives for the tweet (checked in the beginning of May 2024); empty means it's available
- twitter_profile_link_decision: any error messages Twitter gives for the user (checked in the beginning of May 2024); empty means the user exists
- botometer_score: Bot score fetched from the [Botometer](https://botometer.osome.iu.edu/) and the date up to which data was available for it

## Retweets

File: [misinformation_retweets.csv.gz](https://github.com/Gautamshahi/RussoUkraine2022/blob/main/misinformation_retweets.csv.gz)

- id: tweet ID of the retweet
- misinfo_id: tweet ID of the misinfo tweet that is being retweeted

## Search keywords for Fact-checked articles

The list of search keywords extracted from the Wikinews categories are as follows:

russian invasion of ukraine, russian invasion, invasion of ukraine, russo-ukrainian war, ukrainian war, controversies, international relations, russia, ukraine, europe, military history, military, military history of russia, history of russia, conflicts, invasions by russia, invasions russia, invasions, invasions of ukraine, opposition to nato, nato, conflicts in territory of the former soviet union, soviet union, former soviet union, russian irredentism, irredentism, russian–ukrainian wars, belarus–nato relations, belarus, belarus–ukraine relations, russia–nato relations, ukraine–nato relations, russia–nato, russia nato, ukraine nato, ukraine–nato, vladimir putin, putin, vladimir, volodymyr zelenskyy, volodymyr, zelenskyy, alexander lukashenko, alexander, lukashenko, wars involving belarus, wars involving Chechnya, wars involving russia, wars involving the donetsk people republic, wars involving the luhansk people republic, wars involving ukraine, donetsk, luhansk

## Search keywords for Tweets
The list of search keywords used for collecting tweets:

'ukraine', 'ukrainewar', 'ukrainerussiawar', 'kiev', 'kyiv', 'standwithukraine', 'stopputin', 'russiaukrainewar', 'украина', 'Україна', 'Україні', 'СлаваУкраїни', 'НетВойне', 'Киев', 'Bійна', 'Українська', 'UkraineRussia', 'Росія', 'Путін', 'путин', 'putin', 'RussianAggression', 'FreeUkraine', 'война', 'Крым', 'donbas', 'luhansk', 'ukraina', 'Ukraine', 'Ukrajna', 'ukrajina', 'ukrayna', 'Ukraïne', 'úkraín', 'ucraina', 'Ucrania', 'украине', 'украйна', 'ukraina', 'Украин', 'ukrain', 'україни', 'Ukireni', 'ukrajina', 'ukrayna', 'ukrajin', 'Yukreeniyaan', 'ዩክሬን', 'اوكرانيا', 'ուկրաինա', 'ইউক্রেন', 'ukrajina', 'Ucraïna', '乌克兰', 'Uccrainia', 'Oekraïne', 'ukrainio', 'ucraína', 'უკრაინა', 'Ουκρανία', 'યુક્રેન', 'Ikrèn', 'Ukelena', 'אוקראינה', 'Úcráin', 'ウクライナ', 'ಉಕ್ರೇನ್', 'អ៊ុយក្រែន', '우크라이나', 'Okraina', 'ഉക്രെയ്ൻ', 'युक्रेन', 'ယူကရိန်း', 'युक्रेन', 'ୟୁକ୍ରେନ', 'اوکراین', 'اوکراین', 'Ucrânia', 'Ugrain', 'يوڪرائين', 'යුක්රේනය', 'உக்ரைன்', 'ఉక్రెయిన్', 'ยูเครน', 'یوکرین', 'wcrain', 'Yukreyini', 'אוקריינא'


