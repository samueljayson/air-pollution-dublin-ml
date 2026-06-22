# Dublin Air Pollution Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Folium](https://img.shields.io/badge/Folium-Geospatial-red)
![GeoPandas](https://img.shields.io/badge/GeoPandas-Spatial%20Analysis-yellow)

## Project Overview

This project predicts street-level air pollution in Dublin City using Google Project Air View data. Machine learning models were developed to identify pollution patterns and important predictors.

---

## Dataset

- **Source:** Google Air View Data – Dublin City
- **Period:** May 2021 – August 2022
- **Target Variable:** PM2.5 concentration

---

## Objectives

- Clean and prepare the air pollution dataset
- Extract spatial features from road geometry
- Build Random Forest and Gradient Boosting models
- Evaluate model performance using RMSE, MAE and R²
- Identify important predictors
- Visualize pollution hotspots across Dublin

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- GeoPandas
- Shapely
- Folium
- Matplotlib

---

## Machine Learning Models

### Random Forest Regressor

- n_estimators = 300
- random_state = 42
- n_jobs = -1

### Gradient Boosting Regressor

- random_state = 42

---

## Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Spatial Feature Extraction
5. Train-Test Split
6. Random Forest Model Development
7. Gradient Boosting Model Development
8. Model Evaluation
9. Feature Importance Analysis
10. Hotspot Visualization

---

## Key Results

- Successfully predicted street-level air pollution patterns.
- Compared Random Forest and Gradient Boosting models.
- Evaluated models using RMSE, MAE and R².
- Identified important predictors influencing PM2.5 levels.
- Visualized pollution hotspots across Dublin.

---

## Repository Structure

```text
air-pollution-dublin-ml/
│
├── Data/
│
├── Images/
│
├── Notebooks/
│
├── README.md
```

---

## Future Improvements

- Hyperparameter tuning
- SHAP explainability
- XGBoost implementation
- Streamlit dashboard deployment
- Real-time air quality prediction

---

## Author

### Samuel Jayson B F

MSc Data Analytics  
Dublin Business School, Ireland

GitHub:
https://github.com/samueljayson

LinkedIn:
https://www.linkedin.com/in/samuel-jayson-bf

---

## License

This project is intended for educational and research purposes.
