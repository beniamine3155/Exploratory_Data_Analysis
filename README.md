# Exploratory Data Analysis in Python

This project demonstrates the step-by-step process of performing Exploratory Data Analysis (EDA) on a dataset using Python. It includes data cleaning, transformation, and visualization techniques to extract meaningful insights.

---

## Project Overview

The dataset contains information about various car models with features such as engine details, fuel type, transmission type, vehicle size, and MSRP (Manufacturer's Suggested Retail Price).  
EDA helps in understanding the dataset by identifying patterns, anomalies, missing values, and relationships between variables.

---

## Key Features

1. **Data Inspection**
   - Loading the dataset into a Pandas DataFrame.
   - Displaying the top and bottom rows of the dataset.
   - Checking data types and shape.

2. **Data Cleaning**
   - Dropping irrelevant columns (`Engine Fuel Type`, `Number of Doors`).
   - Renaming columns for clarity (e.g., `Engine HP` -> `HP`).
   - Removing duplicate rows.
   - Handling missing values by dropping rows with null values.

3. **Data Visualization**
   - Box plots for detecting outliers in `MSRP`, `HP`, and `Cylinders`.
   - Scatter plots to analyze relationships between numerical features.
   - Histograms for understanding feature distributions.

4. **Dataset Summary**
   - Final dataset shape: **7736 rows x 14 columns**.
   - No missing values or duplicate rows after cleaning.

---

## Getting Started

### Prerequisites

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`

Install the required libraries using:
```bash
pip install numpy pandas matplotlib seaborn
