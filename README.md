Urban Airscape: Determinants of Air Quality in City Environments
Context
This project focuses on analyzing and predicting air quality levels based on meteorological data and pollutant concentration across various regions. It integrates exploratory data analysis (EDA) and machine learning regression models to understand the relationships between environmental factors and air quality.

Objectives
Perform in-depth EDA to uncover patterns and correlations between pollutants and meteorological variables.
Implement dimensionality reduction using PCA to create interpretable features.
Build and evaluate machine learning models for predicting air quality, using metrics such as RMSE and R².
Provide insights into feature importance using SHAP values for interpretability.
Data
The dataset used contains information about air pollutant concentrations and meteorological data. Key variables include:

Pollutant concentrations (e.g., PM2.5, NOx).
Meteorological factors (e.g., temperature, humidity).
Spatial and temporal data across various regions.
Exploratory Data Analysis (EDA)
Key insights from the EDA include:

Correlations between temperature, humidity, and nitrogen oxide concentrations.
Seasonal trends in pollutant levels, with higher concentrations during colder months.
Dimensionality reduction using PCA resulted in 4 main components:
Overall Pollutant Concentration (PC1)
Temperature and Humidity vs. Nitrogen Oxides (PC2)
Relative Humidity (PC3)
Nitrogen Oxides and Temperature (PC4)
Machine Learning Models
We tested three regression models: Random Forest, Support Vector Regression (SVR), and XGBoost. Cross-validation was used to evaluate performance based on RMSE and R² scores.

Best Model
Random Forest was the best performing model:
RMSE: X.XX
R²: X.XX
Feature importance revealed PC1 (Overall Pollutant Concentration) as the most significant feature.
SHAP Analysis
SHAP (SHapley Additive exPlanations) was used to interpret the model, revealing:

The impact of each feature on the model's predictions.
PC1 and PC2 as critical features in predicting air quality levels.
Repository Structure
Data: Dataset files and data preprocessing scripts.
EDA: Notebooks with data visualization and analysis.
Models: Machine learning model scripts, training, and evaluation.
Results: Cross-validation scores, feature importance, and SHAP plots.
Conclusion
This project provided key insights into air quality prediction and feature contributions. The Random Forest model, along with SHAP analysis, gave strong predictive performance and interpretability.
