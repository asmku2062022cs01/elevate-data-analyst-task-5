# Task 5 — Exploratory Data Analysis (EDA) on Titanic Dataset
# Project Overview

This project performs statistical and visual exploratory data analysis (EDA) on the Titanic dataset to uncover patterns, trends, and factors that influenced passenger survival. Using Python and key data science libraries, the dataset was analyzed through summary statistics and various visualizations.

# Objective

To explore the Titanic dataset and extract insights by:

Understanding dataset structure

Identifying missing values and distributions

Analyzing patterns using visualizations

Studying relationships affecting survival rate

# Dataset Details
Feature	Value
Source	Kaggle – Titanic ML Dataset
Rows	891
Columns	12
Target Variable	Survived
Important Features	Pclass, Sex, Age, Fare, Embarked

# Tools & Libraries Used

| Tool / Library | Purpose                    |
| -------------- | -------------------------- |
| Python         | Programming                |
| Pandas         | Data manipulation          |
| NumPy          | Calculations               |
| Matplotlib     | Data visualization         |
| Seaborn        | Statistical visualizations |
| Google Colab   | Notebook execution         |

# EDA Steps Performed

1️⃣ Data Understanding

Loaded dataset using pandas

Inspected column types using .info()

Summary statistics computed using .describe()

Identified missing values with .isnull().sum()

2️⃣ Univariate Analysis

| Visualization    | Insight                            |
| ---------------- | ---------------------------------- |
| Histogram of Age | Majority passengers aged **20–40** |
| Boxplot of Fare  | **High variance** and **outliers** |

3️⃣ Bivariate Analysis

| Plot                            | Observation                                         |
| ------------------------------- | --------------------------------------------------- |
| Countplot of Sex vs Survived    | **Females survived more than males**                |
| Countplot of Pclass vs Survived | **1st class passengers survived most**              |
| Boxplot of Age vs Survived      | **Younger passengers had slightly better survival** |


4️⃣ Correlation & Multivariate Analysis

Heatmap of numerical features →
‣ Survival negatively correlated with Pclass
‣ Survival positively correlated with Fare

Pairplot → relationship between Survived, Age, Fare, Pclass

# Key Insights

✔ Gender strongly affects survival → Females survived more
✔ Higher-class passengers had higher survival rate
✔ Higher fares linked to higher survival
✔ Children had slightly better survival probability
✔ Cabin data has many missing values → not reliable for analysis

# Repository Structure

titanic-eda-task-5
 ┣ Titanic_EDA.ipynb
 ┣ Titanic_EDA_Report.pdf
 ┣ visuals/  (screenshots/plots if exported)
 ┗ README.md

# Conclusion

The Titanic EDA shows that gender, passenger class, and fare are the most influential factors associated with survival. These findings reflect priority rescue patterns during the disaster and the socioeconomic influence on survival outcomes.



 
