# Titanic Survival Prediction with Deep Learning

This project aims to predict the survival of passengers aboard the Titanic using a deep learning model. The dataset used in this project is sourced from Kaggle's Titanic dataset.

## Project Overview

The Titanic dataset contains information about the passengers who were aboard the Titanic. The goal of this project is to develop a deep learning model that can accurately predict which passengers survived the disaster.

## Data Dictionary

- **survival**: Survival status (0 = No, 1 = Yes)
- **pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **sex**: Gender of the passenger
- **age**: Age of the passenger (in years)
- **sibsp**: Number of siblings/spouses aboard the Titanic
- **parch**: Number of parents/children aboard the Titanic
- **ticket**: Ticket number
- **fare**: Passenger fare
- **cabin**: Cabin number
- **embarked**: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Dataset

The dataset can be downloaded from [Kaggle's Titanic Dataset](https://www.kaggle.com/c/titanic/data).

## Project Workflow

1. **Data Import and Exploration:** 
   - Importing the dataset and understanding the data structure.
   - Checking for missing values and performing exploratory data analysis (EDA).

2. **Data Preprocessing:**
   - Handling missing values for 'Age', 'Fare', 'Cabin', and 'Embarked' columns.
   - Encoding categorical variables and feature scaling.
   - Engineering new features such as 'FamilySize', 'Ticket_Length', and 'Cabin_Number'.

3. **Model Development:**
   - Building a deep learning model using TensorFlow and Keras.
   - Training the model on the training dataset and evaluating its performance.

4. **Model Evaluation:**
   - Evaluating model accuracy and loss using validation data.
   - Fine-tuning the model parameters to improve performance.

## Results

**Data Loading and Processing:** The Titanic dataset was preprocessed to handle missing data and transform categorical variables.

**Model Creation:** A deep learning model was built and trained using TensorFlow and Keras.

**Model Training and Evaluation:** The model was trained and evaluated using training and test datasets. After completing the training, the model's performance on the validation dataset was assessed, showing an accuracy of 85%. This accuracy represents a significant improvement compared to the results obtained using simple machine learning algorithms.

## Notes

This project is a continuation of the Titanic Survival Prediction project, which addressed the same problem using machine learning. It aims to test the applicability and performance of deep learning techniques.
The dataset and code used in this project are shared as open source and are open for further development and contributions.