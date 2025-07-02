# Data Science Internship
## Task 3: Bank Marketing Decision Tree Classifier
![Screenshot](Task3.png)
## Introduction
In this task, I built a Decision Tree Classifier using the Bank Marketing dataset to predict whether customers will subscribe to a term deposit, based on their demographic and behavioral data. The model achieved an accuracy of **87.6%**, though class imbalance affected predictions for the positive class.
## Dataset

This project uses the [**Bank Marketing dataset**](https://archive.ics.uci.edu/ml/datasets/bank+marketing), which contains 45,211 records and 17 features. The data includes customer demographics, account information, and details of previous marketing interactions, helping predict whether a customer will subscribe to a term deposit (`y` variable).

## Task Description

The goal of this task is to build a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit. The model uses demographic and behavioral features from the Bank Marketing dataset and is evaluated based on accuracy, classification metrics, and visualizations.
## Analysis Highlights

- Achieved an overall accuracy of **87.6%** on the test set.
- The model predicts the majority class well, but performance is lower for customers who subscribed due to class imbalance.
- Visualizations, including the decision tree plot and confusion matrix, help interpret the model’s decisions.
## Conclusion:
The model demonstrated strong overall performance with an accuracy of 87.6%, effectively predicting the majority class. However, due to class imbalance, its ability to identify customers who subscribed is less accurate. Visual tools like the decision tree and confusion matrix provided valuable insights into the model’s decision-making process, highlighting areas for potential improvement in handling minority classes.
