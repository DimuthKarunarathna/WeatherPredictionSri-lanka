# 🌧️ Weather Prediction Using Logistic Regression

This project builds a machine learning model to predict whether it will rain tomorrow in Sri Lanka based on historical weather data. The model uses logistic regression and various preprocessing steps to build an effective binary classifier.

## 📁 Dataset
- Source: Custom CSV (`SriLanka_Weather_Dataset.csv`)
- Features:
  - Weather codes
  - Temperature (max, min, mean)
  - Apparent temperature
  - Precipitation and wind speed

## Model
- **Type**: Binary Classification
- **Algorithm**: Logistic Regression & Logistic Regression with Cross-Validation
- **Target**: `RainTomorrow` (1 = Rain, 0 = No Rain)

## Preprocessing
- Handling missing values
- Feature scaling using `StandardScaler`
- Train-Test Split

## Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

## Results
Achieved decent accuracy using both standard and cross-validated logistic regression techniques. This can serve as a baseline model for weather prediction.

## Future Work
- Try more complex models (Random Forest, XGBoost)
- Time-series based modeling (LSTM, ARIMA)
- Use real-time API data for live predictions

## Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
