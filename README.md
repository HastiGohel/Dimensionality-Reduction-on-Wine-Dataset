# PCA - Dimensionality Reduction on Wine Dataset

This repository demonstrates **Dimensionality Reduction** using **Principal Component Analysis (PCA)** on the classic Wine dataset from the UCI Machine Learning Repository.  
It includes data preprocessing, PCA application, visualization, and a comparison of classification model performance with and without PCA.  

---

## 📂 Repository Structure
- `data/`
  - `wine.data` → Wine dataset (numeric features and class labels)  
  - `wine.names` → Dataset description and feature information  
- `notebooks/`
  - `PCA - Dimensionality Reduction.ipynb` → Jupyter Notebook implementation of PCA with Q5–Q8 tasks  

---

## 📊 Project Overview

### Load and Preprocess the Dataset
- Load the Wine dataset using `sklearn.datasets.load_wine()`
- Display dataset shape and column names  
- Explore summary statistics using `.describe()`  
- Scale the dataset using `StandardScaler`  

### Apply PCA
- Apply `PCA` from `sklearn.decomposition`  
- Display explained variance ratio  
- Plot **cumulative explained variance**  
- Identify number of components required to explain **≥95% variance**  

### Visualize PCA Output
- Create a **2D scatter plot** using the first two principal components  
- Color-code samples by their target class for visual separation  

### Compare Model Performance (With vs Without PCA)
- Train a **Logistic Regression classifier** on:
  - Original dataset  
  - PCA-transformed dataset (95% variance retained)  
- Split data using `train_test_split`  
- Compare and report accuracy of both models  
- Comment whether dimensionality reduction **improved or maintained** performance  

---

### Clone the Repository
```bash
[https://github.com/HastiGohel/wine-pca-dim-reduction.git](https://github.com/HastiGohel/Dimensionality-Reduction-on-Wine-Dataset)
