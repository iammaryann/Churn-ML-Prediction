# Churn-ML-Prediction


![image](https://github.com/iammaryann/Churn-ML-Prediction/assets/169622423/0f42bdec-7ddf-40d5-acc1-b131fb8290c1)



## Table of Contents
- [Project Objective](#Project-Objective)
- [Data Sources](#Data-Sources)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Preprocessing](#Data-Preprocessing)
- [Machine Learning Model](#Machine-Learning-Model)
- [Evaluation Metrics](#Evaluation-Metrics)
- [Conclusion](#Conclusion)

## Project Objective
The aim of this project is to build a machine learning algorithm that is able to predict customers within a business that will churn (customers that will stop patronising or purchasing a company's products or services within a specified period of time) thereby minimising customer churn risk as much as possible.

## Data Sources
The dataset used for this project was provided by 10alytics. It consists of 21 features related to telecommunications and includes the churn feature (indicates whether or not a customer has churned).

## Exploratory Data Analysis
After extraction of the data, it was analysed and cleaned. Univariate, bivariate and multivariate analysis was carried out during which new features were created to develop more insight into the data.

## Data Preprocessing
Feature engineering was carried out to prepare the data and make it suitable to be used to train and build the machine learning model. One-hot encoding method was used to transform the categorical data, afterwhich the data was segmented and scaled using the standard method for classification.

## Machine Learning Model
The churn detection model was trained and built using a supervised machine learning process. The proportion of data for the training and testing was 80:20. Three machine learning models were trained;
-**Logistic Regression**
-**Random Forest**
-**Decision Tree Classifier**
After testing and evaluation, the most accurate model with the least number of Fals Negatives was selected to be used for the project.

## Evaluation Metrics
The evaluation of the models was carried out using the following metrics;
-**Accuracy:** is the total number of correctly predicted instances in the dataset (churned or not churned customers)
-**Precsion:** the total number of correctly predicted customers that will churn out of all the correctly predicted churn instances of customers by the model.
-**Recall:** is the proportion of correctly predicted customers that will churn out of all the actual churned customers.
-**F1 Score:** the mean of precision and recall. it provides a balance metric evaluation.
-**AUC-ROC:** measures the ability of the model to distinguish between instances of churn and not churned customers across all the instances in the dataset.
-**Confusion Matrix:** visualises the true negatives (TN), true positives (TP), false negatives (FN), and false positive (FP)instances in the dataset.

## Conclusion
The use of supervised machine learning model was able to predict the customer churn for the purpose of this project. Out of the three models adopted, the Logistic Regression model emerged as the most effective in predicting customers that will churn or not churn according to the dataset. it had the following evaluation metric results; Accuracy: 79.7%, Precision: 62.9%, Recall: 53%, F1 Score: 57.6%, and AUC-ROC: 71%. While Confusion Matrix had; 926 True Negatives (TN), 115 True Positives (TP), 171 False Negatives (FN), and 195 False Positives (FP)
For the purpose of this project,the focus is on the 'FN' which shows the total number of innacurate instances of customers that will not churn. This is because, it gives the percentage or number of customers that will potentially be lost. Logistic Regression had the least number of False Negatives out of all the other models therefore, making it the most effective to reduce the risks to the barest minimum for the target organisation in this project.



