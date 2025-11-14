# ASD_classification&other_analysis-Thesis-
This repository contains the code for my thesis on Autism Spectrum Disorder (ASD) detection using PCA and ensemble machine learning models. The goal was to improve the accuracy of ASD versus typically developing (TD) classification while reducing computational complexity. (ABIDE dataset)


🎯 Objective

Build an efficient ML pipeline that:

Reduces feature dimensionality using PCA

Trains and optimizes four linear models (SVM, Linear SVC, Logistic Regression, Ridge Classifier)

Combines top performers into an ensemble classifier

Evaluates performance using 10-fold cross-validation

Compares results with and without PCA

Examines the impact of ASD subtypes on classification

🧪 Method Summary

Input: rs-fMRI connectivity features

Dimensionality reduction: Principal Component Analysis

Models tested: SVM, Linear SVC, Logistic Regression, Ridge

Ensemble: Best 3 models

Evaluation: 10-fold CV on ASD–TD and Autism–TD subsets

📊 Key Results

Ensemble + PCA achieved the best performance

Accuracy: 76.01%

Precision: 72.01%

Recall: 70.69%

Excluding subtypes (Asperger’s, PDD-NOS) improved classification

PCA helped both accuracy and computational efficiency

