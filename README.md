# ITI-Data-Analysis-Statistics-Assignment
Exploratory Data Analysis &amp; Inferential Statistics on Tips Dataset - ITI Data Analysis Bootcamp.


This repository contains a comprehensive statistical data analysis project on the **Tips Dataset**, completed as part of the **Information Technology Institute (ITI) Data Analysis Bootcamp**.

---

##  Project Overview
The main goal of this assignment is to perform end-to-end Exploratory Data Analysis (EDA) and apply fundamental descriptive & inferential statistical methods using Python.

The project walks step-by-step through dataset exploration, summary statistics, data visualizations, measure of spread, correlation analysis, linear regression modeling, and sampling distributions (Central Limit Theorem).

---

##  Key Statistical Topics Covered

1. Data Inspection & Cleaning: Checking data types, non-null values, and basic structures.
2. Frequency Analysis: Value counts for categorical columns (`sex`, `smoker`, `day`, `time`, `size`).
3. Central Tendency Measures: Mean, Median, and Mode calculation for `total_bill`, `tip`, and `size`.
4. Measures of Spread & Variability: Range, Variance, and Standard Deviation.
5. Percentiles & Quartiles: Q1, Q2 (Median), Q3, and Interquartile Range (IQR).
6. Outlier Detection: Visualizing distributions using Boxplots.
7. Distribution & Skewness: Analyzing shape via Histograms, KDE plots, and Skewness coefficients.
8. Group Comparisons: Aggregating metrics across categories (Day, Sex, Time, Smoker).
9. Bivariate Analysis: Covariance, Pearson Correlation Coefficient, and Scatter Plots.
10. Linear Regression: Polyfit modeling, slope, intercept, $R^2$ determination, and predictive           evaluation for custom bill amounts.
11. Sampling Distributions: Simulating 100 random samples ($n=30$) to demonstrate the Central Limit Theorem.

---

##  Tech Stack & Libraries
- Language: Python 3.14
- Environment: Jupyter Notebook / VS Code
- Libraries Used:
  - `pandas` - Data manipulation & analysis
  - `numpy` - Numerical operations & linear regression modeling
  - `matplotlib` - Static plotting and visualizations
  - `seaborn` - Advanced statistical visual styling

---

##  Repository Structure
├── Statistics_and_Data_Analysis_Tips_Dataset.ipynb    # Main Jupyter Notebook with code & outputs
├── tips.xlsx                                          # Dataset file
└── README.md                                          # Project documentation


Key Findings & Insights
- Both `total_bill` and `tip` exhibit **right-skewed (positively skewed)** distributions where $\text{Mean} > \text{Median}$.
- `total_bill` demonstrates significantly higher variance and standard deviation compared to `tip` due to its wider range of values.
- There is a **moderate positive correlation** ($r \approx 0.68$) between `total_bill` and `tip`.
- The sampling distribution of mean tips approaches a **normal distribution**, reinforcing the Central Limit Theorem.

🎓 Acknowledgments
Developed during the ITI Data Analysis Bootcamp
