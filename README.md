# MachineLearning

First of all, we train the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. Next, I test the model on 260 emails. After predicting the category of those emails, I compare the accuracy with correct classification that we already know.

Part 1: Cleaning and preparing the data 

There are two folders test-mails and train-mails. I will use train-mails to train the model.In cleaning, we remove the non required words, expressions and symbols from text.After cleaning what I need from every email document, I should have some matrix representation of the word frequency.

Part 2: Naive Bayes Classification Algorithm
Steps as following: 
-Train a Gaussian Naive Bayes classifier with imported library 
-Predict on test data 
-Evaluate the performance of classifier 
