# Data Science Projects Portfolio
## Description
Welcome to my data science portfolio! This repository showcases a collection of academic and applied machine learning projects developed as part of my Master of Data Science program at the University of the Pacific. Each project applies foundational and advanced concepts in data preprocessing, statistical modeling, deep learning, and predictive analytics, using real-world datasets from healthcare, aerospace, sports, education, and more.

# Projects
## Deep Learning for Time Series Forecasting

- Conducted end-to-end time series forecasting using historical multivariate data to predict future values.
- Developed and evaluated Feedforward Neural Networks, RNNs, and 1D ConvNets.
- Applied imputation, normalization, and exploratory visualization.
- Tuned hyperparameters and monitored loss curves for overfitting mitigation.
- Reported unnormalized MAE and generated predictions for March 1–2, 2020.

## Feature Selection and Shallow Neural Networks

- Used Lasso regression with cross-validation to select optimal features for wine quality prediction.
- Debiased the model and compared Eout performance.
- Built a 3-layer neural network using backpropagation and SGD from scratch.
- Trained until convergence and visualized model predictions vs. actual outcomes.

## Bias-Variance Analysis of Hypothesis Sets

- Simulated 10,000 hypotheses each from constant and linear models to approximate sin(πx).
- Calculated and compared bias² and variance for each model.
- Visualized confidence intervals and selected optimal model based on empirical error decomposition.

## Model Validation and Regularization in Healthcare

- Built KNN classifier with 10-fold cross-validation to predict healthcare adherence.
- Identified best K using validation accuracy trends.
- Simulated 10,000 hypotheses to compare regularized and unregularized linear models.
- Visualized model behavior and variance to assess generalization.

## Clustering and RBF Networks

- Built Kernel Ridge Regression models with linear and RBF kernels to predict NFL QB ratings.
- Compared training/test MSE and generalization performance.
- Implemented k-means clustering from scratch with convergence criteria.
- Built RBF network for binary classification using γ = 0.5 and cluster centers.

## Predictive Modeling with KNN, VDM, and Logistic Regression

- Applied KNN with normalized features for healthcare adherence prediction.
- Developed custom Value Distance Metric (VDM) for symbolic features (U.S. regions).
- Implemented logistic regression using gradient descent to model O-ring failure risk.
- Simulated Challenger launch outcome using real NASA data.

## Statistical Testing of Graduation Outcomes

- Assessed if demographic and academic variables differed between graduating vs. non-graduating students.
- Conducted Mann-Whitney U, t-tests, and chi-square tests across seven hypotheses.
- Interpreted significance levels and relationships between student success and categorical variables.

## Handwritten Digit Classification using SVD

- Converted digit images to matrix format using NumPy and Pandas.
- Applied SVD and least squares to classify digits with dimensionality reduction.
- Evaluated model with a confusion matrix.

## Landsat Image Compression with PCA

- Merged 5 multispectral bands from Landsat imagery (~58 million samples).
- Applied PCA for dimensionality reduction and computational efficiency.
- Visualized compressed images with Plotly for interpretation.

## Quarterback Rating Prediction

- Built multiple linear regression model using Scikit-learn to predict NFL QB ratings.
- Performed feature engineering and validated predictions with pseudoinverse solutions.

## Senator Voting Classification

- Parsed XML data for U.S. senator voting records into structured formats.
- Used cosine similarity to measure voting alignment and predict political affiliation.
