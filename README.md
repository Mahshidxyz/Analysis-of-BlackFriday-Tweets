# Capstone Project 2: Exploring Black Friday Tweets  
My second capstone project at the Springboard bootcamp  

### Data

Size:  ~110 GB json
Data source: I collected the tweets through Twitter streaming API from Nov 8 to Dec 1, 2017. I tracked the followings: blackfriday, blackfriday2017, cybermonday, cybermonday2017, blackfridayshopping, blackfridaydeals, cybermondaydeals. I saved the tweets in json format.
After initial processing and selecting the needed attributes, data was saved in two separate datasets: tweets and retweets. The size of the tweet dataset is ~ 570 MB and the size of the retweet dataset is ~ 1.4 GB. The clean datasets with no duplicates include ~1.7 million tweets and ~2.9 million retweets.

Why twitter and Black Friday? Defining this project and working on it gave me the opportunity to collect a very large and rich dataset. I chose Twitter and Black Friday Shopping because of my personal interest in the applications of Data Science in social media, business and marketing.


### Workflow
For more information please see the corresponding notebook to each step and the final slide deck.

* Collecting the data & breaking down the large (up to 19 GB) json files to processable pieces
* Data Mining: Selecting the needed attributes from the tweet dictionaries and building the tweets and retweets dataframes
* Time Studies - Exploratory Data Analysis (EDA): Change in the tweet volume by time & the netneutrality spike
* Hot Topics (EDA): Most frequent hashtags and user mentions  
* Sentiment Analysis: Tweet Dataset, Apple vs Samsung 
* Machine Learning – Linear Regression: Correlation between the number of followers and other accounts features  

### Slide Deck
See this file: Exploring_Twitter_BlackFriday.pptx

