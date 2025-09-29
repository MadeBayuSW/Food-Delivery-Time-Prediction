# Food-Delivery-Time-Prediction
📌 Project Description

This project focuses on predicting food delivery times using machine learning models. The dataset contains order details such as distance, traffic conditions, weather, courier experience, and time of day. The goal is to build a predictive model that helps optimize courier assignment, improve customer satisfaction, and enhance operational efficiency.

Several models were tested — Random Forest, XGBoost, and LightGBM — with XGBoost selected as the final model due to its strong accuracy (R² = 0.81) and generalization performance.

Additionally, SHAP explainability analysis was conducted to understand key features influencing delivery times, providing actionable business insights.

📊 Key Steps

Data Understanding & Cleaning

Handled missing/unknown values.

Encoded categorical features (traffic, weather, vehicle type).

Removed/treated outliers.

Feature Engineering

Created interaction features (e.g., Distance × Traffic).

Combined preparation and travel time.

Added peak-hour and bad-weather indicators.

Exploratory Data Analysis (EDA)

Analyzed distribution of delivery times.

Studied impact of distance, traffic, and weather.

Correlation and interaction plots.

Modeling & Evaluation

Random Forest, XGBoost, LightGBM.

Evaluation metrics: R², MAE, RMSE.

Cross-validation for robustness.

Model Explainability (SHAP)

Identified top features impacting delivery times.

Visualized feature importance & dependencies.

Business Recommendation

Use model predictions to optimize courier assignments.

Factor in traffic, weather, and peak hours for better ETA accuracy.

Retrain model periodically to adapt to changing conditions.

📈 Results

Best Model: XGBoost

Test Performance:

R²: 0.810

RMSE: 9.236

MAE: 6.316

Key Features Impacting Delivery Time

Distance (km)

Total Preparation + Travel Time

Traffic Level

Weather Conditions

Peak Hours

🚀 Tech Stack

Python: pandas, numpy, matplotlib, seaborn

ML Models: scikit-learn, XGBoost, LightGBM

Explainability: SHAP

Visualization: matplotlib, seaborn
