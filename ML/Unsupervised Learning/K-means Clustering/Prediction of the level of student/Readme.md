# Student Level Prediction using K-Means Clustering

**Notebook:** [K_Means.ipynb](K_Means.ipynb)
**Data:** `student_clustering.csv` (200 students: `cgpa`, `iq`)

## Workflow
1. Load data and plot CGPA vs IQ
2. Elbow method: run `KMeans` for several values of `k` and compare inertia
3. Fit `KMeans(n_clusters=4)` and predict a cluster for each student
4. Plot the 4 clusters and interpret each as a student level
