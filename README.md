# Titanic Survival Analysis (Cleaned Dataset)

This repository contains a **cleaned version of the Titanic dataset**, prepared for data analysis and machine learning tasks, such as predicting passenger survival.

## Dataset Overview

The dataset includes the following features:

- **PassengerId** – Unique ID for each passenger  
- **Survived** – Survival status (0 = No, 1 = Yes)  
- **Pclass** – Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Name** – Full name of the passenger  
- **Sex** – Gender of the passenger  
- **Age** – Age in years (missing values imputed)  
- **SibSp** – Number of siblings/spouses aboard  
- **Parch** – Number of parents/children aboard  
- **Ticket** – Ticket number  
- **Fare** – Passenger fare  
- **Cabin** – Cabin number (cleaned for consistency)  
- **Embarked** – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

## Cleaning and Outlier Detection

- Handled missing values in **Age**, **Cabin**, and **Embarked**  
- Removed duplicate rows  
- Standardized categorical values (e.g., Gender, Embarked)  
- **Outliers detected using two methods:**  
  1. **Visualization with Matplotlib** – boxplots to spot extreme values  
  2. **IQR (Interquartile Range) Method** – statistical approach to remove outliers  

The dataset is now cleaned and ready for **exploratory data analysis and machine learning**.

## Usage

You can use this dataset for:

- Data exploration and visualization  
- Outlier analysis and preprocessing  
- Machine learning models to predict survival  

## File

- `titanic_cleaned.csv` – Cleaned and ready-to-use dataset  

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  

