<div align="center">

# 🌌 DBSCAN Clustering

### Density-Based Spatial Clustering of Applications with Noise

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas">
<img src="https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Level-Beginner_to_Intermediate-green?style=for-the-badge">

---

### 🚀 Learn how DBSCAN discovers clusters of arbitrary shapes and detects outliers automatically

</div>

---

# 📌 Overview

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is a powerful clustering algorithm that groups data points based on density rather than distance from centroids.

Unlike K-Means, DBSCAN:

✅ Does not require specifying the number of clusters beforehand

✅ Can discover clusters of arbitrary shapes

✅ Automatically detects outliers and noise

✅ Works well on real-world datasets containing irregular patterns

This folder demonstrates DBSCAN using:

- Mall Customer Dataset
- Wine Quality Dataset

---

# 🧠 What is Density-Based Clustering?

DBSCAN groups observations that are densely packed together while marking sparse observations as noise.

```text
Dense Region
      ↓
Cluster

Sparse Region
      ↓
Noise / Outlier
```

The algorithm expands clusters by exploring neighboring points within a specified radius.

---

# 📐 Core Concepts

## Epsilon (ε)

Defines the neighborhood radius around a point.

```text
ε = Search Radius
```

Larger ε:

- Larger clusters
- Fewer outliers

Smaller ε:

- More clusters
- More outliers

---

## MinPts

Minimum number of neighboring points required to form a dense region.

```text
MinPts = Minimum Points
```

A point becomes a core point if it has at least MinPts neighbors within ε.

---

## Core Point

A point having enough nearby neighbors.

```text
Neighbors ≥ MinPts
```

---

## Border Point

Belongs to a cluster but does not satisfy MinPts itself.

---

## Noise Point

An isolated point that does not belong to any cluster.

---

# ⚙️ How DBSCAN Works

### Step 1

Choose ε and MinPts.

### Step 2

Find all neighboring points.

### Step 3

Identify core points.

### Step 4

Expand clusters from core points.

### Step 5

Mark remaining observations as noise.

---

# 📂 Project Structure

## 1️⃣ Mall Customer Segmentation using DBSCAN

📄 Files

- `Mall_Customers.csv`
- `mall_db.ipynb`

### Objective

Cluster customers based on spending behavior and annual income.

### Concepts Covered

✔ Customer Segmentation

✔ Density-Based Clustering

✔ Noise Detection

✔ Cluster Visualization

✔ Outlier Identification

✔ DBSCAN Parameter Selection

---

## 2️⃣ Wine Dataset Clustering using DBSCAN

📄 Files

- `winequality_red.csv`
- `wine_db.ipynb`

### Objective

Identify natural groupings within wine samples using density-based clustering.

### Concepts Covered

✔ Feature Scaling

✔ Density-Based Clustering

✔ Cluster Formation

✔ Outlier Detection

✔ Data Visualization

✔ High-Dimensional Data Clustering

---

# ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

# 🔄 Workflow

```text
Load Dataset
      ↓
Data Preprocessing
      ↓
Feature Scaling
      ↓
Select ε and MinPts
      ↓
Apply DBSCAN
      ↓
Identify Clusters
      ↓
Detect Noise Points
      ↓
Visualize Results
```

---

# 📊 Visualizations Included

## Cluster Visualization

Visual representation of discovered clusters.

---

## Noise Detection

Highlights observations identified as outliers.

---

## Density-Based Grouping

Shows how clusters emerge based on local density.

---

## Customer Segmentation

Visualizes customer groups using spending score and annual income.

---



# ⚔️ K-Means vs DBSCAN

| Feature | K-Means | DBSCAN |
|----------|----------|----------|
| Need K beforehand | ✅ Yes | ❌ No |
| Detects Outliers | ❌ No | ✅ Yes |
| Handles Irregular Shapes | ❌ Poorly | ✅ Excellent |
| Centroid-Based | ✅ Yes | ❌ No |
| Density-Based | ❌ No | ✅ Yes |

---

# 🌍 Real-World Applications

### Fraud Detection

Identify suspicious transactions and anomalies.

### Customer Segmentation

Group customers based on purchasing behavior.

### Network Security

Detect abnormal network activity.

### Geographical Analysis

Cluster locations and spatial data.

### Anomaly Detection

Identify unusual observations automatically.

---

# 📈 Advantages of DBSCAN

✔ No need to specify number of clusters

✔ Detects outliers automatically

✔ Handles arbitrary cluster shapes

✔ Effective on noisy datasets

✔ Robust clustering performance

---

# ⚠️ Limitations

❌ Sensitive to ε selection

❌ Performance decreases in very high dimensions

❌ Struggles with varying density clusters

❌ Parameter tuning may be required

---

# 📚 Topics Covered

- DBSCAN
- Density-Based Clustering
- Core Points
- Border Points
- Noise Points
- Outlier Detection
- Customer Segmentation
- Wine Dataset Analysis
- Unsupervised Learning

---


<div align="center">

## ⭐ If this repository helped you, consider giving it a star!

</div>
