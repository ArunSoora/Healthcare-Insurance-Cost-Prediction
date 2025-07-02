# Healthcare Insurance Cost Prediction Using Statistical Modeling

This project investigates the relationship between individual characteristics and health insurance charges using statistical and machine learning methods in R.

## Project Overview

We aimed to develop a predictive model that estimates insurance costs based on age, BMI, smoking status, region, and number of children. By applying regression models and statistical hypothesis testing, the study provides insights for pricing strategies in the health insurance domain.

## Objectives

- Explore how demographic and lifestyle factors influence health insurance premiums.
- Use exploratory data analysis (EDA), hypothesis testing, and multiple regression to identify significant predictors.
- Evaluate the accuracy of linear and multiple linear regression models using R.

## Research Questions

- Do age, BMI, and smoking significantly affect health insurance charges?
- Can we build a predictive model with improved pricing accuracy using demographic and behavioral variables?

## Dataset

- Source: [Kaggle - Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Records: 1,338 individuals with variables such as age, BMI, smoking status, region, and charges

## Methodology

1. **Data Collection and Cleaning**: Transformed categorical variables, encoded factors, removed anomalies.
2. **Exploratory Data Analysis**: Used scatter plots, histograms, and boxplots to explore relationships.
3. **Statistical Tests**:
   - Shapiro-Wilk test for normality
   - Chi-square test for categorical influence
   - T-tests and Kruskal-Wallis for group comparisons
4. **Modeling**:
   - Spearman Correlation
   - Simple Linear Regression
   - Multiple Linear Regression (R² = 0.78)

## Key Findings

- Smoking status had the strongest correlation (0.66) with insurance charges.
- Age and BMI also significantly influenced cost.
- The multiple regression model performed significantly better than the simple model.
- Region and gender were not statistically significant predictors.

## Repository Contents

| File Name                                      | Description |
|-----------------------------------------------|-------------|
| `Healthcare_Insurance_Cost_Prediction_Report.pdf` | Full project report including methods, analysis, and model results |
| `notebooks/` (to be added)                    | R scripts or markdown notebooks for analysis |
| `data/` (to be added)                         | Cleaned or raw dataset if permitted by license |

## Team Members

- Arun Kumar Soora  
- Kalyan Raj Chinigi  
- Pallavi Vandanapu  
- Srihari Myla Venkata  
- Yugala Ramula  

## Contact

For any inquiries, please contact Arun Kumar Soora via [LinkedIn](https://www.linkedin.com/in/arun-kumar-soora).
