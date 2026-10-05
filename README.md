# Titanic EDA – Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to identify patterns and relationships between passenger characteristics and survival outcomes.

The analysis focuses on factors such as **gender, passenger class, age, fare, family size, and port of embarkation**.

## 🎯 Objectives

- Understand the structure and characteristics of the Titanic dataset.
- Identify missing values and data quality issues.
- Explore factors associated with passenger survival.
- Analyze relationships between passenger demographics and survival.
- Present findings using clear statistical summaries and visualizations.

## 📊 Dataset

The dataset contains information about Titanic passengers, including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Ticket
- Fare
- Cabin
- Port of embarkation

A derived **FamilySize** variable was also created using:

`FamilySize = SibSp + Parch + 1`

## 🔎 Analysis Performed

The notebook includes analysis and visualizations covering:

- Dataset structure and descriptive statistics
- Missing value analysis
- Duplicate record checking
- Passenger gender distribution
- Overall survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution and survival
- Fare distribution and survival
- Correlation analysis
- Survival by embarkation port
- Family size distribution
- Survival by family size
- Survival rate comparisons

## 📈 Key Findings

- The overall survival rate in the analyzed dataset was approximately **36.36%**.
- Survival rates differed considerably between **male and female passengers**.
- **Passenger class** was associated with differences in survival outcomes.
- The dataset contained substantial missing values in the **Cabin** variable.
- Family size and embarkation port were also explored as potential factors related to survival.

## 🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

## 📁 Project Files

| File | Description |
|---|---|
| `Titanic_EDA.ipynb` | Jupyter Notebook containing the complete EDA and visualizations |
| `titanic_eda.csv` | Processed dataset used for the analysis |

## 🚀 How to Run

1. Clone this repository.
2. Open `Titanic_EDA.ipynb` using Jupyter Notebook or JupyterLab.
3. Make sure the required Python libraries are installed.
4. Run the notebook cells from beginning to end.



