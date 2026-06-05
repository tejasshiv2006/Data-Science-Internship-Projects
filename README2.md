# Exploratory Data Analysis (EDA) on Titanic Dataset

## Objective

The objective of this project is to analyze the Titanic dataset to uncover patterns, trends, and factors that influenced passenger survival.

## Dataset Overview

The Titanic dataset contains information about passengers aboard the RMS Titanic, including demographic details, ticket information, passenger class, and survival status.

### Key Features

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

## Data Exploration

### Statistical Summary

Statistical summaries were generated using the `describe()` function to understand the distribution of numerical variables such as Age, Fare, SibSp, and Parch.

### Missing Value Analysis

Missing values were identified using `isnull().sum()`.

Observations:

* Age contained missing values.
* Cabin contained a large number of missing values.
* Embarked contained a few missing values.

### Data Cleaning

* Missing Age values were filled using the median.
* Missing Embarked values were filled using the mode.
* Cabin column was removed due to excessive missing values.

## Visualizations and Insights

### Survival Distribution

A count plot showed the number of passengers who survived versus those who did not survive.

Insight:

* More passengers did not survive than survived.

### Survival by Gender

A count plot comparing gender and survival status was created.

Insight:

* Female passengers had a significantly higher survival rate than male passengers.

### Age Distribution

A histogram was used to visualize passenger age distribution.

Insight:

* Most passengers were between 20 and 40 years old.

### Correlation Analysis

A correlation heatmap was generated to identify relationships between numerical variables.

Insights:

* Passenger class (Pclass) showed a negative correlation with survival.
* Fare showed a positive correlation with survival.
* Sex was one of the strongest factors influencing survival.

## Key Influencing Factors

The analysis identified the following factors as most influential:

1. Gender (Sex)
2. Passenger Class (Pclass)
3. Fare
4. Age

These variables showed strong relationships with passenger survival outcomes.

## Conclusion

The Exploratory Data Analysis revealed important patterns in the Titanic dataset. Female passengers and passengers traveling in higher classes had greater chances of survival. Fare and age also influenced survival probabilities. Through statistical summaries, visualizations, and correlation analysis, valuable insights were obtained that can support predictive modeling and machine learning applications.

## Learning Outcomes

* Performed data cleaning and preprocessing.
* Generated statistical summaries.
* Created meaningful visualizations.
* Identified correlations and influential factors.
* Developed analytical thinking and data exploration skills.
