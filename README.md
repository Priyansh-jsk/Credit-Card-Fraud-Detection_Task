# Credit Card Fraud Detection

This repository contains machine learning models for detecting fraud credit card.

## Dataset

The project uses the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)


📘 Documentation:

1. Importing Libraries: The code begins by importing necessary Python libraries:

2. Loading the Dataset: The dataset is read from a CSV file (creditcard.csv) using pandas. It contains real transactions with features like Time, Amount, and anonymized features V1 to V28.

3. Basic Data Exploration

4. Class Distribution: Plots how many transactions are fraudulent (1) vs. non-fraudulent (0). It shows that the dataset is imbalanced – very few fraud cases.

📊 5. Data Visualization: Uses histograms to understand distribution of features.

Visualizes class distribution using a pie chart.

Checks correlation of features with the Class label using a heatmap.

🧹 6. Data Preprocessing: Separates features (X) and target (y). Splits data into training and testing sets using train_test_split.

7. Model Training: Trains multiple machine learning models:

- Logistic Regression

- XGBoost

8. Model Evaluation:

For each model: Predicts on test data.

Calculates accuracy, precision, recall, F1-score.

Prints confusion matrix.

Visualizes the confusion matrix with heatmaps.
