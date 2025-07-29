This project implements a neural network-based machine learning pipeline to detect fraudulent credit card transactions using the popular Credit Card Fraud Detection dataset. It demonstrates data preprocessing, class imbalance handling, model building, training, and evaluation.

Features
Data loading and preprocessing, including scaling of transaction amount and normalization of transaction time.
Handling missing values.
Addressing class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
Splitting data into training and test sets.
Building a deep learning model with TensorFlow/Keras, including layers for normalization and dropout for regularization.
Model training with early stopping and batch training.
Model evaluation using accuracy, classification report, and confusion matrix visualization.

Dataset
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
It includes features like Time, Amount, and 28 anonymized features (V1 to V28).
The target variable Class indicates fraudulent (1) or non-fraudulent (0) transactions.
Dataset source: Credit Card Fraud Detection

Results
The model achieves good performance in detecting fraudulent transactions despite class imbalance.
Evaluation metrics include precision, recall, F1-score, and accuracy.
Confusion matrix visually demonstrates the model’s classification results.

Future Work
Experiment with different model architectures and hyperparameters.
Apply other resampling or anomaly detection techniques.
Use additional feature engineering for better accuracy.
Deploy the model as a web API for real-time fraud detection.

