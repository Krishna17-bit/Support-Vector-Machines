## Overview
This project involves the analysis of forest fire data to understand the relationship between various environmental factors and the occurrence of forest fires. The analysis uses statistical methods and machine learning to predict forest fire risks based on weather conditions and other factors.

## Datasets
The dataset used in this analysis contains historical data on forest fires and includes variables such as month, day, FFMC (Fine Fuel Moisture Code), DMC (Duff Moisture Code), DC (Drought Code), ISI (Initial Spread Index), temperature, relative humidity, wind speed, rain, and burned area.

## Features of the Dataset
- **Month and Day**: Encoded as integers for easier processing.
- **Weather Conditions**: Includes FFMC, DMC, DC, ISI, temperature, humidity, and wind.
- **Rain**: Amount of precipitation.
- **Burned Area**: The size of the forest fire.

## Preprocessing Steps
- Encoding categorical data such as month and day into numerical format.
- Dropping irrelevant columns to focus the analysis on significant predictors.
- Creating dummy variables for categorical features.

## Analysis Performed
- **Data Visualization**: Bar charts to analyze the relationship between the month/day and various environmental factors.
- **Correlation Analysis**: Heatmap to identify the strength of association between different variables.
- **Support Vector Machine (SVM)**: Used to classify the data into different months based on selected features.

## Libraries Used
- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `matplotlib.pyplot` and `seaborn` for data visualization.
- `sklearn` for machine learning model implementation.
