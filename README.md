---

CIFAR-10 Image Classification using Machine Learning
Project Overview

This project uses machine learning models to classify images from the CIFAR-10 dataset into 10 categories. The models used are Random Forest and Support Vector Machine (SVM), and their performance is compared.

---

**Steps Performed**

**Data Preprocessing**
- Combined training and test data
- Normalized pixel values (0–255 to 0–1)
- Flattened images into 1D vectors
- Split data into 80% training and 20% testing

**Model Training**

- Random Forest trained using GridSearchCV
- SVM trained using a linear kernel
- Both models trained on a subset of data for speed

**Evaluation**

**Models were evaluated using:**
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

**Results**
Model	                   Accuracy
Random Forest	           ~0.35–0.45
SVM  	                   ~0.30–0.40

Random Forest performed slightly better than SVM.

---

**How to Run**

Clone the repository:
git clone https://github.com/your-username/cifar10-image-classification-ml.git

Open the notebook: Assignment_11_AI.ipynb

Install dependencies: pip install numpy matplotlib scikit-learn tensorflow

Run all cells from top to bottom.

---
