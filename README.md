# HearthDiseasePrediction

This project focuses on predicting the presence of heart disease using the Heart Disease Dataset. The problem is handled as a binary classification task.

The target variable represents whether an individual has heart disease:

0: No heart disease
1: Heart disease present
Dataset

The dataset contains several health-related features, including:

Age
Sex
Chest pain type
Resting blood pressure
Cholesterol
Fasting blood sugar
Electrocardiographic results
Maximum heart rate
Exercise-induced angina

These variables are used as input features to predict the target variable.

Data Preprocessing

Before model training, the dataset was examined and prepared for classification.

The main preprocessing steps were:

Loading the dataset with Python
Checking column names and data types
Checking missing values
Separating independent variables and the target variable
Splitting the dataset into training and test sets
Scaling numerical features

The dataset was divided into:

80% training data
20% test data

Numerical features were standardized using StandardScaler because the variables were measured on different scales.

Models

Four ensemble learning methods were used in this project:

Random Forest
AdaBoost
Gradient Boosting
Voting Classifier

These models were trained on the same classification problem and their performances were compared using the test dataset.

Workflow
Heart Disease Dataset
        ↓
Data Exploration
        ↓
Data Preprocessing
        ↓
Train-Test Split
        ↓
Feature Scaling
        ↓
Model Training
        ↓
Random Forest
AdaBoost
Gradient Boosting
Voting Classifier
        ↓
Model Evaluation
Technologies
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Objective

The main objective of this project is to compare different ensemble learning algorithms for heart disease prediction and evaluate their performance on previously unseen test data.
