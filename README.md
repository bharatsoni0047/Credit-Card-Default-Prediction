# Credit-Card-Default-Prediction
![image](https://github.com/bharatsoni0047/Credit-Card-Default-Prediction/assets/111848240/6878096f-43ea-45e8-b326-dcde24c6486b)

Predicting whether a customer will default on his/her credit card

This project is aimed at predicting the case of customers default payments in Taiwan.From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

Started with the logistic regression model, then compared the results with traditional machine learning-based models. Then K-means SMOTE resampling method on Taiwan client’s credit dataset.

Data Read & Handle Missing Values

Data Preprocessing

Eploratory Data Analysis

Detecting outliers in dataframe

Feature Engineering

Label and One Hot Encoding

Applying SMOTE (Synthetic Minority Oversampling Technique)


MODEL IMPLEMENTATION-

Model1. Logistic Regression

Model2. Random Forest Classifier

Model3. K-Nearest Neighbour Classifier

Model4. Support Vector Classifier

Best models are Random Forest and K-Neighbor Classifier as they have the best Precision, Recall, ROC_AUC and F1 score values. 
This being an imbalanced dataset, Recall will be most important metric as we don't want to classify a defaulter as a non defaulter so that makes K Neighbor Classifier model more suitable for the task.


