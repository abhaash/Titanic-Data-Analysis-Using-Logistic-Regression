**Titanic Survival Prediction**
This repository contains Python code for predicting passenger survival on the Titanic. The dataset used for this project is 'titanic.csv'.

**Project Overview**
The goal of this project is to build a predictive model to determine whether a passenger survived or not based on various features such as age, gender, ticket class, and embarkation port.

**Data Wrangling**
The data wrangling process involves cleaning and preparing the dataset for modeling.

Missing Values: Checked for missing values in the dataset and dropped the 'Cabin' column due to a high number of missing values.
Handling NaN Values: Removed rows with missing values.
One-Hot Encoding: Used one-hot encoding to convert categorical variables like 'Sex', 'Embarked', and 'Pclass' into numerical format.
Feature Selection: Dropped unnecessary columns like 'PassengerId', 'Name', 'Ticket', and 'Pclass'.
**Training the Model**
Split Data: Split the dataset into training and testing sets using a 70-30 split.
Logistic Regression: Utilized logistic regression as the classification algorithm.
Model Training: Fit the logistic regression model to the training data.
Model Evaluation: Evaluated the model using classification reports, confusion matrices, and accuracy scores.
**Dependencies**
pandas
numpy
seaborn
matplotlib
scikit-learn
**Usage**
Clone this repository to your local machine.
Ensure you have the required dependencies installed.
Download the 'titanic.csv' dataset and place it in the same directory as the code.
Run the code to train and evaluate the model.

python titanic_survival_prediction.py

**Results**
The code provides a predictive model for Titanic passenger survival. It generates classification reports, confusion matrices, and accuracy scores to evaluate the model's performance.

**Contributors**
Abhaash Kumar Bhiwaniya
Feel free to contribute to this project by improving the model, adding new features, or enhancing the documentation.





