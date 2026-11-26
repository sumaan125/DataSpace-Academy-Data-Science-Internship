# Median House Value Prediction using ANN

**Notebook:** [Median_House_value_prediction.ipynb](Median_House_value_prediction.ipynb)
**Data:** `housing.csv` (California housing, about 20,640 districts; target `median_house_value`)

## Workflow
1. Check missing values and drop them (`total_bedrooms`)
2. Encode `ocean_proximity`
3. Train/test split and `StandardScaler`
4. Deep network: 12 inputs and 10+ hidden Dense layers of 150 ReLU units, linear output
5. Compile with Adam, loss `mse`, metric `mae`; train 160 epochs, batch size 32, validation split 0.33
6. Evaluate with R2 score and MAPE
