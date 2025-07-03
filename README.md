# K-Means Clustering on BMI Dataset

##  Project Overview

This project applies K-Means clustering to a dataset containing age, height, weight, BMI, and BMI class. The objective is to group individuals based on their BMI-related attributes and evaluate the clustering using Mean Squared Error (MSE).

---

##  Dataset

The dataset used is located at `/content/bmi.csv`. It contains the following columns:

- Age
- Height
- Weight
- BMI (Body Mass Index)
- BmiClass (categorical label based on BMI value)

---

##  Steps Performed

### 1. Data Loading and Preprocessing

- The dataset is loaded and scaled for clustering.
- Only relevant numerical features are used for model training.

### 2. Model Training

- K-Means algorithm is applied with 3 clusters.
- The clustering model identifies 3 cluster centers in the transformed feature space.

### 3. Evaluation

- The model is evaluated using **Mean Squared Error (MSE)**.
- **MSE value obtained**: `0.347867086210254`

### 4. Cluster Centers

[[-0.12988183 0.26432505]
[ 1.97719564 0.90637795]
[-0.90329608 -1.49290571]]



---

##  Conclusion

The clustering model successfully grouped individuals based on BMI-related features. The MSE value is relatively low, indicating that the clusters are formed with reasonable accuracy. This analysis gives insight into how individuals can be categorized based on health metrics like BMI, which can help in segmenting populations for further medical or lifestyle analysis.
