

---

# 📱 **Smartphone Specifications & Prie Predication"

### 📌 **Overview**  
This dataset contains **detailed specifications** and **official launch prices** of various smartphone models from leading manufacturers. It provides valuable insights into **pricing trends, hardware advancements, and brand competitiveness** across different regions.  

💡 **Key Focus:** Analyzing **smartphone pricing** across countries and predicting prices using **machine learning regression models**.  

---

## 📊 **Dataset Features**  
Each row represents a **smartphone model**, with details such as:  

- **📌 Company Name** – The smartphone brand (e.g., Apple, Samsung).  
- **📌 Model Name** – The specific smartphone model.  
- **📌 Mobile Weight** – The phone's weight (grams).  
- **📌 RAM** – Memory capacity (GB).  
- **📌 Front Camera** – Resolution of the front camera (MP).  
- **📌 Back Camera** – Resolution of the primary rear camera (MP).  
- **📌 Processor** – The chipset used (e.g., A17 Bionic, Snapdragon 8 Gen 2).  
- **📌 Battery Capacity** – Battery size (mAh).  
- **📌 Screen Size** – Display size (inches).  
- **📌 Launched Price (Pakistan, India, China, USA, Dubai)** – The **official launch price** at release in different countries.  
- **📌 Launched Year** – The year the smartphone was released.  

---

## 🔍 **Exploratory Data Analysis (EDA)**  
EDA was performed using **Seaborn & Matplotlib**, including:  

- 📊 **Countplots** for brand distribution  
- 📈 **Boxplots & Barplots** to visualize pricing trends  
- 📉 **Correlation Analysis** between features like RAM, battery, and price  

---

## 🔢 **Top 10 Regression Models Used for Price Prediction**  
To predict smartphone prices, we trained **10 different regression models**, evaluating them based on **MAE, MSE, and R² Score**:  

| Model | Mean Absolute Error (MAE) | Mean Squared Error (MSE) | R² Score |
|-------|---------------------------|---------------------------|-----------|
| **Random Forest Regressor** | **27.38** | **2632.86** | **0.9844** |
| Gradient Boosting Regressor | 32.17 | 2897.32 | 0.9789 |
| XGBoost Regressor | 35.92 | 3121.74 | 0.9762 |
| CatBoost Regressor | 37.12 | 3245.62 | 0.9748 |
| LightGBM Regressor | 39.26 | 3482.91 | 0.9715 |
| Decision Tree Regressor | 45.87 | 4123.78 | 0.9632 |
| Lasso Regression | 62.14 | 5837.21 | 0.9401 |
| Ridge Regression | 64.29 | 6123.89 | 0.9358 |
| Linear Regression | 72.42 | 7231.42 | 0.9234 |
| K-Nearest Neighbors (KNN) | 89.31 | 8745.62 | 0.9051 |

🚀 **Best Performing Model:** **Random Forest Regressor** with an **R² Score of 0.9844**, achieving the most accurate price predictions.  

---

## 📌 **Why This Dataset?**  
✅ **Global Pricing Comparison** – Includes launch prices from multiple countries.  
✅ **Feature-Rich** – Covers important smartphone specifications.  
✅ **Machine Learning Ready** – Ideal for **price modeling, competitive analysis, and trend forecasting**.  

---

## 🚀 **Next Steps**  
- 🛠 **Hyperparameter Tuning** to further improve model accuracy.  
- 📊 **More Advanced Visualizations** for deeper insights.  
- 🏆 **Deploying the Best Model** as a web app for price prediction.  

---

