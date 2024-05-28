# Restaurant Monthly Revenue Prediction

## Project Overview

This project aims to predict the monthly revenue for a restaurant using machine learning models. Accurate revenue predictions enable restaurant management to make data-driven decisions regarding inventory, staffing, and marketing, thereby improving operational efficiency and profitability. project article, https://medium.com/@mokhutliletsae/restaurant-revenue-prediction-using-deep-learning-b582cd3704f7

## Table of Contents

- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
- [Data Preparation](#data-preparation)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Contact](#contact)

## Business Understanding

### Problem Statement
The primary objective is to predict the monthly revenue of a restaurant. Accurate forecasting helps in efficient decision-making related to operations and marketing.

## Data Understanding

### Exploratory Data Analysis
EDA involved:
- Descriptive statistics
- Visualization of data distributions
- Identification of missing values and outliers

## Data Preparation

### Steps Taken
1. **Handling Missing Values**: Imputation techniques for missing data.
2. **Correcting Data Types**: Ensuring correct data types for all variables.
3. **Addressing Outliers**: Using z-score analysis and IQR.
4. **Feature Engineering and Selection**: Creating new features and selecting important ones using variance and correlation thresholds.
5. **Normalization**: Scaling numerical features.

## Model Building

### Models Developed
1. **Deep Learning Model (Multi-Layer Perceptron)**
2. **XGBoost Regressor**

### Model Selection
The MLP neural network model outperformed the XGBoost regressor and was selected for final predictions.

## Evaluation

### Performance Metrics
- **R-squared (R²)**: 0.67
- **Mean Absolute Error (MAE)**: 44
- **Error Percentage**: 35%

The MLP model showed good performance with minimal overfitting.

## Conclusion
The MLP neural network model provides reliable revenue predictions, enabling effective decision-making for restaurant management.

## Future Work
- Additional feature engineering (e.g., incorporating external factors)
- Exploring advanced time-series forecasting techniques
- Using ensemble methods for improved performance

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/restaurant-revenue-prediction.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the capstone_prep_fle.ipnyb using jupyter notebooks:

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- TensorFlow/Keras
- XGBoost
- Matplotlib/Seaborn (for visualizations)

## Contact
For any queries or issues, please contact me on https://www.linkedin.com/in/mokhutliletsae/.
