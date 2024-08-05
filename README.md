# Drug Classification using Decision Trees

# Project Overview
This project demonstrates the use of decision trees for classifying drugs based on patient characteristics. The dataset used contains information about patients' age, sex, blood pressure, cholesterol levels, sodium-to-potassium ratio, and the drug prescribed. The goal is to build a model that accurately predicts the type of drug a patient should be prescribed based on their health metrics.

# Table of Contents
Project Motivation
Dataset Description
Steps
1. Data Loading
2. Data Preprocessing
3. Data Splitting
4. Decision Tree Model
5. Model Training
6. Prediction
7. Evaluation
8. Visualization
Results and Insights
Future Work

# Project Motivation
With the increasing amount of patient data available, it's essential to leverage machine learning techniques to assist in medical decision-making. This project aims to build a decision tree model to classify drugs based on patient characteristics, providing a tool that can potentially aid healthcare professionals in prescribing the appropriate medication.

# Dataset Description
The dataset includes the following features:
Age: Age of the patient
Sex: Gender of the patient (M/F)
BP: Blood pressure levels (HIGH/LOW/NORMAL)
Cholesterol: Cholesterol levels (HIGH/NORMAL)
Na_to_K: Sodium-to-potassium ratio in blood
Drug: The drug prescribed (DrugA, DrugB, DrugC, DrugX, DrugY)

# Steps

1. Data Loading
The dataset is loaded from a CSV file using pandas.

2. Data Preprocessing
Categorical features (sex, blood pressure, cholesterol) are encoded using LabelEncoder.

3. Data Splitting
The data is split into training and testing sets using train_test_split.

4. Decision Tree Model
A DecisionTreeClassifier is created with the 'entropy' criterion and a maximum depth of 4.

5. Model Training
The decision tree model is trained on the training data.

6. Prediction
The trained model is used to predict drug classifications for the test data.

7. Evaluation
The model's accuracy is evaluated using metrics.accuracy_score.

8. Visualization
The decision tree is visualized using tree.plot_tree.

# Results and Insights
The decision tree model achieved an accuracy of 98.3% on the test set. The model's performance demonstrates its ability to classify drugs based on patient characteristics accurately. The visualization of the decision tree provides insights into the decision-making process of the model.

# Future Work
1. Model Improvement: Explore other classification algorithms such as Random Forests or Gradient Boosting to improve accuracy.
2. Feature Engineering: Investigate additional features that could improve model performance, such as patient medical history or lifestyle factors.
3. Hyperparameter Tuning: Optimize hyperparameters using techniques like GridSearchCV to enhance model performance.
