# Breast_Cancer_Classification

## Problem Statement
To build a breast cancer classifier on dataset provided by https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic) that can accurately classify a tumor as benign or malignant based on several observations/features.

30 features are used, examples:
-radius
-area
-texture
-perimeter, etc.

Datasets are linearly separable using all 30 input features.

Number of instances : 569

Class Distribution : 212 Malignant, 357 Benign

Target Class:
- Malignant
- Benign

In this project in python, we’ll build a classifier to train on 80% of a breast cancer dataset. Of this, we’ll keep 10% of the data for validation. Using Scikit Learn, we’ll define a SVM (Support Vector Machine), and train it on our images. We’ll then derive a confusion matrix to analyze the performance of the model.

## Conclusion
The Machine Learning Technique(SVM) was able to classify tumors into Malignant/Benign with 97% accuracy.
The technique can rapidly evaluate breast masses and classify them in an automated fashioin.
Early breast cancer can dramatically save lives specially in the devloping world.
The technique can be further improved by combining computer vision/ML techniques to directly classify cancer using tissue images.
