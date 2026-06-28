# Bank Marketing Subscription Prediction

## Project Overview
Briefly explain the business problem.

## Business Objective
Predict whether a customer will subscribe to a term deposit so banks can improve marketing campaigns.

## Dataset
- Source: UCI Bank Marketing Dataset
- Records: 45,211
- Features: 16 (before encoding)

## Project Workflow
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Encoding
- Scaling (for Logistic Regression)
- Model Training
    - Random Forest
    - Balanced Logistic Regression
- Model Evaluation
- Business Conclusion

## Results

| Model | Accuracy | Precision | Recall | F1 | AUC |

| Random Forest | 90.5% | 0.68 | 0.39 | 0.50 | 0.93 |

| Balanced Logistic Regression | 84.2% | 0.42 | 0.83 | 0.56 | 0.91 |

## Business Conclusion
Random Forest achieved the highest overall accuracy, while Balanced Logistic Regression detected significantly more potential subscribers due to its higher recall.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
