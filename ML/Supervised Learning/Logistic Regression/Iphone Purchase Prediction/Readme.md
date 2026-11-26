# iPhone Purchase Prediction using Logistic Regression

**Notebook:** [Logistic_Regression.ipynb](Logistic_Regression.ipynb)
**Data:** `iphone_purchase_records.csv` (399 records: Gender, Age, Salary, Purchase Iphone)

## Workflow
1. Load and inspect data
2. Encode Gender (Male/Female to 0/1)
3. Train/test split and feature scaling (`StandardScaler`)
4. Fit `LogisticRegression`
5. Evaluate with accuracy score and confusion matrix (**~85% accuracy**)
