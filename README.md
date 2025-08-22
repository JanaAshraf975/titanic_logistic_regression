# titanic-logistic-regression
 A Machine Learning project using the Titanic dataset to predict passenger survival based on features such as age, gender, passenger class, and family size. The project applies Logistic Regression for binary classification, with full steps of EDA (Exploratory Data Analysis), preprocessing, model training, and evaluation. 
itanic Survival Prediction – Logistic Regression

Project Overview

This project predicts the survival of passengers aboard the Titanic using Logistic Regression. The workflow involves data exploration, preprocessing, visualization, feature engineering, and model evaluation to understand the key factors affecting survival.

Dataset

The dataset is the Titanic dataset
, which contains information about passengers:

Passenger details: ID, Name, Sex, Age

Travel information: Pclass, Ticket, Cabin, Embarked

Family aboard: SibSp (siblings/spouses), Parch (parents/children)

Fare and survival status (target variable: Survived)

Project Workflow
1. Data Exploration

Inspect the dataset for structure, missing values, and duplicates

Analyze summary statistics and distributions of features

2. Data Visualization

Explore survival rates using count plots

Compare survival by Sex and Passenger Class

Examine age distribution and detect outliers

3. Data Preprocessing

Handle missing values in Age and Embarked

Drop irrelevant columns (e.g., PassengerId, Name, Ticket, Cabin)

Encode categorical variables for model compatibility

Detect and cap outliers to reduce their impact

4. Train-Test Split & Scaling

Split the dataset into training and testing sets

Apply feature scaling to normalize numerical values

5. Model Training

Train a Logistic Regression model on the preprocessed dataset

6. Evaluation

Evaluate model performance using accuracy, precision, recall, F1-score

Visualize results with a confusion matrix

Test predictions on sample data points

Key Findings

-Gender and passenger class are strong indicators of survival

-Age and family size also affect survival probability

-Logistic Regression achieves reliable performance in predicting survival

Conclusion
This project demonstrates how data preprocessing, feature engineering, and Logistic Regression can be combined to predict survival outcomes. The workflow can be extended to other classification problems with similar structured datasets.

This project demonstrates how data preprocessing, feature engineering, and Logistic Regression can be combined to predict survival outcomes. The workflow can be extended to other classification problems with similar structured datasets.
