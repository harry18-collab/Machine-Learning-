📌 Project Overview

This project focuses on building and evaluating multiple regression models on a cleaned dataset to achieve better generalization and reduce overfitting.

The complete workflow includes:

Data Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering

Model Training

Regularization Techniques

Cross-Validation

Model Evaluation using multiple metrics

The main goal is to compare different regression techniques and show how regularization (Ridge, Lasso, ElasticNet) helps in controlling overfitting and improving model performance.

🧹 Step 1: Data Cleaning

Handled missing values

Fixed data types of columns

Removed unnecessary / highly correlated features

Cleaned column names

Prepared the dataset for modeling

After cleaning, the dataset was saved and used for further analysis and training.

📊 Step 2: Exploratory Data Analysis (EDA)

Performed EDA to understand the data distribution and relationships between features:

Plotted histograms for all numeric features

Analyzed class/target distribution

Checked correlation between features

Visualized important patterns and trends

Identified highly correlated features

This helped in:

Understanding feature importance

Detecting multicollinearity

Making decisions about feature selection

🤖 Step 3: Model Building

Trained multiple regression models on the cleaned dataset:

✅ Models Used:

Linear Regression

Ridge Regression

Lasso Regression

ElasticNet Regression

🎯 Why Regularization?

Linear Regression can overfit on complex data

Ridge, Lasso, and ElasticNet help:

Reduce overfitting

Control model complexity

Improve generalization

Handle multicollinearity

🔁 Step 4: Cross-Validation (CV)

Applied Cross-Validation on:

Ridge Regression

Lasso Regression

ElasticNet Regression

This ensures:

More reliable performance estimation

Better hyperparameter tuning

Reduced risk of overfitting to a single train-test split

📏 Step 5: Model Evaluation

Each model was evaluated using the following metrics:

R² Score (R2 Score)

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

This allows a fair and complete comparison of all models based on:

Accuracy

Error magnitude

🛠️ Tech Stack / Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📌 Conclusion

This project demonstrates a complete machine learning pipeline:

From raw data → cleaned data → EDA → modeling → regularization → evaluation

Shows how regularization + cross-validation improves model robustness

Provides a clear comparison of different regression techniques
