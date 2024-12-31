Employment-Rate-Prediction-by-Neural-Network
Employment Rate Prediction Based on Economic Indicators: An Interactive Analysis with Neural Network and Traditional Machine Learning Modelling

This repository showcases a final year MSc Data Science project focused on predicting employment rates for 150+ countries using economic indicators. The project evaluates traditional and advanced machine learning models, integrates ARIMA for feature forecasting, and presents insights through an interactive dashboard.

## Project Overview
The project aims to predict employment rates for 2023–2025 using historical economic data (2000–2022). Key objectives include performing exploratory data analysis (EDA), feature forecasting with ARIMA, training machine learning models (e.g., Random Forest, LSTM, XGBoost), and creating a dashboard for dynamic visualization.

## Project Objectives
Conduct EDA to uncover data patterns and trends.
Forecast key economic indicators for 2023–2025 using ARIMA.
Train and evaluate models including Linear Regression, LSTM, XGBoost, and Random Forest.
Compare models using metrics like MAE, MSE, R², and Accuracy (%).
Build an interactive dashboard to visualize employment rate predictions and trends.
## Project Structure
data/: Contains cleaned and processed datasets.

models/: Scripts for training and evaluating machine learning models.

forecasting/: ARIMA forecasting scripts for economic indicators.

dashboard/: Dash-based files for interactive visualization.

colab_notebooks/: Google Colab notebooks for EDA, modeling, and forecasting.

results/: Outputs including model metrics and visualization assets.
## Key Results
Best Model: Random Forest achieved the highest accuracy of 94.9%, outperforming all other models.
Key Insight: Labor Force Participation Rate emerged as the strongest predictor of employment rates.
Dashboard Highlights:
Country-specific employment rate trends (2023–2025).
Global employment variations via interactive maps.


 
Dependencies
Programming Language: Python 3.8+
Libraries:
Pandas, NumPy: Data manipulation.
Matplotlib, Plotly: Visualization.
Scikit-learn, XGBoost, TensorFlow/Keras: Modeling.
Statsmodels: ARIMA modeling.
Dash: Interactive dashboard development.
Acknowledgments
Special thanks to my supervisor (Ralf Napiwotzki) for insightful feedback and guidance.
Gratitude to my family for unwavering support and encouragement.
Thanks to open-source contributors for tools and resources used in this project.

## License
This project is licensed under a custom license. Permission must be obtained from the author before using the materials. For inquiries, contact **A Noman** at **nomansajalwu@gmail.com**.


