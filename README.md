RMKMavericks@DravidianLangTech 2025

Title: Emotion Mining in Tamil and Tulu Code-Mixed Text: Challenges and Insights

Authors: Gladiss Merlin N.R, Boomika E, Lahari P

Affiliation: R.M.K. Engineering College, Tiruvallur

Overview
This study explores sentiment analysis in code-mixed Tamil-English and Tulu-English social media texts. Due to irregular grammar, frequent code-switching, and non-standard scripts, traditional sentiment analysis techniques struggle with such data. We employ pre-processing techniques and machine learning models to address these challenges.

Dataset:

* Languages: Tamil-English and Tulu-English code-mixed texts
* Sources: Social media comments and posts
* Classes: Positive, Negative, Neutral sentiments
* Challenges: Class imbalance, linguistic variations, and non-native scripts

Methodology:

* Preprocessing:
  * Tokenization and normalization
  * Removal of punctuation and unnecessary characters
  * Text vectorization using TF-IDF (Term Frequency-Inverse Document Frequency)
* Models Used:
  * Logistic Regression (LR): Trained using the ‘liblinear’ solver for small datasets
  * Support Vector Machine (SVM): Evaluated with different kernels (Linear & RBF)
 
* Hyperparameter Tuning: GridSearchCV for optimizing performance.
Hyperparameter Tuning: GridSearchCV for optimizing performance
