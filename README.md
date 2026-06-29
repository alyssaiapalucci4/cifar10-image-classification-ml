---

Tital: CIFAR-10 Image Classification using Machine Learning
Author: Alyssa I

---

## Overview

This project demonstrates image classification using machine learning techniques on the CIFAR-10 dataset. The goal is to classify images into 10 categories using traditional machine learning models and compare their performance.

Two models were implemented:
- Random Forest Classifier  
- Support Vector Machine (SVM)
  
---

Dataset

The CIFAR-10 dataset contains:

- 60,000 color images (32x32 pixels)
- 10 object classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

All images were flattened into 1D feature vectors to be used with traditional machine learning models.

---

**Workflow**

1. Data Preprocessing
- Combined training and test datasets
- Normalized pixel values (0–255 → 0–1)
- Flattened images into feature vectors
- Split into 80% training and 20% testing

--- 

**2. Model Training**
Random Forest
- Tuned using GridSearchCV
- Hyperparameters optimized:
    - n_estimators: 50, 100
    - max_depth: 10, None
    - min_samples_split: 2
    - min_samples_leaf: 1
- Trained on a subset for efficiency

Support Vector Machine (SVM)
- Linear kernel used
- Trained on same dataset subset for fair comparison
  
---

**Results**
Model	             Accuracy	         Notes
Random Forest	     ~0.35 – 0.45	     Best overall performance
SVM	               ~0.30 – 0.40	     Faster but less accurate

---

**Visualizations** 

Confusion Matrix
- Shows classification performance across all 10 classes.

Feature Importance
- Highlights which pixel regions contributed most to predictions.

--- 

How to Run
1. Clone the repository: git clone https://github.com/alyssaiapalucci4/cifar10-image-classification-ml/tree/main
   
2. Open the notebook

Open:Assignment_11_AI.ipynb

Run using: 
- Google Colab (recommended)
- Jupyter Notebook
- VS Code (Jupyter extension)

3. Install dependencies
- pip install numpy matplotlib scikit-learn tensorflow

4. Run the notebook

Run all cells from top to bottom to:

- Load dataset
- Train models
- Evaluate results
- Generate plots
---
