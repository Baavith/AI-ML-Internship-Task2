# AI-ML-Internship-Task2

🫀 Heart Disease Dataset - Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on a heart disease dataset using Python libraries such as **Pandas, Seaborn, Matplotlib, and Plotly**.

## 📊 Objective

The goal is to:
- Understand the structure and distribution of the data
- Generate useful statistical summaries
- Visualize relationships between features
- Identify patterns, trends, or anomalies that may impact heart disease prediction

## 🛠️ Tools Used

- **Python 3.x**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Static visualizations
- **Plotly** – Interactive visualizations
- **NumPy** – Numerical computations

## 📁 Dataset

The dataset used is: `heart_disease_uci.csv`.  
It includes clinical data like age, cholesterol, resting blood pressure, heart rate, and the target variable `num` indicating heart disease severity.

## 📌 Steps Performed

1. **Data Loading & Cleaning**
   - Drop non-numeric and missing values for specific analyses

2. **Summary Statistics**
   - Mean, Median, Standard Deviation, Count, Min/Max

3. **Univariate Visualizations**
   - Histograms with KDE
   - Boxplots to detect outliers

4. **Multivariate Analysis**
   - Correlation matrix heatmap
   - Seaborn pairplot (colored by target variable)
   - Plotly interactive scatter matrix
