# NBA Wins Regression Models (Team: Golden State Warriors)

You are a data analyst for an NBA team with access to historical performance data. The goal is to build regression models that predict the number of **regular-season wins** from performance metrics, then translate results into actionable insights for coaches and management.

## 📊 Project Overview
- **Objective:** Predict team wins using simple and multiple linear regression.
- **Team:** Golden State Warriors (same team used across all three projects).
- **Dataset:** FiveThirtyEight NBA Elo dataset (cleaned for course use).

## 🔬 Analyses Performed
### Scatterplots & Correlation
- Created scatterplots of wins vs. candidate predictors.
- Computed correlation coefficients to identify strongest linear relationships.

### Simple Linear Regression
- Fit a simple model using the strongest single predictor.
- Checked slope significance and R²; interpreted coefficients in basketball terms.

### Multiple Regression
- Built a multivariate model with several performance metrics.
- Reviewed the correlation matrix, addressed multicollinearity, and evaluated model fit (R²/Adj. R²), residuals, and assumptions.

## 🛠 Tools & Libraries
- Python 3, Jupyter Notebook  
- pandas, numpy  
- matplotlib  
- statsmodels or scikit-learn  

## 🧠 Practical Implications
- Identify which metrics most strongly drive wins.
- Provide evidence-based levers for coaching (e.g., pace, 3PT efficiency, turnover control).
- Use model predictions to set performance targets and track progress.