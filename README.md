# House Price Prediction — Linear Regression Models

This project develops multiple linear regression models to predict housing prices using engineered features, non-linear terms, and statistical diagnostics. The goal is to understand key drivers of home value and improve model performance through iterative refinement.

## 🏡 Problem Statement

How accurately can we predict home prices using a combination of numerical, categorical, and engineered features?

## 🧠 Approach

- Built baseline OLS regression models using Statsmodels
- Engineered non-linear terms and interaction features
- Applied log-transformation to stabilize variance and improve model fit
- Encoded categorical variables using one-hot encoding
- Conducted diagnostic analysis to detect:
  - Multicollinearity
  - Skewness
  - Heteroscedasticity
  - Underprediction patterns
- Iteratively refined the model structure based on diagnostics

## 📊 Results

- **R² improved from 0.20 → 0.51** after feature engineering and log-transformation  
- Residual plots revealed improved variance stability  
- Model captured key predictors such as square footage, location, and condition  
- Visualizations included:
  - Residual vs. fitted plots  
  - Distribution comparisons  
  - Feature importance insights  

## 🛠 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Statsmodels  
- Scikit-learn  
- Seaborn  
- Matplotlib  
- Google Colab

## 📁 Files

- `House_Price_Prediction.ipynb`: Full notebook with models, diagnostics, and visualizations  
- `README.md`: Project overview and documentation

## 📎 Link to Colab Notebook

(Insert your Colab link here once uploaded)

## 📌 Author

**Oluwasunmisola Odeyemi**  
Aspiring Data Analyst / Entry-Level Data Scientist  
[LinkedIn](https://linkedin.com/in/oluwasunmisola-odeyemi) • [GitHub](https://github.com/suOdeyemi)
