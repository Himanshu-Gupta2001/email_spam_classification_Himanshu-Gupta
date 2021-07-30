# Email-Classification
It's very easy to build a ML model which works well on training data, but is it the case for test data?
This project is done for learning purposes. It aims to test a ML model on real Gmail emails to evaluate it's accuracy. We first build the model and then we extract
our "NORMAL" emails from our inbox and then we feed the built model with them to know if he gonna classify them as spams (which means our model is bad) or normal
(which mean our model is very good). If you want you can run the same test on your spam inbox.

![project](https://user-images.githubusercontent.com/24523745/87186436-c9627f00-c2eb-11ea-98ac-0b4591253904.png)

# Email-Spam-Classifier-Using-Naive-Bayes

Naive Bayes is a supervised classification technique based on Bayes' Theorem with an assumption of independence among predictors. That is, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.

It is a popular technique for text categorization, judging documents as belonging to one category or the other (such as spam or legitimate, sports or politics, etc.) with word frequencies as features.

**Goal:** Previously unseen records should be assigned a class as accurately as possible

* We have a bunch of emails classified as ['spam']
and a bunch of emails classified as ['ham'](not spam)
* The emails are first read and stored in a dataframe. They are then parsed using CountVectorizer.
* This information is used to train the model and its prediction is then tested with a sample input.

**Python Libraries used:** pandas, numpy, io, os, CountVectorizer and MultinomialNB from sklearn.

### Here are the direct links of my files used in this project-
* The dataSet link is attached here(https://github.com/Himanshu-Gupta2001/email_spam_classification_Himanshu-Gupta/blob/main/emailSpam.csv).
* The trainingData link is attached here() which train the data .
* The testingData link is attached here(https://github.com/Himanshu-Gupta2001/email_spam_classification_Himanshu-Gupta/blob/main/testingData.ipynb) which gives the testing result.
* The spamClassifier(https://github.com/Himanshu-Gupta2001/email_spam_classification_Himanshu-Gupta/blob/main/spamClassifier.py) classifies the given input as a spam/ham. 

# Testing Your emails
To test your emails just run the code in jupyter notebook and write your email as a text.
