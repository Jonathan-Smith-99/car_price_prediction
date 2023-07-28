# Car Price Prediction

## Description
Car Price Prediction is a project that aims to determine the market value of used cars based on historical data, including technical specifications, trim versions, and prices. The project uses machine learning models to predict car prices and provides insights into the quality and speed of the predictions.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- LightGBM
- XGBoost
- CatBoost

## Model Evaluation
The models are evaluated using the Root Mean Squared Error (RMSE) metric. The performance of each model on the validation and test sets is as follows:


| Model             | CV Tuning Time | Tuned Model Training Time | Validation RMSE | Test RMSE   | Prediction Time |
|-------------------|---------------|---------------------------|-----------------|-------------|-----------------|
| Linear Regression | 0.000000      | 17.343750                 | 2553.225802     | 2542.670145 | 0.067149        |
| Random Forest     | 1438.754136   | 36.095162                 | 1614.783606     | 1630.854449 | 0.135137        |
| Decision Tree     | 76.178583     | 6.897701                  | 1657.127616     | 1685.447806 | 0.074401        |
| LightGBM          | 42.063741     | 0.785883                  | 1504.871885     | 1510.258370 | 0.130114        |
| XGBoost           | 224.758258    | 4.917339                  | 1498.501033     | 1499.988799 | 0.151498        |
| CatBoost          | 838.009918    | 32.334932                 | 1511.483392     | 1527.589387 | 0.104630        |


