📌 Project Overview

This project demonstrates the complete machine learning workflow on a synthetically generated dataset.
The goal was to understand how model complexity affects performance by:

Training a Linear Regression model

Evaluating performance using R² score

Extending the model to Polynomial Regression (degree = 2)

Observing improvement in model fit

Predicting on new unseen input values

Implementing the entire workflow using Scikit-learn Pipeline for clean preprocessing and modeling

🧪 Dataset Creation

Instead of using a prebuilt dataset, a custom dataset was generated using NumPy:

Input feature X sampled from a uniform range

Target Y generated using a quadratic equation with added Gaussian noise

This helps in clearly visualizing:

Underfitting with Linear Regression

Better fitting with Polynomial Regression

⚙️ Models Implemented
1️⃣ Linear Regression

Trained on generated dataset

R² score computed on test set

Result: Linear model fails to capture the non-linear relationship

2️⃣ Polynomial Regression (Degree = 2)

Polynomial features created

Linear Regression applied on transformed features

R² score improves significantly

Shows how non-linear patterns are captured better

🔁 Pipeline Implementation

A Scikit-learn Pipeline was used to combine:

Polynomial Feature Transformation

Linear Regression Model

This ensures:

Clean and reusable ML workflow

No data leakage

Same preprocessing during training and prediction

Pipeline:
[ PolynomialFeatures → LinearRegression ]

📊 Visualization

The following were visualized:

Training data points

Test data points

Regression curve for different polynomial degrees

Comparison between Linear and Polynomial model fitting

This helps visually understand:

Underfitting vs Good fit

Effect of polynomial degree

📈 Evaluation Metric

R² Score (Coefficient of Determination) was used to evaluate model performance:

Linear Regression → Lower R²

Polynomial Regression (degree 2) → Higher R²

This shows that increasing model complexity (to an extent) improves performance on non-linear data.

🔮 Prediction on New Data

New unseen input values were generated using linspace, and predictions were made using the trained pipeline model.
The predicted curve was plotted along with training and test points to visualize generalization.

🛠️ Tech Stack

Python

NumPy

Matplotlib

Scikit-learn

🚀 Learning Outcome

Through this project, I learned:

How to generate and visualize synthetic datasets

Difference between Linear and Polynomial Regression

How R² score reflects model performance

How model complexity affects bias–variance tradeoff

How to build clean ML pipelines using Scikit-learn

How to visualize model predictions and generalization