# SMS-Spam-Detection-Using-Machine-Learning
A simple SMS spam detection project using TF-IDF vectorization and a Multinomial Naive Bayes classifier and a logistic regressor and compared their recall.  
Includes data preprocessing, model training and evaluation

## Project overview

This project demonstrates a classic text classification pipeline:

1. Load and inspect SMS dataset (`spam.csv`).
2. Preprocess text: lowercase, remove punctuation, remove stopwords.
3. Convert text to numeric features using TF-IDF.
4. Train a `MultinomialNB` classifier and a Logistic regressor.
5. Evaluate using accuracy, precision, recall and confusion matrix.
