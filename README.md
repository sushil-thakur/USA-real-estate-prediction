# 🏠 USA Real Estate Price Prediction

This repository contains a machine learning project focused on **predicting real estate prices across the USA** using property data and an **XGBoost regression model**.

> This project demonstrates how ML can support buyers, sellers, and real estate professionals by providing accurate property value predictions based on structured features.

---

## 📌 Project Overview

The primary objective is to build a predictive model that estimates the price of a property using various attributes like location (city, state, zip code), street, and potentially other features (e.g., number of bedrooms, size, etc.).

---

## 🧠 Machine Learning Model

- **Algorithm**: [XGBoost Regressor](https://xgboost.readthedocs.io/en/stable/)
- **Preprocessing**: Label encoding for categorical variables (city, state, zip code, street)
- **Environment**: Jupyter Notebook with Python

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| `fixed_code.ipynb` | Jupyter Notebook with complete data pipeline: preprocessing, model training, evaluation |
| `real_estate_price_xgb_model.pkl` | Saved XGBoost model for predicting property prices |
| `real_estate_price_xgb_model (1).pkl` | Possibly a second version or backup of the model |
| `city_label_encoder.pkl` | Label encoder for transforming city names |
| `state_label_encoder.pkl` | Label encoder for state names |
| `street_label_encoder.pkl` | Label encoder for street names |
| `zip_code_label_encoder.pkl` | Label encoder for zip codes |

---

## ⚙️ Tech Stack

- **Python**
- **XGBoost**
- **Scikit-learn**
- **pandas, numpy**
- **Jupyter Notebook**

---

## 🔁 Workflow

1. **Data Preprocessing**
   - Categorical variables are encoded using `LabelEncoder`
   - Features and labels are separated for training

2. **Model Training**
   - XGBoost regressor is trained using the processed data
   - Model performance is evaluated on a test set

3. **Model Export**
   - Trained model and encoders are saved as `.pkl` files for future inference

4. **Prediction**
   - The saved model and encoders can be loaded to predict prices for new property data

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/sushil-thakur/usa-real-estate-price-prediction.git
cd usa-real-estate-price-prediction
