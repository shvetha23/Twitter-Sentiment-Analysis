# Twitter-Sentiment-Analysis

## Description ##
Sentiment analysis plays a huge role in understanding a user's opinion on a commodity, an event, etc. Given twitter data sets containing tweets from Obama's and Romney's election, we analyse the sentiments of the general public and predict the sentiment of the test tweet.The classes are labeled as +1 for a positive , -1 for a negative and 0 for a neural opinion. Pre-processing involved removal of stop-words stemming and removal of other unnecessary data.The testing was performed on various classifiers which included Logistic Regression, Linear SVM, K-Nearest Neighbors ,Random Forest and a Voting Classifier (10-fold cross validation). Our results showed that the soft voting classifier achieved the best precision, recall and F1-score for the positive and negative class.

## Libraries Used ##
* Numpy
* SciPy
* nltk
* sklearn

## Files ##
This data was testing using the following Models
* Naive Bayes
* Linear SVM
* Logistic Regression
* Voting Classifier
* K-Nearest Neighbours


## Experiment ##
1. Run the files using Jupyter notebook and include the necessary dependencies. 
2. The output will display the Overall Accuracy, Precision, Recall, F1-Score

## References ##
http://scikit-learn.org/stable/user_guide.html
