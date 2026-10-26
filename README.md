# breast-cancer-classification
This project compares three machine learning classification models—Artificial Neural Network (ANN) trained using backpropagation, Support Vector Machine (SVM), and Decision Tree—to classify breast cancer cases as benign or malignant.

# Dataset

Dataset: Breast Cancer Wisconsin (Diagnostic)
Samples: 569
Features: 30 numeric features
Target classes: Benign (0) and Malignant (1)
Source: Scikit-learn built-in dataset loader

# Technologies Used

Python
Jupyter Notebook / Google Colab
Scikit-learn
NumPy
Pandas
Matplotlib

# Methodology

Load the breast cancer dataset.
Encode malignant cases as 1 and benign cases as 0.
Split the data into 80% training and 20% testing sets.
Scale features for ANN and SVM.
Train ANN, SVM, and Decision Tree models.
Evaluate the models using confusion matrices and classification metrics.

# Results

# Model Accuracy

1. Artificial Neural Network (ANN) 99.12%
2. Support Vector Machine (SVM) 97.37%
3. Decision Tree 92.98%

# The ANN achieved the highest accuracy on this test split. These results reflect one train/test split and do not necessarily represent performance on every unseen dataset.

# How to Run

Open the Jupyter notebook in Google Colab or a local Jupyter environment.
Install the required libraries if they are not already installed.
Run all notebook cells in order.

# Project Files

1. breast_cancer_model_comparison.ipynb — this notebook is containing the implementation and evaluation.
2. Comparison Table of all the Metrics
3. Snaps of ANN, SVM and Decision Tree confusion Matrix

