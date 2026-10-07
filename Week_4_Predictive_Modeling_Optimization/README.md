# Week 4 – Predictive Modeling and Optimization in Logistics Systems

## Project Overview

This project focuses on predictive modeling and optimization in logistics systems using Python and Machine Learning.

A simulated logistics dataset was created to predict **Delivery Days** using factors such as distance, shipment weight, number of items, shipping cost, processing time, and traffic level.

Two regression models were developed and compared:

- Linear Regression
- Random Forest Regression

The project also includes feature analysis, correlation analysis, and a simulated optimization scenario for reducing processing time.

## Objectives

- Predict logistics delivery time.
- Identify important factors affecting delivery duration.
- Compare machine learning regression models.
- Evaluate model performance using MAE, RMSE, and R² Score.
- Analyze relationships between logistics variables.
- Demonstrate a logistics optimization approach.
- Provide data-driven recommendations.

## Dataset

The simulated dataset contains **1,500 records and 7 variables**.

### Features

- `Distance_km`
- `Weight_kg`
- `Number_of_Items`
- `Shipping_Cost`
- `Processing_Hours`
- `Traffic_Level`
- `Delivery_Days` – Target variable

Traffic levels were encoded as:

- Low → 0
- Medium → 1
- High → 2

## Models Used

### Linear Regression
Used as a baseline model for predicting continuous delivery time.

### Random Forest Regression
Used to compare performance with a non-linear ensemble regression approach.

## Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 0.250 | 0.308 | 0.951 |
| Random Forest | 0.309 | 0.379 | 0.926 |

**Best Model: Linear Regression**

Linear Regression achieved the best performance with an R² Score of **0.951**.

## Analysis Performed

- Data simulation
- Data inspection
- Data preprocessing
- Feature and target selection
- Train-test split
- Linear Regression
- Random Forest Regression
- Model evaluation
- Model comparison
- Feature impact analysis
- Correlation analysis
- Optimization analysis

## Optimization

A simulated optimization scenario was performed by reducing **Processing Hours by 20%** and estimating its effect on delivery time using the trained model.

This demonstrates how predictive analytics can support logistics process improvement and decision-making.

## Key Findings

- Delivery time is influenced by multiple logistics factors.
- Linear Regression performed better than Random Forest on the simulated dataset.
- The selected model achieved an R² Score of **0.951**.
- Reducing processing delays can potentially improve delivery efficiency.
- Predictive analytics can support better logistics planning.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
Machine Learning
Data Analysis
Limitations

The dataset used in this project is simulated and does not represent real-world company logistics data. The optimization scenario is also hypothetical.

Future Scope
Use real-world logistics datasets.
Apply additional machine learning models.
Perform hyperparameter tuning and cross-validation.
Integrate real-time traffic data.
Implement route optimization.
Develop logistics dashboards.
Author

Palak Bhargav

B.Tech – Computer Science & Engineering (Artificial Intelligence)
Arya Institute of Engineering, Technology and Management
Internship Domain: Data Analytics / Logistics Analytics


