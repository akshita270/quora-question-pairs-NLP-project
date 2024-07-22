The primary objective of this project is to determine whether two given questions are semantically similar, even if they are phrased differently. This involves developing a model that can accurately identify pairs of questions that convey the same meaning.

Dataset Link - https://www.kaggle.com/c/quora-question-pairs

Steps Involved:
Data Collection:
Obtain a dataset containing pairs of questions with labels indicating whether they are duplicates or not. The Quora Question Pairs dataset is a popular choice for such tasks.

Data Preprocessing:

Text Cleaning: Remove special characters, numbers, and stopwords. Convert text to lowercase.
Tokenization: Split text into individual words or tokens.
Lemmatization/Stemming: Reduce words to their base or root form.
Feature Engineering:

Basic Features: Length of questions, number of common words, etc.
Advanced Features: TF-IDF vectors, word embeddings (Word2Vec, GloVe), or contextual embeddings (BERT).
Modeling:

Machine Learning Models: Rndom forest and  XGBoost using engineered features.

Evaluation:

Split the data into training, validation, and test sets.
Use metrics like accuracy, precision, recall, F1-score, and AUC-ROC to evaluate model performance.
