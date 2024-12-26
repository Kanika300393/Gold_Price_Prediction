# Gold Price Prediction

![Gold-Price-Prediction-Using-Machine-Learning-In-Python-OG](https://github.com/user-attachments/assets/3c8bff7b-a2bf-4760-be2f-d81d4731baa5)



## Project Overview

This project focuses on predicting the price of gold using historical data and a Random Forest Regressor model. The steps include data preprocessing, visualization, correlation analysis, model training, and evaluation. The goal is to create an accurate predictive model to assist in forecasting gold prices based on various economic indicators.

## Workflow


| **Workflow Step**              | **Details**                                                                                                                                   |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| **1. Data Collection and Processing** | - **Dataset**: Loaded from a CSV file (`gold_price_data.csv`).<br>- **Exploration**: Inspected dataset's first and last rows, shape, and info.<br>- **Missing Values**: Checked and handled missing values.<br>- **Statistics**: Summary statistics calculated.<br>- **Correlation Analysis**: Identified positive/negative correlations and visualized with a heatmap. |
| **2. Feature Selection**       | - Dropped non-numeric columns (e.g., `Date`).<br>- Selected numerical features for the model.                                                 |
| **3. Data Visualization**      | - **Heatmap**: Showed correlations between variables.<br>- **Distribution Plot**: Analyzed the distribution of `GLD` (Gold Price).            |
| **4. Feature and Target Splitting** | - **Features (X)**: Independent variables excluding `Date` and `GLD`.<br>- **Target (Y)**: `GLD` price.                                     |
| **5. Train-Test Split**        | - Dataset split into training and test sets (80:20 ratio).                                                                                   |
| **6. Model Training**          | - **Model Used**: Random Forest Regressor.<br>- **Parameters**: 100 estimators.<br>- **Training**: Model trained on training data.            |
| **7. Model Evaluation**        | - **Predictions**: Made on the test dataset.<br>- **Metric**: R-squared error used for evaluation.                                            |
| **8. Actual vs Predicted Values** | - Created plots to visualize and compare actual vs. predicted values for better understanding.                                                |



## Results

R-squared Error: The model’s accuracy was evaluated using this metric.

## Visualizations

**Heatmap**: Showcases the correlation between features.

![Heatmap](https://github.com/user-attachments/assets/73009cd1-840d-407a-9ab0-a34da1b9b7d0)



**Distribution Plot**: Highlights the distribution of the GLD prices.

![Distribution Chart](https://github.com/user-attachments/assets/4d42878f-416b-4e68-9fe4-1b05805ee809)


**Actual vs Predicted Values Plot**: Compares actual and predicted prices for gold.

![Actual Vs Predicted](https://github.com/user-attachments/assets/8bec023f-58bc-44f8-9103-340ae1158210)



## Conclusion

This project demonstrates the use of machine learning techniques, specifically Random Forest Regressor, to predict gold prices. The model provides insights into economic indicators and their impact on gold price fluctuations.
