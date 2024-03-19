# Prediction-of-BreastCancer-Using-SVM
This repository contains a machine learning model developed to predict breast cancer using Support Vector Machine (SVM) algorithm.

The SVM algorithm implemented in this project learns to classify breast cancer tumors into malignant (cancerous) and benign (non-cancerous) categories by analyzing a set of features extracted from breast imaging data, such as mammography or ultrasound images. 

Explanation:

from sklearn import datasets: This line imports the datasets module from scikit-learn library, which contains various built-in datasets for machine learning tasks.

cancer = datasets.load_breast_cancer(): This line loads the breast cancer dataset using the load_breast_cancer() function from the datasets module. The dataset contains features extracted from breast cancer biopsies and corresponding labels indicating whether the tumor is malignant or benign.

print("Features: ", cancer.feature_names): This line prints the names of the features present in the breast cancer dataset. These features represent various characteristics extracted from the tumors, such as mean radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

print("Labels: ", cancer.target_names): This line prints the types of labels in the breast cancer dataset. In this case, the labels represent the types of tumors, which are either 'malignant' or 'benign'.

By printing out the feature names and label types, you get a better understanding of the structure and content of the breast cancer dataset, which is essential for further data preprocessing and model building steps.
