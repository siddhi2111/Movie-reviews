Project Overview
<br>
This project implements sentiment analysis on IMDb movie reviews using Naïve Bayes classifiers. The model classifies reviews as positive (1) or negative (0) based on textual features extracted using Natural Language Processing (NLP) techniques.
<br>
Features:
<br>
Preprocesses IMDb movie reviews (removes HTML tags, special characters, stopwords, and applies stemming).
<br>
Converts text into numerical representation using Bag of Words (BoW).
<br>
Trains and compares three Naïve Bayes classifiers: GaussianNB, MultinomialNB, and BernoulliNB.
<br>
Evaluates model performance using accuracy metrics.
<br>
Predicts sentiment of new reviews and saves the trained model using pickle.
<br>
Technologies Used:
<br>
Python
<br>
Pandas, NumPy
<br>
Natural Language Toolkit (NLTK)
<br>
Scikit-Learn (sklearn)
<br>
Regular Expressions (re)
<br>
Pickle (for model persistence)
<br>
