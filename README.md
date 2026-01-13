# Bike Sharing Demand Forecasting

This project forecasts **hourly bike rental demand (`cnt`)** using historical data from the UCI Bike Sharing Dataset.  

---

## What’s Included

- Exploratory data analysis (EDA)
- One forecasting model (Random Forest Regressor)
- Model evaluation using Mean Absolute Deviation (MAD)
- Business-focused insights and recommendations

---

## Dataset

- `hour.csv` — hourly bike rental data (used for modeling)
- `day.csv` — daily aggregated data (not used in the model)

Target variable: `cnt` (total rentals per hour)

Dataset source: UCI Bike Sharing Dataset

---

## How to Run (Google Colab)

1. Open the notebook in Google Colab
3. Run all cells from top to bottom

---

## Model Summary

- **Model:** Random Forest Regressor  
- **Metric:** Mean Absolute Deviation ≈ 47 bikes/hour  
- **Why this model:** Good accuracy, stable behavior, and easy to maintain in production

---


---

## Author

[Your Name]
