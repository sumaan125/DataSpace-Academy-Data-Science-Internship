# Customer Churn Prediction using ANN

**Notebook:** [Churn_Prediction_using_ANN.ipynb](Churn_Prediction_using_ANN.ipynb)
**Data:** `Churn_Modelling.csv` (10,000 bank customers; target `Exited`)

## Workflow
1. Drop non-predictive columns (`RowNumber`, `CustomerId`, `Surname`)
2. Encode categorical features (Geography, Gender)
3. Train/test split and `StandardScaler`
4. Model: 11 inputs, Dense(6, ReLU), Dense(6, ReLU), Dense(1, sigmoid)
5. Compile with Adam and binary cross-entropy; train with a validation split
6. Evaluate: **~84% accuracy** on 2,000 test samples
