# 📦 Food Delivery Time Prediction  

## 📌 Project Description  
This project predicts **food delivery times** using machine learning models. The dataset contains features such as **distance, traffic, weather, courier experience, and time of day**.  

Three models were tested: **Random Forest, XGBoost, and LightGBM**.  
The final chosen model is **XGBoost** with the best performance (**R² = 0.810**).  

Explainability analysis with **SHAP** was also conducted to identify the most important features affecting delivery times, providing actionable business insights.  

---

## 📊 Key Steps  
1. **Data Understanding & Cleaning**  
   - Handled missing/unknown values.  
   - Encoded categorical features (traffic, weather, vehicle type).  
   - Treated outliers.  

2. **Feature Engineering**  
   - Created interaction features (Distance × Traffic).  
   - Combined preparation and travel time.  
   - Added peak-hour and bad-weather indicators.  

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of delivery times.  
   - Impact of distance, traffic, and weather.  
   - Correlation heatmaps and interaction plots.  

4. **Modeling & Evaluation**  
   - Algorithms: Random Forest, XGBoost, LightGBM.  
   - Metrics: **R², MAE, RMSE**.  
   - Cross-validation for robustness.  

5. **Model Explainability (SHAP)**  
   - Top features: Distance, Total Preparation + Travel Time, Traffic Level, Weather, Peak Hour.  
   - Dependency plots for interpretability.  

6. **Business Recommendations**  
   - Use XGBoost predictions for accurate ETAs.  
   - Optimize courier assignments using traffic & weather insights.  
   - Retrain the model periodically for operational changes.  

---

## 📈 Results  
- **Best Model**: XGBoost  
- **Test Performance**:  
  - R²: **0.810**  
  - RMSE: **9.236**  
  - MAE: **6.316**  

---

## 🚀 Tech Stack  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **ML Models**: scikit-learn, XGBoost, LightGBM  
- **Explainability**: SHAP  
- **Visualization**: matplotlib, seaborn  

---

## 📂 Repository Structure  
