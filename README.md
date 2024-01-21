---
Title: Predict Term Deposit Using Dataiku
Author: Rahat, A.D. and Sultana, Tania
Date: January 18th, 2024
---


### Introduction
This project, "Predict Term Deposit Using Dataiku," aimed to utilize Dataiku's data science platform to predict whether clients of a banking institution would subscribe to a term deposit. It involved univariate analysis of individual features to understand their impact and the creation of a structured workflow for data processing and model evaluation. The dataset was split into training (70%) and testing (30%) sets to train and assess three different machine learning models: Logistic Regression, Support Vector Machine (SVM), and Random Forest. Model performance was evaluated using metrics like Accuracy, Precision, Recall, F1-Score, and ROC AUC both on training and test data.

### Machine Learning Pipeline

![grafik](https://github.com/AhmedDiderRahat/predict_term_deposit/assets/23084348/8101e4fb-e7e2-46ed-9e5e-44645423792a)

### Model Comparison

#### On training dataset:

| Model                    | Accuracy | Precision | Recall | F1-Score | ROC AUC |
|--------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression      |    86%   |     38%   |   38%  |   38%    |   74.2% |
| Support Vector Machine   |    84%   |     37%   |   50%  |   43%    |   76.5% |
| Random Forest            |    84%   |     35%   |   46%  |   40%    |   76.1% |


#### On teat dataset:

| Model                    | Accuracy | Precision | Recall | F1-Score | ROC AUC |
|--------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression      |   86.0%  |   39.4%   |  39.4% |   39.4%  |   76.1% |
| Support Vector Machine   |   84.8%  |   38.5%   |  52.3% |   44.3%  |   78.0% |
| Random Forest            |   83.5%  |   35.0%   |  49.1% |   40.9%  |   78.0% |



### Conclusion
The comparative analysis of the three models indicated that the Support Vector Machine (SVM) displayed a notable improvement with the highest ROC AUC of 78% on test data, suggesting its strong predictive power. Although Logistic Regression maintained consistent accuracy, the precision and recall for SVM and Random Forest indicated a more balanced trade-off between identifying positive cases and the accuracy of those identifications. 
