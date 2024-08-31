*Air Quality Index Prediction Model*
=====================================
*Overview*
This project involves predicting the Air Quality Index (AQI) using a Random Forest Regressor. The model utilizes various air quality parameters to estimate AQI values, aiming to provide accurate and actionable insights into air quality.

*Dataset*
The dataset used in this project is based on the AQIs of major cities of India.
Duration: January 1 2015 to July 1 2020.

Parameters included:
PM2.5: Particulate Matter less than 2.5 micrometers
PM10: Particulate Matter less than 10 micrometers
NO: Nitric Oxide
NO2: Nitrogen Dioxide
NOx: Nitrogen Oxides
NH3: Ammonia
CO: Carbon Monoxide
SO2: Sulfur Dioxide
O3: Ozone
Benzene: Benzene concentration
Toluene: Toluene concentration
Xylene: Xylene concentration
AQI: Air Quality Index (Target Variable)

*Model*
Algorithm: Random Forest Regressor
Parameters:
Number of Estimators: 100
Random State: 42

Data Splitting: Divided the dataset into training (80%) and testing (20%) sets.
Feature Scaling: Standardized features using StandardScaler.

*Model Evaluation*:
R-squared (R²): 94% - Indicates that 94% of the variance in AQI is explained by the model.

*Usage*
To use the model:

Load the Model: Load the trained model from a saved file.
Prepare Input Data: Ensure input data is in the same format and scaling as used during training.
Predict AQI: Use the model to predict AQI values for new input data.

*Future Work*
Model Improvement: Explore additional features or alternative models to further improve performance.
Cross-Validation: Perform cross-validation for a more robust performance evaluation.
Real-World Application: Adapt the model for real-time predictions and integrate it with air quality monitoring systems.
