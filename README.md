# twitter-mawkishness-analysis

Sentiment analysis, also refers as opinion mining, is a sub machine learning task where we want to determine which is the general sentiment of a given document. Using machine learning techniques and natural language processing we can extract the subjective information of a document and try to classify it according to its polarity such as positive, neutral or negative. It is a really useful analysis since we could possibly determine the overall opinion about a selling objects, or predict stock markets for a given company like, if most people think positive about it, possibly its stock markets will increase, and so on. Sentiment analysis is actually far from to be solved since the language is very complex (objectivity/subjectivity, negation, vocabulary, grammar,...) but it is also why it is very interesting to working on.
In this project I choose to try to classify tweets from Twitter into “positive” or “negative” sentiment by building a model based on probabilities. Twitter is a microblogging website where people can share their feelings quickly and spontaneously by sending a tweets limited by 140 characters. You can directly address a tweet to someone by adding the target sign “@” or participate to a topic by adding an hastag “#” to your tweet. Because of the usage of Twitter, it is a perfect source of data to determine the current overall opinion about anything.
Resources
In order to facilitate the pre­processing part of the data, we introduce five resources which are,
● An ​emoticon dictionary​ regrouping 132 of the most used emoticons in western with their sentiment, negative or positive.
● An ​acronym dictionary​ of 5465 acronyms with their translation.
● A ​stop word dictionary​ corresponding to words which are filtered out before or after
processing of natural language data because they are not useful in our case.
● A ​positive and negative word dictionaries g​ iven the polarity (sentiment out­of­context) of words.
● A ​negative contractions and auxiliaries dictionary​ which will be used to detect negation in a given tweet such as “don’t”, “can’t”, “cannot”, etc.

<img width="485" alt="Screenshot 2023-05-20 at 11 27 04 PM" src="https://github.com/yashshukla20/twitter-mawkishness-analysis/assets/127749722/50310bd7-69af-4bcd-a94b-da3c8ee44db3">

<img width="485" alt="Screenshot 2023-05-20 at 11 27 04 PM" src="https://github.com/yashshukla20/twitter-mawkishness-analysis/assets/12<img width="576" alt="Screenshot 2023-05-20 at 11 27 58 PM" src="https://github.com/yashshukla20/twitter-mawkishness-analysis/assets/127749722/6039e855-161f-49a6-8769-a699033b285e">
7749722/803ac7ac-2666-473c-adc9-7b204f9e2fd7">

<img width="955" alt="Screenshot 2023-05-20 at 11 27 37 PM" src="https://github.com/yashshukla20/twitter-mawkishness-analysis/assets/127749722/ab9062f4-66dd-47db-9a2a-4eda965fb712">

<img width="558" alt="Screenshot 2023-05-20 at 11 28 12 PM" src="https://github.com/yashshukla20/twitter-mawkishness-analysis/assets/127749722/75f5239d-7a01-412b-80fe-cc888af463b6">
