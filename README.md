# AQI_PREDICTION_MODEL
# 🌫 Air Quality Index (AQI) Prediction Model – Sohna 2023

##  Problem Statement

Air pollution is a growing concern, especially in rapidly developing towns like Sohna. The goal of this project is to build an AI-based model that can *predict the next hour’s AQI (Air Quality Index)* using historical data. Accurate predictions can help alert authorities and citizens in advance.

---

## Project Summary

- The dataset used is hourly AQI data for Sohna from 2023.
- Features include previous AQI values, rolling averages, and time components like hour and day.
- The task is *supervised learning* (regression).
- Data was cleaned, processed, and split into training and testing datasets.
- A powerful *XGBoost Regression* model was used for predictions.

---

## Solution

We created a machine learning pipeline in Google Colab:
- Loaded and cleaned the dataset.
- Created lag and rolling features to help the model understand time trends.
- Trained a regression model using *XGBoost*.
- Evaluated the model using RMSE, MAE, and R².
- Visualized prediction vs. actual AQI values to show model performance.

---

## Key Features of the Model

- ✔ Uses time-series features like past AQI and rolling means
- ✔ Trained on real-world hourly AQI data
- ✔ High accuracy (R² ≈ 0.94)
- ✔ Ready for deployment or API integration
- ✔ Simple structure for easy modification

---

##  Benefits of This Model

- Helps in early warnings for high pollution hours
- Can guide citizens about safe hours for outdoor activities
- Useful for urban planning, traffic control, and health awareness
- Can be scaled to other cities with similar structure

---

##  Technologies Used

- *Python 3*
- *Pandas, NumPy* – data manipulation
- *XGBoost* – machine learning algorithm
- *Matplotlib, Seaborn* – visualizations
- *Scikit-learn* – model evaluation
- *Google Colab* – cloud-based training
- *GitHub* – version control and sharing

---

##  Evaluation Metrics

- 📉 *RMSE*: 19.78  
- 📉 *MAE*: 14.05  
- 📈 *R² Score*: 0.938
