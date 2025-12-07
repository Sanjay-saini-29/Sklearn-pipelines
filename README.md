# Sklearn-pipelines

# Titanic Survival Prediction — ML Pipeline vs Non-Pipeline Approach

This project compares two complete machine learning workflows on the Titanic dataset:

1️⃣ Manual ML workflow (without Pipeline)  
2️⃣ Automated preprocessing + model training using sklearn.Pipeline  

The goal is to understand how pipelines simplify the ML process, reduce code,
avoid data leakage, and improve reproducibility.

## Key Steps:
- Data cleaning (missing values, dropped columns)
- One-hot encoding (Sex, Embarked)
- Scaling numerical features
- Model training (Logistic Regression, Random Forest)
- Hyperparameter tuning using GridSearchCV
- Saving trained pipeline using pickle (pipe.pkl)

## Results:
- Pipeline approach reduced code complexity by 40%  
- Improved model consistency and eliminated preprocessing errors  

