Deep Neural Network Assignment
--Overview--------------------------------------

This project implements machine learning models from scratch, including a baseline Logistic Regression model and a Multi-Layer Perceptron (MLP).
-------------------------------------------------
--DATASET
Name: Adult Income Dataset
Source: Kaggle / UCI Repository
Task: Binary Classification (Predict income >50K)
--------------------------------------------------
--IMPLEMENTATION
Data preprocessing (encoding, scaling, splitting)
Logistic Regression (from scratch)
Multi-Layer Perceptron (from scratch using NumPy)
---------------------------------------------------
--EVALUATION MATRICES
Accuracy
Loss curves
Model comparison
---------------------------------------------------
--KEY LEARNINGS
Understanding gradient descent
Implementing neural networks without libraries
Comparing linear vs deep models
---------------------------------------------------
--RESULTS--ANALYSIS

[Baseline Accuracy: 0.8157436789845429]
[MLP Accuracy: 0.7676323062749514]

The baseline logistic regression performed better than the MLP model. This may be because the dataset has relatively simple linear relationships, which the baseline model can capture effectively. The MLP model, being more complex, may require better tuning of hyperparameters such as learning rate, number of hidden units, and epochs. This shows that more complex models do not always guarantee better performance.