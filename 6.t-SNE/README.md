<div align="center">

# 🎯 t-Distributed Stochastic Neighbor Embedding (t-SNE)

### Visualizing High-Dimensional Data Through Nonlinear Dimensionality Reduction

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Level-Beginner_to_Intermediate-green?style=for-the-badge">

---

### 🚀 Learn how t-SNE reveals hidden patterns in complex datasets

</div>

---

# 📌 Overview

t-Distributed Stochastic Neighbor Embedding (t-SNE) is a powerful nonlinear dimensionality reduction technique primarily used for visualization.

Unlike PCA, which focuses on preserving variance, and MDS, which focuses on preserving distances, t-SNE focuses on preserving local neighborhood relationships between data points.

This folder demonstrates t-SNE using both the Iris Dataset and the Wine Dataset.

---

# 🧠 Why t-SNE?

High-dimensional datasets are difficult to visualize and interpret.

t-SNE helps by:

✔ Revealing hidden clusters

✔ Preserving local relationships

✔ Discovering nonlinear structures

✔ Visualizing high-dimensional data in 2D

✔ Exploring class separability

---

# 📐 How t-SNE Works

### Step 1

Measure similarity between points in high-dimensional space.

### Step 2

Convert similarities into probabilities.

### Step 3

Map observations into a lower-dimensional space.

### Step 4

Minimize the difference between original and projected similarities.

### Step 5

Generate a meaningful low-dimensional embedding.

---

# 🔑 Important Parameters

## Perplexity

Controls how many neighboring points influence each observation.

Typical values:

```text
5 – 50
```

The notebooks compare:

- Perplexity = 5
- Perplexity = 30
- Perplexity = 50

---

## Learning Rate

Controls optimization behavior.

The notebooks compare:

- Learning Rate = 10
- Learning Rate = 200
- Learning Rate = 1000

---

## Initialization Methods

Two initialization techniques are explored:

### PCA Initialization

```python
init="pca"
```

### Random Initialization

```python
init="random"
```

---

# 📂 Project Structure

## 1️⃣ t-SNE on Wine Dataset

📄 File

- `tsne_wine.ipynb`

### Objective

Visualize the Wine Dataset in two dimensions using t-SNE.

### Concepts Covered

✔ Data Standardization

✔ t-SNE Embedding

✔ Perplexity Selection

✔ PCA Initialization

✔ Random Initialization

✔ Cluster Visualization

✔ KL Divergence Analysis

---

## 2️⃣ MDS vs t-SNE Analysis on Iris Dataset

📄 File

- `mdstsne.ipynb`

### Objective

Compare MDS and t-SNE for dimensionality reduction and visualization.

### Concepts Covered

✔ Metric MDS

✔ Non-Metric MDS

✔ Precomputed Distance MDS

✔ 3D MDS

✔ t-SNE Embedding

✔ Perplexity Comparison

✔ Learning Rate Comparison

✔ MDS vs t-SNE Visualization

✔ KL Divergence

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
Preprocess Data
      ↓
Standardize Features
      ↓
Apply t-SNE
      ↓
Tune Parameters
      ↓
Generate Low-Dimensional Embedding
      ↓
Visualize Clusters
      ↓
Analyze Results
```

---

# 📊 Visualizations Included

### 2D t-SNE Embedding

Visualize high-dimensional data in two dimensions.

### Perplexity Comparison

Compare embeddings using different perplexity values.

### Learning Rate Comparison

Observe how learning rate affects the embedding.

### Initialization Comparison

Compare PCA and Random initialization methods.

### MDS vs t-SNE Visualization

Analyze differences between the two techniques.

---

# 📈 Evaluation Metrics

The notebooks evaluate:

### KL Divergence

Measures how well the low-dimensional representation preserves neighborhood relationships.

```text
Lower KL Divergence = Better Embedding
```

### Iterations

Number of optimization iterations required for convergence.

---

# ⚔️ PCA vs MDS vs t-SNE

| Technique | Goal | Strength |
|------------|------------|------------|
| PCA | Preserve Variance | Fast & Simple |
| MDS | Preserve Distances | Similarity Analysis |
| t-SNE | Preserve Neighborhoods | Cluster Visualization |

---



# 🌍 Real-World Applications

### Customer Segmentation

Visualize customer groups and behavior patterns.

### Bioinformatics

Analyze gene expression and biological data.

### Image Recognition

Visualize image feature representations.

### Anomaly Detection

Identify unusual patterns in data.

### Exploratory Data Analysis

Discover hidden structures before modeling.

---

# 📚 Topics Covered

- t-SNE
- Nonlinear Dimensionality Reduction
- Perplexity
- Learning Rate
- KL Divergence
- Embedding Visualization
- MDS vs t-SNE
- Cluster Visualization
- Data Exploration

---


<div align="center">

## ⭐ If this repository helped you, consider giving it a star!

</div>
