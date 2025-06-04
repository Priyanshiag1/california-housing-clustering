# 🏘️ DBSCAN Clustering on California Housing Data

This project applies the **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** algorithm on California housing data to discover spatial and feature-based clusters. It also includes hyperparameter tuning and visualization.

## 📁 Files Included

- `DBSCAN_California_Housing.ipynb` — Complete notebook with explanations and visualizations
- `california_housing_train.csv` — Dataset
- `README.md` — You’re here!

---

## 📌 Project Objective

To explore unsupervised learning using DBSCAN for clustering:
- House locations (`latitude`, `longitude`)
- Housing features (`total_rooms`, `housing_median_age`)

---

## 📊 Techniques Used

- **DBSCAN** clustering
- **Silhouette Score** for evaluation
- **Parameter tuning** for `eps` and `min_samples`
- **StandardScaler** for scaling
- **2D and interactive 3D plots** for visualization

---

## 📈 Key Steps

1. Load and explore data
2. Visualize house locations
3. Apply DBSCAN with different parameters
4. Evaluate clusters using Silhouette Score
5. Optimize parameters for best clustering
6. Visualize results using Plotly
7. Repeat for different feature combinations

---

## 📦 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Plotly
- Matplotlib

---

## 📁 Dataset Info

The dataset includes:
- `longitude`, `latitude` — spatial info
- `total_rooms`, `housing_median_age` — housing features
- Other features like `total_bedrooms`, `median_income`, etc.

---

## 🧠 Learning Outcomes

- Understand how DBSCAN forms clusters
- Learn to tune DBSCAN parameters effectively
- Evaluate clusters using silhouette scores
- Handle spatial and scaled numerical data
