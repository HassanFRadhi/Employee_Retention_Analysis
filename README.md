# Employee Retention Analysis and Prediction
## Overview

The goal of this project was to analyze employee data and build a machine learning model to predict whether an employee would leave Salifort Motors. The project focused on identifying the factors that may be associated with employee turnover and using these findings to provide recommendations for improving employee retention.
The final logistic regression model achieved 83% accuracy and 80% precision in predicting employee turnover.
Based on the model, department, salary, and promotions last 5 years were the most important factors in predicting whether an employee would leave the company.

## Business Understanding

Salifort Motors is a fictional French-based alternative energy vehicle manufacturer with a global workforce of more than 100,000 employees.
The company is facing a high employee turnover rate. This creates significant costs because Salifort invests time and money in recruiting, training, and developing its employees.
For this reason, the main business problem of this project was to identify the factors associated with employee turnover and build a model that can help predict whether an employee is likely to leave the company.

## Data Understanding
The data used in this project contained information about Salifort Motors employees, including factors such as department, job title, number of projects, average monthly hours, satisfaction level, and other employee-related information.
The dataset contained approximately 14,999 rows and 10 features. For more information about the data, refer to its source on [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv).
During the data preparation process, columns renamed, missing values and duplicates checked, and outliers were imputed.
Some features were transformed to help improve the model and better represent factors that may influence employee turnover.

## Modeling and Evaluation

A logistic regression model was used to predict whether an employee would leave the company.

The model achieved:

- **Accuracy:** 83%
- **Precision:** 80%
- **Recall:** 83%
- **F1-score:** 80%

The results showed that department, salary, and promotions last 5 years were the most important factors in predicting employee turnover. <br> <br>
<img width="869" height="837" alt="image" src="https://github.com/user-attachments/assets/2a8099d0-1292-4cd5-a018-6248b2bd81c4" />

These findings helped identify the main patterns associated with employees leaving the company.

## Conclusion

This project showed that average monthly hours and number of projects has an important relationship with employee turnover.
The model can help Salifort Motors identify employees who may be at higher risk of leaving and better understand the factors that contribute to turnover.
Based on the results, the main recommendations for the company are that the company modifies its policies in a way that minimize the effects mentioned in the above figure. And to seek for increasing fairness between different
departments since some departments tend to have higher turnover rate than others.
In the future, we can develop an XGBoost or Random Forest model to increase the relainess
of the predictions. Further feature engineering could also be used to improve the model and provide more useful insights for the company's employee retention strategy. 
