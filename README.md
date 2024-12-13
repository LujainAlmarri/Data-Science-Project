# Data-Science-Project
Predicting Mobile Phone Prices Using Machine Learning
Overview
This project aims to analyze the relationship between mobile phone specifications, performance metrics, and pricing in the competitive smartphone market. By leveraging machine learning techniques, we identified key drivers of mobile phone prices and developed predictive models to support strategic decisions in product development and marketing.
Introduction
In a highly dynamic smartphone market, understanding the factors influencing pricing is crucial for both manufacturers and consumers. This project investigates the following research question:

What are the most important factors influencing mobile phone prices, and how do these factors interact to predict price using machine learning?

Dataset
Source: The dataset, named "Mobile Dataset," contains detailed specifications for a variety of mobile phone models.
Target Variable: price_usd (price in USD).
Predictors: Includes features like processor speed (GHz), RAM (GB), storage (GB), and engineered metrics such as performance score and price per RAM.
Size: 785 observations with 15 raw features and several engineered features.
Data Cleaning and Preprocessing
Missing values were imputed using median values.
Outliers were identified but retained for analysis.
Non-numeric features were converted to numeric formats where applicable.
Engineered features such as price per RAM and performance score were added for improved model performance.
Methodology
Tools and Libraries
Data Manipulation: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: scikit-learn
Analysis Approach
Exploratory Data Analysis (EDA):

Visualized data distributions and relationships.
Generated correlation heatmaps to identify key predictors.
Feature Engineering:

Created features like price per RAM and RAM-storage interaction.
Enhanced dataset interpretability and model accuracy.
Model Selection and Training:

Models evaluated: Random Forest, Gradient Boosting, K-Nearest Neighbors (KNN).
Random Forest Regressor chosen for its robustness in handling non-linear relationships.
Evaluation Metrics:

R² score
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
