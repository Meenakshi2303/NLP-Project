# NLP-Project
# IMDb Movie Review Sentiment Analysis

This project performs **sentiment analysis on IMDb movie reviews** using NLP and Machine Learning.
The dataset contains **50,000 balanced reviews** labeled as Positive or Negative.
Text preprocessing includes cleaning, tokenization, stopword removal (keeping *“not”*), and lemmatization.
Features are extracted using **TF-IDF (10,000 features)** along with basic text statistics.
Additional numerical features include review length, word count, character count, and average word length.
Multiple models were trained: Logistic Regression, Random Forest, and SVM.
**Logistic Regression** performed best after hyperparameter tuning.
The final model achieved **89.29% accuracy** on unseen test data.
Model performance was evaluated using precision, recall, F1-score, and confusion matrix.
The system can predict sentiment for **new user-entered movie reviews**.
