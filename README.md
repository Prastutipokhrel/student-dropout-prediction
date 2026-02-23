#  Student Dropout Prediction
Predicting university student dropout risk using Logistic Regression

##  Results
| Metric | Score |
|---|---|
| Accuracy | 87.34% |
| AUC-ROC | 0.9272 |
| F1-Score | 0.8082 |
| CV AUC-ROC | 0.9148 ± 0.011 |

##  Key Findings
- 2nd semester approved courses is the strongest predictor of dropout
- Students with up-to-date tuition fees are significantly less likely to drop out
- Model identifies at-risk students with 92.7% AUC ranking ability

##  Tech Stack
Python · Pandas · Scikit-learn · Matplotlib · Seaborn

##  Dataset
UCI Higher Education Student Dropout Dataset (4,424 students, 36 features)
Source: https://archive.ics.uci.edu/dataset/697

##  Project Structure
- Data loading & quality check
- Exploratory Data Analysis (EDA)
- sklearn Pipeline with StandardScaler
- Logistic Regression with 5-Fold Cross Validation
- Evaluation: Confusion Matrix, ROC Curve, Probability Distribution
- Feature Importance & Odds Ratios
```
