# Task8_ElevateLabs
# K-Means Clustering — Mall Customer Segmentation

## 📌 Objective

The objective of this task is to perform **unsupervised learning** using K-Means clustering to segment customers based on their income and spending behavior.

---

## 🛠 Tools & Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

Mall Customer Segmentation Dataset

Key features used:

* Annual Income (k$)
* Spending Score (1–100)

This dataset does not contain labeled categories, making it suitable for clustering (unsupervised learning).

---

## 🔎 Steps Performed

### 1. Data Loading

* Uploaded dataset into Google Colab
* Loaded using Pandas

### 2. Feature Selection

Selected:

* Annual Income
* Spending Score

### 3. Data Scaling

* Applied StandardScaler to normalize features

### 4. Elbow Method

* Calculated inertia for K values from 1 to 10
* Identified optimal K = 5

### 5. K-Means Clustering

* Applied K-Means with 5 clusters
* Assigned cluster labels to each customer

### 6. Cluster Visualization

* Plotted clusters with color-coding
* Observed clear separation of customer groups

### 7. Silhouette Score Evaluation

* Calculated Silhouette Score = **0.55**
* Indicates good cluster separation and cohesion

---

## 📊 Results

| Parameter        | Value |
| ---------------- | ----- |
| Optimal K        | 5     |
| Silhouette Score | 0.55  |

---

## 📈 Interpretation

* Customers were segmented into 5 meaningful groups.
* Silhouette Score above 0.5 confirms effective clustering.
* The clusters can represent different customer behaviors such as:

  * High income, high spending
  * High income, low spending
  * Low income, high spending
  * Budget customers
  * Average customers

---

## 🧠 Interview Questions

**1. How does K-Means work?**
It assigns points to the nearest centroid and updates centroids iteratively until convergence.

**2. What is the Elbow Method?**
A technique to find optimal K by plotting inertia and identifying the bend point.

**3. Limitations of K-Means?**
Sensitive to initialization and struggles with non-spherical clusters.

**4. What is inertia?**
Sum of squared distances of points from their cluster centroids.

**5. What is Silhouette Score?**
Measures how well a data point fits within its cluster compared to other clusters.

**6. Clustering vs Classification?**
Clustering is unsupervised; classification is supervised learning.

---

## 🏁 Conclusion

K-Means clustering successfully segmented customers into five distinct groups based on income and spending behavior. The Silhouette Score confirms that the clusters are well-defined. This demonstrates how unsupervised learning can uncover hidden patterns and support data-driven decision-making.

---

## 👨‍💻 Author

Mohd Yusuf Khan
