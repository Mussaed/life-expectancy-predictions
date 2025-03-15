# Predicting Life Expectancy Using Multiple Regression

## Overview
This project explores the factors affecting life expectancy across different countries using multiple regression analysis. The study analyzes a global dataset containing socio-economic, healthcare, and environmental variables to predict life expectancy based on key influencing factors.

## Key Findings
**Strong predictors of life expectancy include:**  
- **Density (P/Km²)** – Positively correlated  
- **Maternal Mortality Ratio (MMR)** – Negatively correlated  
- **Out-of-Pocket Health Expenditure (OPHE)** – Negatively correlated  
- **Physicians per Thousand (PPT)** – Positively correlated  
- **Total Tax Rate (TTR)** – Positively correlated  

### Regression Models Used  
1. **Model 1:** Backward elimination based on Variance Inflation Factors (VIF) and p-values  
2. **Model 2:** Stepwise selection using Bayes Information Criterion (BIC)  

Both models satisfied statistical assumptions, with Model 1 achieving 72 percent accuracy and Model 2 achieving 70 percent accuracy in explaining life expectancy variations.

## Dataset & Preprocessing
- Data sourced from 195 countries (after cleaning: 118 countries)  
- 36 features including GDP, healthcare access, education, urbanization, fertility rate, CO2 emissions, and tax rates  
- Applied log transformation for normality and feature selection based on statistical significance  

## Methods & Implementation
- **Data Cleaning & Preprocessing**  
- **Exploratory Data Analysis (EDA)**  
- **Regression Model Building (VIF, BIC)**  
- **Statistical Tests (Shapiro-Wilk, Breusch-Pagan)**  
- **Model Evaluation (R², Mean Squared Error, Diagnostic Plots)**  

## Results & Insights
- Countries with higher tax revenue and physician availability tend to have longer life expectancy  
- High maternal mortality and out-of-pocket health expenses negatively impact life expectancy  
- Further investigation needed into healthcare expenditure policies and tax distribution  

## Future Work
- Expand dataset with more countries and missing data imputation  
- Consider normalization techniques to improve model accuracy  
- Investigate influential data points affecting predictions  
- Explore machine learning models such as Random Forest and Neural Networks for better predictive performance  

This study provides insights into public health policies and contributes to Saudi Arabia's Vision 2030 goal of increasing life expectancy to 80 years.
