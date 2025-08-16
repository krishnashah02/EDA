# 🛳️ Titanic Dataset – Exploratory Data Analysis (EDA)
This repository contains **Exploratory Data Analysis (EDA)** on the Titanic dataset.  
The goal is to clean the dataset, analyze patterns, visualize distributions, and extract insights that explain survival outcomes.  

EDA Steps Performed

Data Cleaning
Removed duplicates
Handled missing values (Age, Fare, Embarked, Gender)
Converted invalid entries (?, **) to NaN
Univariate Analysis
Distribution of Age, Fare, Gender, Pclass, Survived

Bivariate Analysis

Survival by Gender
Survival by Pclass
Age vs Survival
Fare vs Survival

Multivariate Analysis

Correlation heatmap
Pairwise plots
Outlier & Skew Check
Detected outliers in Fare
Found skewness in Fare (4.35) and mild skew in Age (0.41)

Key Insights

Females survived at higher rates than males
1st class passengers had the highest survival
Higher fares → better chance of survival
Younger passengers had slightly better outcomes

📊 Results & Deliverables

Notebook: Titanic.ipynb
Report: Summarized findings with visuals (PDF in report/ folder)
Figures: Plots saved in figures/ folder

Conclusion

EDA reveals that gender and class are the most important predictors of survival, followed by fare and age.
These findings set the foundation for feature engineering and predictive modeling.
