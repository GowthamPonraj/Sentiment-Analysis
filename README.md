# Sentiment-Analysis
sentiment analysis is basically a machine learning model which classifies the document , be it amazon reviews or tweets or youtube comments or whatsapp chat into postive , neagative or neutral sentiments.

this code is splitted into to two parts .
1st part - analyzing data from .csv file
2nd part - analyzing live data from twitter 

u understand the modules fromthe #comments which will be given for all modules

ANALYZING DATA FROM .csv FILE :
1) for this u just have to pass the .csv file to it
2) the .csv file used here is from https://www.kaggle.com/datasets/gpreda/all-covid19-vaccines-tweets (or) if u want to scarpe live data from amazon then go to amazon review page -> copy the url -> pass the url to web scrapping code given in this repository
3) while passing ur scrapped .csv file , set the the target attribute and related data frames head in the sentiment analysis code

ANALZING LIVE DATA FROM TWITTER:
1) for this we will be using tweepy API
2) u need an twitter api v2 developer's account key credentials ( probably the keys in my code wont work for u , because i would have regenarated by the time u see it )
3) for applying v2 developer account https://developer.twitter.com/en
4) then pass those keys to consumer keys and all respected keys
5) atlast , u just have to pass the tweet topics within " " . it will take first 100 recent tweets from that topic and performs sentiment analysis for u 
