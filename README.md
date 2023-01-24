# Twitter-Sentiment-Anaylsis-A-case-study-from-Automotive-Industry
Final Project(IronHack Bootcamp)
## Project Brief/Summary
The aim of this project is to collect,analyze and finally to build a model to predict sentiments from Twitter data related to different automobile brands using SNScraper.
## Data Collection
Nearly 45K tweets has been extracted from October 22 till December 22 by using maximum limit of 500 tweets/day. 
- the tweets are in English (lang:en)
- the tweets contain the following keywords:Tesla, Mercedes, BMW, Audi
## Preprocessing and Visualization
Before creating models and visualizing data preprocessing has been applied
-Converting text to lowercase
-Removing stopwords, punctuation, URLs, retweet mark (RTs), and username handles (@user)
-Spelling correction
-Tokenizing strings
-Removing emojis / 
-Performing stemming / lemmatization
After preprocessing positive, negative and neutral sentiments has been isolated and analyzed deeply using Trigram Anaylsis. 
Most important 10 topics have been discovered after using LDA(topic Modelling) technique
## Twitter Sentiment and Stock price 
In order to find out any relationship b/w twitter sentiment values and stock price a granger causaulity test has been done only for Tesla. Stock price of Tesla has been collected from yahoo finance and mean of twitter sentiment value has been used for the analysis.
## Modelling
I0 baseline models have been selected. 4 best models from these 10 models have been chosen for hyper-parameter tuning(train/Validation). The best performing model was Support Vector Classifier. 
