# Driver churn prediction

Predict which drivers at a ride-hailing company are likely to leave, so retention effort can be targeted.

## What's inside

- Exploratory analysis of driver demographics, tenure, ratings, income and business value
- KNN imputation for missing values, feature engineering from monthly records, encoding and standardisation
- Class-imbalance treatment with imbalanced-learn
- Decision tree baseline, then bagging and boosting ensembles (scikit-learn, XGBoost)
- Feature importance and recommendations for the business

## Files

- `driver_churn.ipynb` — full analysis and modelling
- `driver_churn.pdf` — rendered notebook

Libraries: pandas, scikit-learn, XGBoost, imbalanced-learn, seaborn.
