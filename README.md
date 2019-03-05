# creditcardFD
A Data science project implemented using Python and R to enable credit card companies to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase by comparing various machine learning algorithms

Problem Statement:
To enable credit card companies to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

70/30 train test split
Create a Balanced Dataset:
As data is imbalanced, the data set is balanced by performing oversampling of under represented class and under-sampling  of over represented class
-SMOTE
-ROSE

Insights:
Logistic regression outperformed the SVM, decision tree, neural network. 

SVM was next, but as there are lot of features and hence cannot visualize the hyperplane separation, proper choice of kernel and parameters are required by tuning

As the value of true positive is very low in Neural networks leading to problems like overfitting in neural networks  which prevents better accuracy in Neural networks. 
