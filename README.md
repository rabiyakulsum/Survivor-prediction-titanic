# Titanic Survival Prediction

## Project Overview
This project focuses on predicting which passengers survived the Titanic shipwreck using a Logistic Regression model. By analyzing various features such as age, gender, socio-economic class, and family relationships on board, the goal is to identify key factors that influenced passenger survival. This analysis can provide insights into how different characteristics affected survival probabilities in this tragic event.

## Project Structure
The project follows these key steps:
1. **Data Loading and Preprocessing**: Load the dataset, handle missing values, encode categorical variables, and prepare the data for modeling.
2. **Exploratory Data Analysis (EDA)**: Visualize and analyze the relationships between features and the survival outcome.
3. **Logistic Regression Modeling**: Build a Logistic Regression model to predict survival.
4. **Evaluation and Insights**: Evaluate the model’s performance and interpret findings to identify significant survival factors.

## Dataset Description
The dataset is provided in CSV format and contains the following columns:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger when boarding
- **SibSp**: Number of siblings or spouses aboard the ship
- **Parch**: Number of parents or children aboard the ship
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Goals
- **Analyze** the data to understand factors that influence survival on the Titanic.
- **Develop** a Logistic Regression model to predict passenger survival.
- **Identify** key factors that management could focus on to improve survival prediction accuracy.

## Methodology
1. **Data Preprocessing**: Handle missing values, encode categorical data, and standardize features as needed.
2. **Exploratory Analysis**: Conduct EDA to explore survival rates across features like class, gender, age, and family size.
3. **Modeling**: Train a Logistic Regression model to predict the `Survived` column using input features.
4. **Evaluation**: Assess model performance using metrics such as accuracy, precision, recall, and F1-score.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn (optional, for visualization)

