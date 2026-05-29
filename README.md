# 🧠 Unsupervised Machine Learning

<div align="center">

### 🚀 A Complete Beginner-Friendly Journey Through Clustering, Dimensionality Reduction, Similarity Analysis, and Deep Representation Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge\&logo=scikitlearn)
![PyTorch](https://img.shields.io/badge/PyTorch-red?style=for-the-badge\&logo=pytorch)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge\&logo=jupyter)
![Level](https://img.shields.io/badge/Level-Beginner_to_Advanced-green?style=for-the-badge)

### 📊 Learn How Machines Discover Hidden Patterns Without Labels

</div>

---

# 🌟 Repository Overview

Most Machine Learning tutorials focus on prediction.

But before predicting anything, we often need to answer questions like:

* Which customers are similar?
* How can thousands of features be reduced to a few?
* Are there hidden groups in the data?
* Can we visualize complex datasets?
* Can neural networks learn useful representations automatically?

These are **Unsupervised Learning problems**.

This repository provides practical implementations of the most important Unsupervised Machine Learning algorithms using real-world datasets and step-by-step Jupyter notebooks.

---

# 🤔 What is Unsupervised Machine Learning?

In Unsupervised Learning:

```text
Input Data ✅
Output Labels ❌
```

The model receives data without target labels and must discover patterns on its own.

---

## Example

Imagine a customer database:

| Customer | Income | Spending |
| -------- | ------ | -------- |
| A        | High   | High     |
| B        | Low    | Low      |
| C        | High   | Medium   |

No labels are provided.

The algorithm automatically discovers groups such as:

```text
Premium Customers
Budget Customers
Moderate Customers
```

This process is called **Clustering**.

---

# 🎯 Main Goals of Unsupervised Learning

### 📊 Discover Hidden Patterns

Find structures that humans may not notice.

### 👥 Group Similar Observations

Create meaningful clusters.

### 📉 Reduce Dimensions

Simplify complex datasets.

### 🔍 Detect Anomalies

Identify unusual observations.

### 🤖 Learn Better Representations

Compress information while preserving meaning.

---

# 🗺️ Learning Roadmap

```text
Distance Measures
        ↓
Dimensionality Reduction
        ↓
Clustering
        ↓
Deep Representation Learning
```

This repository follows the same progression.

---

# 📚 Topics Covered

## 📏 1. Distance Measures

The foundation of most Unsupervised Learning algorithms.

### Concepts

* Distance Matrix
* Pairwise Distances
* Euclidean Distance
* Similarity Analysis

### Files

* USL_DistMatrix.ipynb
* wine_distmatrix.ipynb

---

## 📉 2. Principal Component Analysis (PCA)

Reduce dimensions while preserving maximum variance.

### Concepts

* Principal Components
* Explained Variance
* Feature Compression
* Data Visualization

### Datasets

* Iris Dataset
* Customer Churn Dataset

---

## 📊 3. Linear Discriminant Analysis (LDA)

Dimensionality reduction with class separation.

### Concepts

* Scatter Matrices
* Class Separation
* PCA vs LDA
* Face Recognition

### Datasets

* Customer Churn Dataset
* Wine Dataset
* Face Dataset

---

## 🔢 4. Singular Value Decomposition (SVD)

Matrix factorization for feature extraction and compression.

### Concepts

* TruncatedSVD
* Feature Reduction
* Explained Variance
* Matrix Decomposition

### Datasets

* Digits Dataset
* Wine Dataset
* Face Dataset

---

## 🗺️ 5. Multidimensional Scaling (MDS)

Preserve distances while reducing dimensions.

### Concepts

* Distance Preservation
* Stress Function
* Metric MDS

### Dataset

* Wine Dataset

---

## 🎯 6. t-SNE

Visualize complex datasets through nonlinear dimensionality reduction.

### Concepts

* Perplexity
* KL Divergence
* Neighborhood Preservation
* MDS vs t-SNE

### Datasets

* Iris Dataset
* Wine Dataset

---

## 🎯 7. K-Means Clustering

The most popular clustering algorithm.

### Concepts

* Centroids
* Elbow Method
* WCSS
* Customer Segmentation

### Dataset

* Mall Customers Dataset

---

## 🌌 8. DBSCAN

Density-based clustering with automatic outlier detection.

### Concepts

* Core Points
* Border Points
* Noise Points
* Density-Based Clustering

### Datasets

* Mall Customers Dataset
* Wine Dataset

---

## 🤖 9. Autoencoder

Deep learning for unsupervised representation learning.

### Concepts

* Encoder
* Decoder
* Latent Space
* Image Reconstruction
* Feature Learning

### Dataset

* MNIST Handwritten Digits

---

# 📊 Comparison of Techniques

| Technique         | Category                 | Main Purpose              |
| ----------------- | ------------------------ | ------------------------- |
| Distance Measures | Similarity Analysis      | Measure relationships     |
| PCA               | Dimensionality Reduction | Preserve variance         |
| LDA               | Dimensionality Reduction | Maximize class separation |
| SVD               | Matrix Factorization     | Feature extraction        |
| MDS               | Visualization            | Preserve distances        |
| t-SNE             | Visualization            | Preserve neighborhoods    |
| K-Means           | Clustering               | Group similar points      |
| DBSCAN            | Clustering               | Density-based grouping    |
| Autoencoder       | Deep Learning            | Representation learning   |

---

# ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* PyTorch
* Jupyter Notebook

---

# 🔄 Typical Workflow

```text
Raw Data
    ↓
Preprocessing
    ↓
Feature Scaling
    ↓
Choose Technique
    ↓
Distance Analysis
    ↓
Dimensionality Reduction
    ↓
Clustering
    ↓
Visualization
    ↓
Insights
```

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/kjuhi-18/Unsupervised-Machine-Learning.git
```

## 2️⃣ Navigate to Repository

```bash
cd Unsupervised-Machine-Learning
```

## 3️⃣ Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn torch torchvision jupyter
```

## 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

## 5️⃣ Follow the Learning Path

```text
1.Distance Measures
      ↓
2.PCA
      ↓
3.LDA
      ↓
4.SVD
      ↓
5.MDS
      ↓
6.t-SNE
      ↓
7.K-MEANS
      ↓
8.DBSCAN
      ↓
9.AutoEncoder
```

---



# 🌍 Real-World Applications

🏦 Fraud Detection

🛒 Customer Segmentation

🎬 Recommendation Systems

📷 Face Recognition

🧬 Bioinformatics

📈 Market Analysis

📄 Document Clustering

🤖 Deep Feature Learning

---

<div align="center">

## ⭐ If you found this repository helpful, consider giving it a star!

### Happy Learning 🚀

</div>
