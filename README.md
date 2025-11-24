# -Housing-Price-Prediction-using-Machine-Learning

A complete end-to-end regression project focused on predicting house prices using machine learning models, feature engineering, and data-driven insights.

📌 Project Overview

This project builds a price-prediction engine using regression algorithms.
The dataset contains residential property attributes such as area, bedrooms, bathrooms, parking, etc.
The objective is to learn how different house features influence price and develop an accurate prediction model.

🧰 Tech Stack

Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Environment: Jupyter Notebook / Google Colab

🔄 Workflow Summary
1. Data Collection

Housing dataset with 13+ features, including structural, categorical, and numerical attributes.

2. Exploratory Data Analysis (EDA)

Distribution analysis of price

Heatmap for correlations

Detecting outliers in features

Checking skewness and transformation need (log-transform)

Visualizing feature relationships (area vs price, rooms vs price)

3. Feature Engineering

Handling categorical variables

One-hot encoding binary features

Optional: log transform of target variable for better model performance

Scaling only numerical features (for models like Linear Regression/SVR)

4. Modeling

Regression algorithms applied:

Linear Regression (baseline)

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Random Forest & GB produced the best results.

5. Evaluation

Metrics used:

MAE

RMSE

R² Score

Visuals generated:

Actual vs Predicted Scatter Plot

Residual Error Plot

6. Prediction & Insights

Model predicts house prices for unseen data

Feature importance used to understand what drives prices

Area, bedrooms, bathrooms, and parking show high influence


📈 Key Findings

Area and Number of rooms strongly correlate with price

Categorical amenities like parking, guestroom, and mainroad affect price significantly

Log-transformation of price dramatically improves model stability

Ensemble models outperform simple linear models
