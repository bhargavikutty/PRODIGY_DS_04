# PRODIGY_DS_04
PRODIGY_INFOTECH_TASK-4
About Dataset : 
Twitter Sentiment Analysis
This project focuses on sentiment analysis of tweets using a machine learning model. Given a tweet and an entity mentioned in the tweet, the task is to classify the sentiment of the tweet towards that entity into one of three classes: Positive, Negative, or Neutral.

Dataset
The dataset used in this project is from Kaggle: Twitter Entity Sentiment Analysis. It contains tweets labeled with the sentiment towards a specific entity mentioned in the tweet.

The dataset is split into two files:

twitter_training.csv: Contains 74,681 labeled tweets for training the model.

twitter_validation.csv: Contains 999 labeled tweets for validating the model.

Approach

Data Preprocessing: The text data is cleaned by removing punctuation, converting to lowercase, and removing stopwords.

Feature Extraction: The cleaned text is converted into numerical features using TF-IDF vectorization.

Model Building: A Random Forest Classifier is trained on the vectorized training data.

Evaluation: The trained model is evaluated on the validation dataset, and classification metrics such as precision, recall, F1-score, and accuracy are reported.

Results :
The model demonstrates high precision, recall, and F1-scores for all sentiment classes, with an overall accuracy of 0.97 on the validation dataset.
