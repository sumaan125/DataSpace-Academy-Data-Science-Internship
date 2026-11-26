# Placement Package Prediction using Linear Regression

**Notebook:** [Linear_Regression.ipynb](Linear_Regression.ipynb)
**Data:** `placement.csv` (200 students: `cgpa`, `package`)

## Workflow
1. Load data, check nulls, duplicates, shape, statistics
2. Visualise CGPA vs package
3. Train/test split
4. Fit `LinearRegression` and read the slope `m` and intercept `b`
5. Predict with `y = m*x + b` and plot the best-fit line
