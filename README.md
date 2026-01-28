# TripleTen-Sprint-12-Project
🚗 Rusty Bargain: Used Car Price Prediction
📝 Project Overview

This project focuses on building predictive models to estimate the market value of used cars for Rusty Bargain, a used car sales service. Using historical data containing technical specifications, trim versions, and prices, the goal is to develop models that are accurate, fast, and efficient to train.

The project emphasizes model quality, prediction speed, and training efficiency, providing Rusty Bargain with actionable insights for their new app.

📊 Dataset Description

The dataset includes:

Technical specifications (e.g., engine type, mileage, year)

Trim and model versions

Historical sale prices (target variable)

This allows for supervised regression modeling, with price prediction as the target.

🎯 Objectives

Explore and preprocess the dataset

Train multiple regression models, including:

Linear Regression (sanity check)

Tree-based models (Decision Tree, Random Forest)

Gradient Boosting (LightGBM, optionally CatBoost/XGBoost)

Tune hyperparameters for optimal performance

Evaluate models based on:

RMSE for prediction quality

Training time and prediction speed

Compare models to identify the best trade-off between accuracy and efficiency

🔍 Key Tasks Performed
🧹 Data Preparation

Loaded and inspected the dataset

Encoded categorical features for algorithms requiring numeric input (e.g., XGBoost)

Handled missing values and ensured data consistency

🔧 Model Development

Implemented Linear Regression for sanity checks

Trained Decision Tree and Random Forest with hyperparameter tuning

Trained LightGBM models with multiple parameter sets

Optionally tested CatBoost and XGBoost

Recorded training time and prediction speed using Jupyter Notebook tools

📊 Model Evaluation

Evaluated all models using RMSE

Compared training time, prediction speed, and overall accuracy

Determined trade-offs for practical deployment in the Rusty Bargain app

🛠️ Tools & Technologies

Python

Pandas & NumPy for data manipulation

Scikit-learn for regression and evaluation

LightGBM, XGBoost, CatBoost for gradient boosting

Matplotlib & Seaborn for visualization

Jupyter Notebook

📈 Final Deliverables

Cleaned and prepared dataset ready for modeling

Multiple regression and gradient boosting models with hyperparameter tuning

Performance metrics including RMSE, training time, and prediction speed

Visualizations comparing model performance

Recommendations on the best model for Rusty Bargain's app

✅ Success Criteria

A successful project demonstrates:

Accurate car price predictions with low RMSE

Efficient model training and fast prediction

Proper handling of categorical features and hyperparameter tuning

Clear comparison of multiple model approaches

Reproducible and well-documented analysis

📌 Conclusion

This project illustrates the application of machine learning to real-world pricing and market prediction problems. By comparing multiple models and analyzing trade-offs between accuracy, speed, and efficiency, Rusty Bargain can confidently integrate a predictive pricing tool into their app to enhance customer experience and attract new users.
