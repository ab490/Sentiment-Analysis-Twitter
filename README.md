# Sentiment-Analysis-Twitter
ChatGPT has been a major talk in the world and is in the news quite often. Sentiment Analysis is done on tweets to identify the sentiments of people towards chatGPT. The data available on Kaggle is used to create this machine learning model. The different sentiments identified include positive sentiment, negative sentiment and neutral sentiment. Different classifiers are used to see which classifier gives the best model accuracy.

## Dataset
https://www.kaggle.com/datasets/khalidryder777/500k-chatgpt-tweets-jan-mar-2023
<br> The dataset consists of information on 500,000 tweets related to the topic of chatGPT collected from Jan 2023 to March 2023.

## Data Cleaning and Preprocessing
- The data consists of various redundant information like date, username, id. All these columns are dropped. 
- Regex function is used to remove special characters in the content of tweets and PorterStemmer is used for stemming.
- TextBlob is used for calculating polarity and sentiment.

<img src="/images/Capture.JPG" width="500">

## Visualization
<img src="/images/Capture1.JPG" width="500"><br>
<img src="/images/Capture2.JPG" width="500"><br>
<img src="/images/Capture3.JPG" width="600"><br>
<img src="/images/Capture4.JPG" width="600"><br>
<img src="/images/Capture5.JPG" width="600"><br>

## Model
The data is trained on 2 models - 
<br> (i) Logistic Regression
<br> (ii) Support Vector Machine (SVM)

### 1. Logistic Regression
Test accuracy: 85.98%

After hyperparameter tuning
<br> Test accuracy: 86.89%

Classification Report: <br>
<img src="/images/Capture6.JPG" width="500"><br>

Confusion Matrix:<br> 
<img src="/images/Capture7.JPG" width="500"><br>

### 2. Support Vector Machine (SVM)
Test accuracy: 87.92%

After hyperparameter tuning
<br> Test accuracy: 88.04%

Classification Report:<br>
<img src="/images/Capture8.JPG" width="500"><br>

Confusion Matrix: <br>
<img src="/images/Capture9.JPG" width="500"><br>

## Conclusion
- Hyperparameter tuned SVM gives best model accuracy.
- Most of the people feel positive about chatGPT.






