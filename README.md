# Energy-Consumption-Forecasting
# ⚡ Household Energy Consumption Forecasting

## Overview

This project focuses on predicting household energy consumption using Machine Learning. The goal is to analyze historical electricity usage data and build a model that can estimate power consumption based on electrical measurements and time-related information.

I developed this project to strengthen my understanding of data preprocessing, exploratory data analysis (EDA), feature engineering, machine learning algorithms, and model evaluation.

---

## Project Objectives

* Understand household electricity consumption patterns.
* Clean and preprocess a large real-world dataset.
* Explore relationships between different electrical parameters.
* Train a machine learning model to predict power consumption.
* Evaluate the model using standard regression metrics.
* Save the trained model for future use.

---

## Dataset

The project uses the **Household Power Consumption Dataset**, which contains more than one million records of electricity usage measurements collected over time.

### Features Used

* Global Active Power
* Global Reactive Power
* Voltage
* Global Intensity
* Sub Metering 1
* Sub Metering 2
* Sub Metering 3
* Date and Time Information

Additional time-based features such as Hour, Day, and Month were extracted during preprocessing.

---

## Tools and Libraries

The project was built using:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Joblib

---

## Project Workflow

### 1. Data Preprocessing

* Loaded the dataset
* Handled missing values
* Converted data types
* Created date-time features
* Removed unnecessary records

### 2. Exploratory Data Analysis

Several visualizations were created to better understand the dataset:

* Power Consumption Distribution
* Voltage vs Power Consumption
* Correlation Heatmap
* Actual vs Predicted Comparison
* Feature Importance Analysis

### 3. Model Development

A **Random Forest Regressor** was used to train the model because it performs well on large datasets and can capture complex relationships between features.

### 4. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Results

The trained model achieved the following performance:

| Metric   | Score  |
| -------- | ------ |
| MAE      | 0.0184 |
| RMSE     | 0.0362 |
| R² Score | 0.999  |

These results indicate that the model was able to predict energy consumption with very high accuracy on the test data.

---

## Key Insights

* Global Intensity had the strongest influence on energy consumption.
* Voltage and Reactive Power also contributed to predictions.
* Time-based features helped the model capture usage patterns.
* Energy consumption varies significantly throughout different periods of the day.

---

## Files Included

```text
Household-Energy-Consumption-Forecasting/
│
├── Energy Consumption Forecasting.py
├── household_power_consumption.csv
├── energy_model.pkl
├── scaler.pkl
├── README.md
└── screenshots/
```

---

## How to Run

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### Execute the Project

```bash
python "Energy Consumption Forecasting.py"
```

---

## Future Improvements

Some enhancements that can be added in the future:

* Time Series Forecasting
* XGBoost Regression
* LSTM Neural Networks
* Streamlit Dashboard
* Real-Time Energy Monitoring
* Model Deployment

---

## What I Learned

Through this project, I gained practical experience in:

* Data Cleaning
* Data Visualization
* Feature Engineering
* Machine Learning
* Model Evaluation
* Working with Large Datasets
* Saving and Reusing Trained Models

---

## Author

**Gorle Jani Venkata Pavan Sai Jeevan**

Engineering Student passionate about Python, Machine Learning, Data Analytics, and building real-world projects.

If you find this project useful, feel free to explore the code and provide feedback.
