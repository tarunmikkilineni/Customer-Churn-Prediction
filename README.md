# Support Ticket Priority Prediction Using Supervised Machine Learning

## Project Overview
This project develops and compares multiple supervised machine learning models to automatically predict the priority level of customer support tickets. The objective is to assist organizations in improving ticket management by accurately classifying tickets into High, Medium, and Low priority categories.

## Dataset
Support Ticket Priority Dataset (50K)

Source:
https://www.kaggle.com/datasets/albertobircoci/support-ticket-priority-dataset-50k

## Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machine (SVM)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | 85.61% |
| Decision Tree | 91.59% |
| Random Forest | 91.22% |
| XGBoost | **97.12%** |
| SVM | 83.65% |

XGBoost achieved the highest classification accuracy.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost
