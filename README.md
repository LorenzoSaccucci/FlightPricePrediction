# Flight Price Prediction Project

In a world marked by periods of inflation, economic crises, supply chain disruptions, and fluctuations in commodity prices, the dynamics of flight prices have become increasingly intricate. Airlines, in their pursuit of efficiency and profitability, have turned to sophisticated algorithms and data-driven strategies to optimize ticket pricing. These strategies often involve personalized and dynamically changing fares tailored to individual consumer behavior and market conditions.

This repository encompasses a comprehensive exploration into the realm of flight price prediction. Our central objective is to develop robust predictive models that shed light on the underlying patterns within the complex landscape of flight pricing. Particularly, this project focuses on flights to Europe's prime tourist destinations, both coastal paradises and cultural hubs, during the bustling summer season.

## Table of Contents
- [Context](#context)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering and Selection](#feature-engineering-and-selection)
- [Modeling](#modeling)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion](#conclusion)

## Context
In recent years, the airline industry has grappled with numerous economic challenges that have influenced the pricing of air travel. Factors such as inflation rates, supply chain disruptions, fluctuations in the cost of fuel and other commodities, and changing economic landscapes have made flight pricing an intricate puzzle. Airlines have responded by leveraging advanced algorithms to dynamically adjust fares, leading to personalized pricing structures that can often seem elusive and unpredictable to travelers.

## Data Collection
The foundation of this project rests upon meticulously collected data acquired through Octoparse, a powerful web scraping tool. This data captures the multifaceted aspects of flight information, forming the cornerstone for our predictive models.

## Data Preprocessing
Our commitment to data quality led us through a rigorous preprocessing phase. This phase involved addressing missing values, identifying and handling outliers, and ensuring consistency within the dataset. The resultant clean and structured data laid the groundwork for meaningful analysis.

## Feature Engineering and Selection
In our pursuit of predictive accuracy, we engineered novel features from the dataset, seeking to unveil latent relationships that contribute to flight price dynamics. Additionally, we employed feature selection techniques to identify the most influential variables for model training.

## Modeling
The journey towards accurate flight price predictions involved a comprehensive exploration of diverse machine learning algorithms, including:
- Linear Regression
- Lasso and Ridge Regression
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- Random Forest Regression

## Hyperparameter Tuning
Recognizing the pivotal role of hyperparameters in model performance, we harnessed techniques such as Random Search and Grid Search to fine-tune each algorithm's parameters.

## Evaluation Metrics
Our models underwent rigorous evaluation utilizing key metrics, including:
- R-squared (R²)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

## Conclusion
Through meticulous data collection, preprocessing, feature engineering, and advanced modeling, we strive to uncover the intricate fabric of flight prices in the context of today's complex economic and airline industry landscapes. This repository encapsulates our journey and findings, offering insights into the potential patterns and structures underlying flight pricing dynamics.

Feel free to delve into the code and adapt it to your own projects. Should you have any inquiries or suggestions, we encourage you to reach out.

**Disclaimer:** This project is designed for educational and illustrative purposes only. The flight price predictions presented here are not guaranteed to accurately reflect real-world pricing scenarios.

*Author: Lorenzo Saccucci and Henny Rossatto*

 
