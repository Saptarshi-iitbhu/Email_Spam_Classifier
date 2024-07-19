# Email Spam Classifier

## Description
This model implements a machine learning model for classifying emails as spam or legitimate (ham) using the Naive Bayes classification algorithm. Naive Bayes is a popular choice for text classification due to its simplicity and efficiency.

Data preprocessing is one of the critical steps in any machine learning project. It includes cleaning and formatting the data before feeding into a machine learning algorithm. For NLP, the preprocessing steps are comprised of the following tasks :

1. Tokenizing the string
2. Lowercasing
3. Removing stop words and punctuation
4. Stemming

## Features
* Trains a Naive Bayes model on a labeled dataset of emails.
* Preprocesses emails for feature extraction, including:
  * Text cleaning (removing punctuation, stop words, etc.)
  * Feature engineering (e.g., word frequency, presence of specific keywords)
* Classifies new, unseen emails as spam or ham based on the trained model.
* Provides performance metrics such as accuracy, precision, recall, and F1-score.
  
