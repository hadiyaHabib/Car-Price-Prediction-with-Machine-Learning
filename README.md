# Car-Price-Prediction-with-Machine-Learning

Description
Three regression models — Linear Regression, Random Forest, and Gradient Boosting — are trained to predict the selling price of used cars.
Dataset
Loaded automatically from GitHub:
https://raw.githubusercontent.com/RimjimRazdan/cars_price_prediction/master/car%20data.csv
Features

Price distribution analysis (normal + log-transformed)
Correlation heatmap
Categorical analysis: Fuel Type & Seller Type
Feature engineering: Car_Age = 2024 - Year
Label encoding for categorical columns
5-fold cross-validation

Models Used
ModelParametersLinear RegressionDefaultRandom Forestn_estimators=200Gradient Boostingn_estimators=200
Evaluation Metrics

MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score
Cross-Validation R²

Output Files

car_price_distribution.png
car_correlation.png
car_categorical_analysis.png
car_model_comparison.png
car_actual_vs_predicted.png
car_feature_importance.png

Quick Start
bashpip install numpy pandas matplotlib seaborn scikit-learn
python task3_car_price.py

\
├── task3_car_price.py
├── Unemployment_Rate_upto_11_2020.csv   # optional — Task 2
└── README.md
