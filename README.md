Project Overview:
<br>
This project implements sentiment analysis on IMDb movie reviews using Naïve Bayes classifiers. The model classifies reviews as positive (1) or negative (0) based on textual features extracted using Natural Language Processing (NLP) techniques.
<br>
<br>
Features:
<br>
1. Preprocesses IMDb movie reviews (removes HTML tags, special characters, stopwords, and applies stemming)
2. Converts text into numerical representation using Bag of Words (BoW).
3. Trains and compares three Naïve Bayes classifiers: GaussianNB, MultinomialNB, and BernoulliNB.
4. Evaluates model performance using accuracy metrics.
5. Predicts sentiment of new reviews and saves the trained model using pickle.
<br>
<br>
Technologies Used:
<br>
1. Python
2. Pandas, NumPy
3. Natural Language Toolkit (NLTK)
4. Scikit-Learn (sklearn)
5. Regular Expressions (re)
6. Pickle (for model persistence)
<br>
