# Loan Prediction Project - High-Recall Model for Financial Risk Assessment

![Loan Prediction](images/loan_prediction.png)  <!-- Optional: add a screenshot or visualization -->

## Project Overview
This project aims to **predict loan approvals** using Machine Learning while minimizing the risk of rejecting eligible applicants.  
The focus is on developing a **Logistic Regression model** capable of handling **class imbalance** and achieving a high **Recall** for approved loans (Class 1).  

## Key Features
- **Data Preprocessing:** Handling missing values, encoding categorical variables, feature scaling.  
- **Data Visualization:** Exploring class distributions and feature correlations to understand patterns in the dataset.  
- **Modeling:** Logistic Regression with `class_weight='balanced'` to address class imbalance.  
- **Evaluation:** Confusion Matrix, Classification Report, and key metrics (Precision, Recall, F1-score).  
- **Insights:** Reducing false negatives for approved loans to mitigate financial risk.

## Performance (Test Data)
| Metric                | Value |
|-----------------------|-------|
| Recall (Class 1)      | 0.90  |
| Precision (Class 1)   | 0.83  |
| F1-Score (Class 1)    | 0.86  |
| True Positives        | 72/80 |

## Technologies Used
- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn (Visualization)  
- Scikit-learn  
```bash
git clone https://github.com/Marwan252/Loan-Prediction-project.git
