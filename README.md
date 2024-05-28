# Great-Energy-Predictor

## Project Overview
This project aims to predict and estimate the energy consumption of buildings, focusing on four types of energy: chilled water, electricity, hot water, and steam. Using data from the ASHRAE - Great Energy Predictor III competition, we applied advanced machine learning algorithms to develop accurate and generalizable energy consumption models.

## Motivation
In 2023, research from NREL showed that buildings contributed to 40% of total energy use in the US, including 75% of electricity use and 35% of the nation's carbon emissions. Our goal is to improve energy consumption predictions for buildings to identify key components contributing to energy use and support energy-saving strategies to reduce CO2 emissions and overall energy demand.

## Datasets
We used three datasets in this project:

Building Metadata: Information about the buildings.
Meter Readings: Energy consumption data.
Weather Conditions: Associated weather data impacting energy consumption.
Methodology
We implemented several machine learning algorithms, including:

Principal Component Analysis (PCA)
Decision Trees
XGBoost
LightGBM
Random Forest
Multi-layer Perceptron (MLP)
These models were selected for their robustness and ability to handle complex and varied data types. We evaluated model performance using Root Mean Squared Error (RMSE) and Mean Absolute Percentage Error (MAPE).

## Results
XGBoost performed the best within different clusters of the data. The model not only identified the most effective algorithms but also highlighted which factors influence energy consumption through feature importance analysis. This understanding can help develop more effective policies for sustainable urban energy management.
