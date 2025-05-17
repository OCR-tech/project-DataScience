# Predicting the Sale Price of Bulldozers

## Overview:
This project demonstrates a machine learning pipeline for predicting the future sale price of bulldozers based on their characteristics and previous sales data. The project is structured to include data pre-processing, model building, training, evaluation, hyperparameter tuning, and deployment. The final model will be able to make predictions on test data and extract feature importance to understand the factors influencing the sale price of bulldozers.

## Objectives:
- To predict the future sale price of bulldozers, given its characteristics and previous samples
- To build and train a model using a random forest regressor with time-series data
<!-- - To evaluate the model's performance using root mean squared log error (RMSLE) metric -->

## Data:
The dataset is downloaded from Kaggle and contains information about bulldozer sales, including features such as year, make, model, and various specifications. (Link: https://www.kaggle.com/c/bluebook-for-bulldozers/data)

## Steps:
- Data pre-processing
    - Import data and parsing dates
    - Sort dataframe by saledate
    - Add datetime parameters for saledate column
    - Convert string to categories
    - Fill missing values
    - Turn categorical variables into numbers
    - Split data into train/validation sets
- Building a model
    - Build a machine learning model using random forest regressor
- Training a model
    - Train a model using trained dataset
- Model evaluation
    - Evaluate a model with root mean squared log error (RMSLE) metric
- Tuning hyperparameters
    - Tune hyerparameters with RandomizedSearchCV
    - Train a model with the best hyperparamters
- Deployment
    - Make predictions on test data
    - Extract Feature Importance


## Usage:
- Open in Colab
- Run the notebook to execute the steps outlined in the project
- Use the trained model to make predictions on new data
- Extract feature importance to understand the factors influencing the sale price of bulldozers
- Save the trained model for future use
<!-- - Modify the code as needed to fit your specific use case or dataset -->

## Outcomes:
- A trained model capable of predicting bulldozer sale prices based on input features
- Insights into feature importance, helping to identify key factors influencing sale prices
<!-- - A well-documented and structured project that can be used as a reference for similar machine learning projects -->
<br>

![Alt text](https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds1a.png)



<!-- <br>
<div align="center">
    <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds1a.png" style="width:450px; height:auto; min-width:35%">
</div>
<br> -->

<!-- - The dataset is divided into training and validation sets, with the training set used to build the model and the validation set used to evaluate its performance.
- The dataset is pre-processed to handle missing values, convert categorical variables into numerical representations, and extract relevant features for the model. -->