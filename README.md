# Cryptocurrency and Stock Market Prediction Notebook

## Overview
This Jupyter notebook provides an end-to-end solution for analyzing and predicting cryptocurrency prices (specifically Bitcoin and Ethereum) alongside major stock indices (DJIA and NASDAQ). It encompasses data collection, preprocessing, predictive modeling, and decision-making phases to inform investment strategies using historical and real-time financial data.

## Features

- **Data Collection and Preprocessing:** Fetches historical and real-time financial data using APIs and preprocesses it for analysis. This includes cleaning the data and engineering features for predictive modeling.

- **Predictive Modeling:** Utilizes the XGBoost framework to predict future Bitcoin closing prices based on historical data. Model performance is evaluated using standard metrics like R², MAE, RMSE, and EV.

- **Investment Decision Making:** Based on the predictive model's outputs, the notebook provides actionable insights, suggesting when to buy or sell Bitcoin to maximize investment returns.

- **Visualization:** Includes visualizations to aid in understanding data trends, model predictions, and investment strategy outcomes.

## Requirements
To run this notebook, you will need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- requests

## Installation
Ensure that you have Python and Jupyter installed before running the notebook.

## Usage
Open the Crypto Project.ipynb notebook in Jupyter and execute the cells sequentially. Make sure to set up the necessary API keys for fetching financial data through the specified APIs.

## Structure
The notebook is structured into sections that sequentially take you through the process of data analysis and predictive modeling:

Data Collection: Fetching real-time and historical data.
Data Preprocessing: Cleaning and preparing data for analysis.
Feature Engineering: Enhancing the dataset with new features.
Predictive Modeling: Training and evaluating the machine learning model.
Decision Making: Generating buy or sell signals based on model predictions.
Visualization: Plotting data and predictions for interpretation.
Contributing
Your contributions to improve the project are welcome. Please feel free to fork the repository, make improvements, and submit a pull request.

## License
This project is released under the MIT License.

## Disclaimer
This project is for educational purposes only. The predictive models and strategies developed here are not financial advice. Always conduct your own research and consult with a financial advisor before making investment decisions.
