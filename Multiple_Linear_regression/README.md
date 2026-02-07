# Multiple Linear Regression (Economic Index Dataset)

## Overview
This project focuses on implementing **Multiple Linear Regression (MLR)** on an economic indicators dataset to understand how multiple input features collectively influence a target variable.

## Dataset
- **Name**: Economic Index Dataset  
- **Description:** The dataset contains multiple economic indicators (features) that are used to predict a dependent variable.  
- **Preprocessing:**  
  - Handled missing values (if any)  
  - Performed basic feature scaling / normalization (where required)  
  - Split data into training and testing sets  

## Implementation
- Implemented Multiple Linear Regression model  
- Used **Ordinary Least Squares (OLS)** for parameter estimation  
- (Optional) Compared results with scikit-learn implementation  
- Evaluated model performance using:
  - Mean Squared Error (MSE)  
  - R² score  

##  Files
- `multiple_linear_regression.ipynb` – Notebook with complete implementation and results  
- `economic_index.csv` – Dataset used for training and testing  
- `README.md` – Documentation for this module  

## Key Learnings
- How Multiple Linear Regression extends Simple Linear Regression to multiple features  
- Understanding feature importance and coefficients  
- Impact of multicollinearity on regression performance  
- Importance of data preprocessing before training  

## Results
- Trained an MLR model to capture relationships between economic indicators and the target variable  
- Observed how different features contribute to the prediction  
- Analyzed model fit using error metrics and R² score  

## Next Steps
- Try regularization techniques (Ridge, Lasso)  
- Perform feature selection  
- Validate model on a different dataset  
- Compare performance with tree-based models
