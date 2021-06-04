# Fraud-Detection
Detecting fraudulent transactions with the help of Machine Learning 

The project aims to detect fraudulent transaction. The details regarding the data used for the project can be found here: https://www.kaggle.com/c/fraud-detection-analysis
The data provided was synthetically generated over a period of time. The data consists of over 6 million data points and is heavily imbalanced in nature with only 0.13% points belonging to the positive class (Fraud). 

The project is a demonstration of how thorough analysis and understanding of data can be beneficial especially when paired with excellent ideas from Machine Learning (Random Forest and XGBoost) can do really well and easily combat issues like data imbalance. 

Because of the imbalance in the classes, Recall was chosen as the appropriate metric. 
Following is the interpretation of both recall and precision for the given scenario:

Recall - Out of all the fraudulent points, how many points were correctly clasified as fraud
Precision - Out of all the points that the classifier predicted to be fraudulent, how many of those points were actually fraud

In this case, recall comes out on top. At the end of the project, with some tuning of hyperparameters for both Random Forest and XGBoost, Random Forest performed the best
abd gave a recall score of about 0.996 on the test set.
