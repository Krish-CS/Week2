# Water Quality Prediction – Week 1

This project aims to predict multiple water quality parameters using machine learning techniques, specifically a `MultiOutputRegressor` wrapped around a `RandomForestRegressor`. It was developed as part of a one-month **AICTE Virtual Internship** sponsored by **Shell** in **June 2025**.

---

## 📌 Overview

Access to clean water is a critical environmental and public health concern. Predicting multiple pollutants simultaneously can help early identification of harmful water conditions and enable better policy and operational responses.

During **Week 1**, the primary focus was on:
- Loading and cleaning the dataset
- Extracting relevant time-based features
- Building a base machine learning model
- Predicting future pollutant levels

---

## 🛠️ Technologies Used

- **Python 3.12**
- `Pandas`, `NumPy` – Data handling and preprocessing
- `Scikit-learn` – ML modeling and evaluation
- `Joblib` – Model persistence
- **Jupyter Notebook** – Development environment

---

## 🎯 Water Quality Parameters Predicted

The model predicts the following key pollutant indicators:
- O₂ (Oxygen)
- NO₃ (Nitrate)
- NO₂ (Nitrite)
- SO₄ (Sulphate)
- PO₄ (Phosphate)
- CL (Chloride)

---

## 📊 Model Evaluation Metrics

- **R² Score**
- **Mean Squared Error (MSE)**

Model performance is measured using standard regression metrics across all pollutants.

---

## 📁 Files Included

- `Water_Quality_Prediction.ipynb` – Main notebook
- `pollution_model.pkl` – Trained model
- `model_columns.pkl` – Column structure used for prediction
- `data/water_quality.csv` – Dataset used
- `README.md` – Project overview

---

## 🧪 Sample Prediction Output

The model takes a `station_id` and `year` as input and returns predicted pollutant values.

---

## 🧾 Internship Details

- **Internship Type:** AICTE Virtual Internship – Edunet Foundation
- **Sponsor:** Shell
- **Month:** June 2025
- **Focus Area:** Machine Learning for Environmental Monitoring



# Water Quality Prediction – Week 2 (Enhanced Version)

This enhanced version builds upon the Week 1 base model to include in-depth analysis, visualizations, and improved evaluation methods. This project is part of the AICTE Virtual Internship (June 2025) supported by Shell.

---

## 📌 Objective

Enhance the water quality prediction model with:
- Correlation analysis
- Graphical evaluation (Actual vs. Predicted)
- Better data insights for environmental forecasting

---

## 🔍 Key Improvements

- Added correlation heatmap using `seaborn`
- Scatter plots for actual vs. predicted pollutant levels
- Refactored code for modularity and clarity
- Model evaluation for each pollutant retained

---

## 🧪 Technologies & Libraries

- Python 3.12
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`, `Joblib`
- Jupyter Notebook

---

## 📈 Visualizations Included

- Correlation heatmap of pollutants
- Scatter plots: Actual vs Predicted for each pollutant

---

## 📁 Files Included

- `Water_Quality_Prediction.ipynb` – Enhanced model with plots
- `pollution_model.pkl` – Updated trained model
- `model_columns.pkl` – Encoded input structure
- `data/water_quality.csv` – Dataset
- `README.md`

---

## 📊 Model Evaluation Metrics

- **R² Score**
- **Mean Squared Error (MSE)**

---

## 📅 Internship Details

- **Type:** AICTE Virtual Internship
- **Platform:** Edunet Foundation
- **Sponsored by:** Shell
- **Week:** Week - 2
- **Month:** June 2025
