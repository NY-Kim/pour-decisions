# Pour Decisions
The objective of this project is to predict wine rating based on its review. The final report for the project can be viewed in _report.pdf_.

## Data
Data folder contains train, val, and test data that are preprocessed. 
Stop words and punctuations are removed, and words are lemmatized.

## Baseline
Baseline folder contains source code of baseline model. 
_length.py_ computes the accuracy based by training a linear model using the length of wine reviews

## Naive Bayes
Naive Bayes foler contains source code for Naive Bayes model.
1) _naivebayes.py_: you can specify in the code so that you can run NB with word-count or tf-idf and its n-gram.

## RNN
The code and instruction to run it is included in https://github.com/kimny817/allenNLP.git

## Wordvec
Wordvec folder contains source code for 2 wordvec models:
1) _concat.py_: concatenates the word vector of words in each wine review to train model.
2) _average.py_: averages the word vector of words in each wine review to train model.
3) _weighted_average.py_: uses word2vec to calulate word embeding for the words in the reviews and uses 
and average embedings of a review fed into a random tree classifer to predict the score of a review

## Feature analysis
Feature Analysis folder contains the data and source code for feature analysis
