# SupervisedLearning-Regression-LogisticRegressionWithMultipleVariable
This repository consists of implementation of logistic regression machine learning algorithm with multiple variables.

Machine Learning concept being worked on:

1. Logistic regression machine learning algorithm falls under supervised learning
2. Logistic regression, although the names says that it is a regression algorithm, it falls under the classification category.
3. In logistic regression, the data set that we process will have a set of features in each example along with a label. The value of label will be discrete instead of real / continous value.
3. In logistic regression algorithm, we will learn a model. Based on the examples in the given dataset we will be able to predict the value of label (which will be discrete)
4. Examples of the problems that logistic regression machine learning algorithm attempts to targets are 
        a. The Trauma and Injury Severity Score
        b. To predict the risk of developing a given disease, based on observed characteristics of the patient
        c. To predict whether an Indian voter will vote BJP or Trinamool Congress or Left Front or Congress
        d. It can be used to predict the likelihood of a person's choosing to be in the labor force

In this example we will perform logistic regression to classify whether a customer will purchase or will not purchase. For this we learn a model based on the data provided about the customers, given their age and estimated salary.

Dataset being used: social_network_ads.csv
Feature being used: Age, EstimatedSalary
Label being predicted: Purchase
Python modules being used:

os: This module provides a portable way of using operating system dependent functionality.
pandas: Pandas provide high-performance data manipulation and analysis tool using its powerful data structures.
numpy: NumPy is the fundamental package for scientific computing with Python.
matplotlib: matplotlib is a plotting library for the Python programming language.
sklearn: It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN
