<div align="center">

# 🤖 Autoencoder

### Unsupervised Deep Learning for Feature Learning and Data Compression

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch">
<img src="https://img.shields.io/badge/MNIST-Handwritten%20Digits-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Level-Beginner_to_Intermediate-green?style=for-the-badge">

---

### 🚀 Learn how neural networks can compress and reconstruct data without labels

</div>

---

# 📌 Overview

An Autoencoder is a neural network that learns to compress data into a lower-dimensional representation and then reconstruct the original input.

Unlike traditional supervised learning, Autoencoders learn without labels by trying to reproduce their own inputs.

This project demonstrates an Autoencoder built using **PyTorch** and trained on the **MNIST handwritten digits dataset**.

---

# 🧠 What is an Autoencoder?

An Autoencoder consists of two main components:

### Encoder

Compresses the input into a smaller representation.

### Decoder

Reconstructs the original input from the compressed representation.

```text
Input Image
      ↓
Encoder
      ↓
Latent Space
      ↓
Decoder
      ↓
Reconstructed Image
```

---

# 🎯 Goal of Autoencoders

The objective is to learn meaningful representations while minimizing reconstruction error.

The model learns:

✔ Important features

✔ Data compression

✔ Latent representations

✔ Pattern extraction

---

# 🏗️ Architecture Used

The notebook implements a fully connected Autoencoder.

## Encoder

```text
784
 ↓
128
 ↓
64
 ↓
32
```

---

## Decoder

```text
32
 ↓
64
 ↓
128
 ↓
784
```

---

# 📐 Latent Space

The bottleneck layer contains:

```text
32 Features
```

This compressed representation stores the most important information about the input image.

---

# 📂 Project Structure

## 1️⃣ MNIST Autoencoder

📄 File

- `autoencoder.ipynb`

### Objective

Train an Autoencoder to compress and reconstruct handwritten digit images from the MNIST dataset.

### Concepts Covered

✔ MNIST Dataset

✔ Neural Networks

✔ Encoder Architecture

✔ Decoder Architecture

✔ Latent Space Learning

✔ Data Compression

✔ Image Reconstruction

✔ Deep Learning Fundamentals

---

# ⚙️ Technologies Used

- Python
- PyTorch
- TorchVision
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 🔄 Workflow

```text
Load MNIST Dataset
      ↓
Preprocess Images
      ↓
Flatten Input Images
      ↓
Encoder Compression
      ↓
Latent Representation
      ↓
Decoder Reconstruction
      ↓
Calculate Reconstruction Error
      ↓
Update Network Weights
```

---

# 📊 Loss Function

The notebook uses:

## Mean Squared Error (MSE)

Measures reconstruction quality.

```text
MSE = Average[(Original - Reconstructed)²]
```

Lower MSE indicates better reconstruction.

---

# ⚡ Optimizer

The model uses:

## Adam Optimizer

```python
optim.Adam()
```

Advantages:

✔ Fast convergence

✔ Adaptive learning rates

✔ Widely used in Deep Learning

---



# 🌍 Real-World Applications

### Image Compression

Reduce storage while preserving information.

### Feature Extraction

Learn compact representations of data.

### Dimensionality Reduction

Alternative to PCA and SVD.

### Denoising

Remove noise from images.

### Anomaly Detection

Identify unusual observations through reconstruction error.

### Deep Learning Pretraining

Learn useful representations before supervised training.

---

# ⚔️ PCA vs Autoencoder

| Feature | PCA | Autoencoder |
|----------|----------|----------|
| Linear | ✅ Yes | ❌ No |
| Nonlinear Patterns | ❌ No | ✅ Yes |
| Neural Network Based | ❌ No | ✅ Yes |
| Feature Learning | Limited | Powerful |
| Reconstruction | ✅ Yes | ✅ Yes |

---

# 📚 Topics Covered

- Autoencoders
- Deep Learning
- Neural Networks
- Encoder
- Decoder
- Latent Space
- MNIST Dataset
- Data Compression
- Image Reconstruction
- PyTorch

---



<div align="center">

## ⭐ If this repository helped you, consider giving it a star!

</div>
