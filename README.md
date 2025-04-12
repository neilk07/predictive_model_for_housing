# Predicting Apartment Prices in Buenos Aires

A simple and effective linear regression model to estimate real estate prices of apartments in Buenos Aires, Argentina, using real-world housing data.

---

## 📌 Overview

This project focuses on cleaning and modeling real estate data to predict housing prices for apartments located in the "Capital Federal" region of Buenos Aires. The final model uses **linear regression** and is evaluated using **Mean Absolute Error (MAE)**.

---

## 🧰 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## 🧹 Data Wrangling

The dataset is filtered using the following criteria:

- 📍 Only includes listings in **Capital Federal**
- 🏢 Focuses on **apartments** only
- 💰 Filters out properties priced above **400,000 USD**

---

## 🔍 Features Used

- `surface_covered_in_m2`
- `rooms`
- `bathrooms`
- `lat` and `lon`
- `price_aprox_usd` (Target)

---

## ⚙️ Model Pipeline

1. Load and clean data
2. Select relevant features
3. Handle missing values with `SimpleImputer`
4. Split data (80% train, 20% test)
5. Train `LinearRegression` model
6. Evaluate performance with `MAE`

---

## 📈 Results

- **Model Type:** Linear Regression  
- **Metric:** Mean Absolute Error (MAE)  
- Performance summary printed in the notebook

---
