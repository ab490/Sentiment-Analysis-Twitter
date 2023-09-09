# Sentiment-Analysis-Twitter
ChatGPT has been a major talk in the world and is in the news quite often. Sentiment Analysis is done on tweets to identify the sentiments of people towards chatGPT. The data available on Kaggle is used to create this machine learning model. The different sentiments identified include positive sentiment, negative sentiment and neutral sentiment. Different classifiers are used to see which classifier gives the best model accuracy.

## Dataset
https://www.kaggle.com/datasets/khalidryder777/500k-chatgpt-tweets-jan-mar-2023
<br> The dataset consists of information on 500,000 tweets related to the topic of chatGPT collected from Jan 2023 to March 2023.

## Data Cleaning and Preprocessing
- The data consists of various redundant information like date, username, id. All these columns are dropped. 
- Regex function is used to remove special characters in the content of tweets and PorterStemmer is used for stemming.
- TextBlob is used for calculating polarity and sentiment.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## Visualization

## Model
The data is trained on 2 models - 
<br> (i) Logistic Regression
<br> (ii) Support Vector Machine (SVM)

### 1. Logistic Regression
Test accuracy: 96.93%

After hyperparameter tuning
<br> Test accuracy: 97.19%

Confusion Matrix: 

### 2. Support Vector Machine (SVM)
Test accuracy: 

After hyperparameter tuning
<br> Test accuracy: 

Confusion Matrix: 

## Conclusion
- Hyperparameter tuned SVM gives best model accuracy.
- Most of the people feel positive about chatGPT.






