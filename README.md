Level 1 – Project 1 (EDA) repository.

# Customer Churn Analysis – Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as part of the Codveda Technologies Data Analysis Internship – Level 1 (Basic).

The objective of this project was to perform **Exploratory Data Analysis (EDA)** on a customer churn dataset to understand customer behaviour, identify patterns in the data, detect outliers, analyse distributions, and uncover relationships between numerical variables through statistical analysis and visualisation.

EDA is a critical first step in the data analysis process as it helps analysts understand the structure and quality of data before applying advanced analytics or predictive modelling techniques.

---

## Business Problem

Customer churn is a major concern for telecommunication companies because acquiring new customers is often more expensive than retaining existing ones.

This analysis aims to explore customer usage patterns and identify factors that may be associated with customer churn, providing insights that can support customer retention strategies.

---

## Dataset Information

The dataset contains customer account information, service usage metrics, and churn status.

### Key Features

* Account Length
* International Plan
* Voice Mail Plan
* Number of Voice Mail Messages
* Total Day Minutes
* Total Day Calls
* Total Day Charge
* Total Evening Minutes
* Total Evening Calls
* Total Evening Charge
* Total Night Minutes
* Total Night Calls
* Total Night Charge
* Total International Minutes
* Total International Calls
* Total International Charge
* Customer Service Calls
* Churn (Target Variable)

---

## Objectives

The following tasks were completed:

### Summary Statistics

* Mean
* Median
* Mode
* Standard Deviation

### Distribution Analysis

* Histograms

### Outlier Detection

* Boxplots

### Relationship Analysis

* Scatter Plots

### Correlation Analysis

* Correlation Matrix
* Correlation Heatmap

---

## Tools and Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

The dataset was imported into Python using Pandas and inspected to understand its structure.

### 2. Data Exploration

The dataset was examined using:

* `head()`
* `shape`
* `info()`
* `describe()`

This provided insights into:

* Number of records
* Data types
* Feature distributions
* Missing values

### 3. Statistical Analysis

Descriptive statistics were generated to summarise numerical variables and understand the overall characteristics of the data.

### 4. Data Visualization

Visualisations were created to identify:

* Distribution patterns
* Data spread
* Outliers
* Relationships between variables

### 5. Correlation Analysis

A correlation matrix and heatmap were generated to identify strong and weak relationships between numerical features.

---

## Key Findings

### Customer Distribution

The dataset contains a significantly larger number of customers who remained with the company compared to those who churned.

### Usage Patterns

Customer usage metrics such as:

* Total Day Minutes
* Total Evening Minutes
* Total Night Minutes

show varying levels of customer engagement across the customer base.

### Outliers

Several numerical variables contained outliers, indicating unusually high usage behavior among some customers.

### Strong Correlations

Strong positive correlations were observed between:

* Total Day Minutes and Total Day Charge
* Total Evening Minutes and Total Evening Charge
* Total Night Minutes and Total Night Charge
* Total International Minutes and Total International Charge

These relationships are expected because charges are directly calculated from usage.

### Weak Correlations

Some customer behaviour variables showed weak relationships with churn, suggesting that churn may be influenced by multiple factors rather than a single feature.

---

## Visualisations Included

### Histograms

Used to understand the distribution of numerical features.

### Boxplots

Used to identify outliers and variability within the data.

### Scatter Plots

Used to examine relationships between numerical variables.

### Correlation Heatmap

Used to visualise feature correlations and identify patterns across the dataset.

---

## Project Structure

```text
Level1-Project1-EDA
│
├── churn-bigml.xlsx
├── Customer_Churn_EDA.ipynb
├── README.md
└── images
```

---

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning and Inspection
* Descriptive Statistics
* Data Visualisation
* Correlation Analysis
* Business Insight Generation
* Python Programming
* Jupyter Notebook

---

## Conclusion

This project provided valuable insights into customer usage behaviour and feature relationships within the customer churn dataset. Through exploratory data analysis, key patterns, distributions, and correlations were identified, laying the foundation for future predictive modelling and customer retention analysis.

The project demonstrates practical application of Python-based data analysis techniques and serves as a strong foundation for more advanced machine learning and business intelligence projects.

---

## Author

Adeyemi Victor

Data Analysis Intern | Python | SQL | Power BI | Excel

Completed as part of the Codveda Technologies Data Analysis Internship Program.


