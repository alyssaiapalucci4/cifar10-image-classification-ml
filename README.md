CIFAR-10 Image Classification using Machine Learning
📌 Project Overview

This project focuses on image classification using machine learning techniques applied to the CIFAR-10 dataset. The goal is to classify images into 10 categories using traditional machine learning models and compare their performance.

Two models were implemented:

Random Forest Classifier
Support Vector Machine (SVM)

The models were evaluated and compared using standard classification metrics.

📊 Dataset

The CIFAR-10 dataset contains:

60,000 color images (32×32 pixels)
10 classes (airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, trucks)

Each image was flattened into a feature vector for use with traditional machine learning algorithms.

⚙️ Project Workflow
1. Data Preprocessing
Combined training and testing datasets
Normalized pixel values (0–255 → 0–1)
Flattened images into 1D feature vectors
Split data into 80% training and 20% testing sets

2. Model Training
Random Forest trained using GridSearchCV for hyperparameter tuning
SVM trained using a linear kernel
Both models trained on a subset of data for efficiency

3. Evaluation

Models were evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
📈 Results Summary
Model	Accuracy	Notes
Random Forest	Higher (~0.35–0.45)	Better overall performance
SVM	Lower (~0.30–0.40)	Faster but less accurate
📊 Visual Results
Confusion Matrix (Random Forest)
Feature Importance Plot

These visualizations help understand model performance and feature contribution.

🚀 How to Run This Project
1. Clone the repository
git clone https://github.com/your-username/cifar10-image-classification-ml.git
2. Open the notebook

Open the file:

Assignment_11_AI.ipynb

You can run it using:

Google Colab (recommended)
Jupyter Notebook
VS Code (with Jupyter extension)
3. Install dependencies (if needed)
pip install numpy matplotlib scikit-learn tensorflow
4. Run all cells

Execute the notebook from top to bottom to:

Load dataset
Train models
Evaluate performance
Generate plots
