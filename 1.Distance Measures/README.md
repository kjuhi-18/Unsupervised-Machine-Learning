<div align="center">

# 📏 Distance Measures

### Understanding Similarity and Dissimilarity in Unsupervised Machine Learning

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas">
<img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Level-Beginner-green?style=for-the-badge">

---

### 🚀 Learn how machines measure similarity between data points

</div>

---

# 📌 Overview

Distance Measures form the foundation of many **Unsupervised Machine Learning** algorithms.

Before machines can group data into clusters, they must determine:

- Which observations are similar?
- Which observations are different?
- How far apart are two data points?

This folder introduces commonly used distance metrics through simple examples, image-based comparisons, and a real-world Wine dataset.

---

# 🧠 Why Distance Measures Matter?

Many machine learning algorithms rely on distance calculations:

✔ K-Means Clustering

✔ Hierarchical Clustering

✔ DBSCAN

✔ Multidimensional Scaling (MDS)

✔ t-SNE

✔ K-Nearest Neighbors (KNN)

---

# 📐 Distance Metrics Covered

## 1️⃣ Euclidean Distance

Measures straight-line distance between two points.

```text
Distance = √[(x₂-x₁)² + (y₂-y₁)²]
```

### Used In

- K-Means
- Pattern Recognition
- Similarity Analysis

---

## 2️⃣ Manhattan Distance

Measures distance along horizontal and vertical paths.

```text
Distance = |x₂-x₁| + |y₂-y₁|
```

### Used In

- High-dimensional datasets
- Grid-based movement
- Sparse data

---

## 3️⃣ Chebyshev Distance

Measures the maximum difference along any dimension.

```text
Distance = max(|x₁-y₁|, |x₂-y₂|, ...)
```

### Used In

- Chessboard movement
- Image processing
- Pattern comparison

---

## 4️⃣ Minkowski Distance

Generalized distance metric.

```text
Distance = (Σ|x-y|ᵖ)¹/ᵖ
```

### Special Cases

- p = 1 → Manhattan Distance
- p = 2 → Euclidean Distance

---

# 📂 Project Structure

## 1️⃣ Distance Matrix Fundamentals

📄 File

- `USL_DistMatrix.ipynb`

### Objective

Explore multiple distance metrics using sample datasets and image comparisons.

### Concepts Covered

✔ Euclidean Distance

✔ Manhattan Distance

✔ Chebyshev Distance

✔ Minkowski Distance

✔ Pairwise Distance Matrix

✔ Image Similarity Analysis

---

## 2️⃣ Wine Dataset Distance Analysis

📄 File

- `wine_distmatrix.ipynb`

### Objective

Compare wine samples using standardized features and distance measures.

### Concepts Covered

✔ Data Standardization

✔ Euclidean Distance

✔ Manhattan Distance

✔ Minkowski Distance

✔ Pairwise Sample Comparison

✔ Similarity Measurement

---

# ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- SciPy
- Jupyter Notebook

---

# 🔄 Workflow

```text
Load Dataset
      ↓
Preprocess / Standardize Data
      ↓
Select Distance Metric
      ↓
Compute Distances
      ↓
Generate Distance Matrix
      ↓
Analyze Similarities
```

---

# 📊 What is a Distance Matrix?

A Distance Matrix stores pairwise distances between observations.

Example:

|     | A | B | C |
|-----|---|---|---|
| A | 0 | 4 | 7 |
| B | 4 | 0 | 3 |
| C | 7 | 3 | 0 |

### Interpretation

- Smaller Distance → More Similar
- Larger Distance → Less Similar
- Zero Distance → Same Observation

---

# 🌍 Real-World Applications

### Customer Segmentation

Group similar customers together.

### Image Similarity

Compare images based on pixel values.

### Clustering

Create groups of similar observations.

### Recommendation Systems

Find users with similar preferences.

### Pattern Recognition

Identify hidden relationships in data.

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- How distance metrics work
- Differences between Euclidean, Manhattan, Chebyshev, and Minkowski distances
- How distance matrices are constructed
- Why standardization is important before distance calculations
- How similarity is measured in machine learning

---

# 📚 Topics Covered

- Distance Measures
- Euclidean Distance
- Manhattan Distance
- Chebyshev Distance
- Minkowski Distance
- Distance Matrix
- Pairwise Distances
- Similarity Analysis
- Data Standardization

---



<div align="center">

## ⭐ If this repository helped you, consider giving it a star!

</div>
