# DataSpace Academy Internship Portfolio

Code, models and analyses from my 8-week Summer Training and Internship on **Data Science** at DataSpace Academy. All work is in Jupyter notebooks (written in Google Colab), each with its dataset next to it.

## Repository Structure

| Folder | Topic | Contents |
|---|---|---|
| [python basic](python%20basic/) | Python fundamentals | Operators, data types, collections, control flow |
| [EDA](EDA/) | Exploratory Data Analysis | 4 notebooks on 8+ datasets |
| [ML](ML/) | Machine Learning | Linear/Logistic Regression, K-Means |
| [DL](DL/) | Deep Learning | ANN (classification, regression) and CNN (images) |
| [Completion certificate from DataSpace Academy](Completion%20certificate%20from%20DataSpace%20Academy/) | Certificate | Project report PDF |

## Learning Path
1. **Python basics**, then 2. **EDA** (NumPy, Pandas, visualisation, statistics), then 3. **Machine Learning**, then 4. **Deep Learning** (capstone: rice image classification)

## Projects at a Glance
| Area | Project | Technique | Result |
|---|---|---|---|
| DL | Customer churn prediction | ANN (Keras), binary classification | ~84% test accuracy |
| DL | Median house value prediction | ANN (Keras), regression | MSE loss, MAE metric |
| DL | Rice grain image classification (capstone) | CNN (TensorFlow/Keras), 5 classes | ~99% test accuracy |
| ML | iPhone purchase prediction | Logistic Regression | ~85% accuracy |
| ML | Placement package prediction | Linear Regression (CGPA to package) | Fitted line y = m*x + b |
| ML | Student level clustering | K-Means (k = 4) on CGPA and IQ | 4 clusters, 200 students |
| EDA | Titanic and Tips | Univariate/bivariate analysis | Charts and encodings |
| EDA | IMDb movies | Pandas queries, pivot tables | 1,000 movies |
| EDA | Chocolate portfolio and Flights | Pivot tables, heatmaps | Sales and passenger trends |
| EDA | Iris, IPL and Life Expectancy | Descriptive statistics, PDF/CDF | Central tendency and spread |

## Tools and Libraries
Python, NumPy, Pandas, Matplotlib, Seaborn, SciPy, Scikit-Learn, Keras / TensorFlow, OpenCV, split-folders

## Running the Notebooks
The notebooks read data from `/content/...` (Google Colab). To run locally, change the path in the `read_csv` / `read_excel` cell to the dataset in the same folder. The rice dataset is large and is not included (link in its folder README).
