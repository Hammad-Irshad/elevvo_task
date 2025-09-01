
# 🗓️ Task 7: Sales Forecasting - Elevvo Internship

This project predicts weekly Walmart sales using historical data from stores, departments, and economic indicators. We apply time-based feature engineering and train an XGBoost regression model to forecast future sales.

---

## 📁 Project Structure

```
task 7/
├── code.ipynb               # Main notebook
├── train.csv                # Training data
├── test.csv                 # Test data
├── features.csv             # Additional features like fuel, CPI
├── stores.csv               # Store metadata (Type, Size)
├── walmart_model.h5         # Saved trained model (joblib format)
└── README.md                # This file
```

---

## 📊 Dataset

Source: [Gustavo Serafim's Kaggle Dataset](https://www.kaggle.com/datasets/gustavoserafim/walmart-recruiting-store-sales-forecasting-gsr)

- 45 Walmart stores across various U.S. regions
- Weekly sales per department
- Macroeconomic data: CPI, Unemployment, Fuel Prices

---

## ⚙️ Tools Used

- Python, Pandas, NumPy
- XGBoost Regressor
- Joblib (model persistence)
- Matplotlib & Seaborn for plots
- Scikit-learn for metrics

---

## 🚀 Steps Performed

1. **Data Merging** – train + features + stores
2. **Feature Engineering** – extracted Year, Month, Week, Lag1, Lag7
3. **Encoding** – Categorical encoding for Type and IsHoliday
4. **Train-Test Split** – Time-based (pre-Oct 2012 vs post)
5. **Modeling** – XGBoost with early stopping
6. **Evaluation** – RMSE & visualization

---

## 🧠 Model Saving & Reloading

- Trained models are saved to: `walmart_model.h5`
- The notebook checks if this file exists:
  - ✅ If found, loads the model
  - ❌ If not, trains a new model and saves it

---

## 📈 Output

- RMSE printed after validation
- Plot comparing actual vs predicted weekly sales

---

## 📝 Author

**Syed Muhammad Hammad Irshad**  
Elevvo Internship Submission (Task 7 - August 2025)

---
