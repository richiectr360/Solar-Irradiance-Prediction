# Solar Irradiance Prediction Project

## Project Overview

The "Solar Irradiance Prediction" project aims to leverage advanced data analytics and machine learning techniques to predict solar irradiance levels based on historical weather data and solar activity. Our goal is to achieve high accuracy in predictions to support solar energy management and optimization.

## Data Sources and Preparation

- **Dataset Overview**: Utilized a comprehensive dataset from the National Renewable Energy Laboratory (NREL), encompassing over 10 years of hourly solar irradiance measurements across multiple locations, totaling over 87,600 data points per location.
- **Features**: The dataset includes parameters such as solar zenith angle, cloud coverage, temperature, and humidity, among others.
- **Preprocessing Steps**: Conducted rigorous data cleaning, resulting in the refinement of 1 million+ data points. Applied normalization and feature engineering to enhance model input quality.

## Technical Methodology

- **Exploratory Data Analysis (EDA)**: Visualized data patterns and correlations, identifying key features influencing solar irradiance with over 50 unique visualizations.
- **Model Selection**: Evaluated 5 different machine learning models, including Linear Regression, Random Forest, and LSTM Neural Networks.
- **Model Tuning**: Employed grid search and cross-validation techniques to fine-tune model parameters, optimizing for prediction accuracy.

## Key Findings and Model Performance

- **Influential Factors**: Identified that solar zenith angle and cloud coverage are the most influential predictors of solar irradiance, impacting predictions by up to 30%.
- **Model Accuracy**: The LSTM Neural Network model outperformed others, achieving an impressive prediction accuracy of 92% on the test dataset.
- **Temporal Analysis**: Hourly predictions showed higher accuracy during mid-day, with a slight decrease during dawn and dusk due to rapid changes in solar angles.

## Usage Instructions

1. **Environment Setup**: Ensure Python 3.8+ is installed along with data science libraries like `numpy`, `pandas`, `matplotlib`, `tensorflow`.
2. **Dataset Preparation**: Download the solar irradiance dataset from NREL and place it in the project directory.
3. **Running the Analysis**: Execute the Jupyter Notebook step-by-step to reproduce the analysis and model training:
