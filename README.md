# 🖼️ Clustering and Dimensionality Reduction in Image Data

This project explores machine learning techniques for clustering and dimensionality reduction applied to hyperspectral and remote sensing images. The primary objective is to analyze and cluster image data using various methods, assessing their effectiveness and comparing results.

## 🎯 Objectives

- **Clustering Methods**: Implement and compare **K-Means** and **Fuzzy C-Means** algorithms.
- **Dimensionality Reduction**: Apply **Principal Component Analysis (PCA)** to reduce the dimensionality of hyperspectral images.
- **Feature Extraction**: Utilize a pre-trained **Convolutional Neural Network (CNN)** to extract features from remote sensing images for clustering purposes.

## 🗂️ Project Structure

1. **Part 1: Hyperspectral Image Analysis**
   - **Clustering**: Apply K-Means and Fuzzy C-Means algorithms to hyperspectral images.
   - **Dimensionality Reduction**: Use PCA to reduce image dimensionality.
   - **Evaluation**: Assess clustering effectiveness in the reduced dimensional space.

2. **Part 2: Remote Sensing Image Analysis**
   - **Feature Extraction**: Employ a pre-trained CNN to extract features from remote sensing images.
   - **Clustering**: Perform clustering on extracted features and compare results with clustering based on raw pixel values.

## 🛠️ Tools & Technologies

- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: `numpy`, `pandas`
  - Visualization: `matplotlib`
  - Machine Learning: `scikit-learn`
  - Deep Learning: `tensorflow` or `pytorch` (for CNN feature extraction)

