# Energy Usage Prediction in Northern Ireland (NI) Region

This project aims to predict energy usage in the Northern Ireland (NI) region using historical energy consumption data and machine learning techniques.

## Overview

Energy usage prediction is a crucial task for energy providers and policymakers to ensure efficient energy distribution and management. By accurately forecasting energy demand, stakeholders can optimize resource allocation, reduce costs, and maintain a reliable energy supply.

This project utilizes machine learning, particularly XGBoost, to predict energy usage in the NI region based on various features such as hour of the day, day of the week, month, and year. The model is trained on historical energy consumption data and evaluated using standard regression metrics.

## Dataset

The dataset used in this project contains hourly energy usage data in the NI region. It includes features such as:

- Datetime (timestamp)
- Energy usage in Megawatts (MW)

The dataset is split into training and testing sets to train and evaluate the predictive model effectively.

## Project Structure

The project is organized into the following main components:

1. Data Preprocessing: The dataset is preprocessed to handle missing values, set the datetime column as the index, and create additional features such as hour of the day, day of the week, month, etc.

2. Exploratory Data Analysis (EDA): Visualizations are generated to understand the relationship between energy usage and various features like hour, month, etc.

3. Model Development: XGBoost regression model is trained using the training data, and hyperparameter tuning is performed using GridSearchCV to find the best model configuration.

4. Model Evaluation: The trained model is evaluated on the testing data using mean squared error (MSE) and root mean squared error (RMSE) metrics.

5. Results Visualization: The predictions generated by the model are visualized alongside the actual energy usage data to assess the model's performance.

## Usage

To run the project, follow these steps:

1. Clone the repository to your local machine.
2. Download the dataset (`NI_hourly.csv`) and place it in the project directory.
3. Run the Jupyter Notebook (`energy_usage_prediction.ipynb`) to execute the code and generate predictions.
4. View the results and analysis in the notebook, and adjust parameters or experiment with different models as needed.

## Dependencies

- pandas
- numpy
- seaborn
- matplotlib
- xgboost
- scikit-learn

## Author

Denis Evmenenko
