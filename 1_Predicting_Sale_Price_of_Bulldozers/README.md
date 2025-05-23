# Project 1: Predicting the Sale Price of Bulldozer

## Objectives:
- To predict the sale price of bulldozers, given its characteristics and previous samples
- To build and train a model using a random forest regressor with time-series data
- To tune hyperparameters using RandomizedSearchCV

## Steps:
1. Data pre-processing
    - Import data and parsing dates
    - Sort dataframe by saledate
    - Add datetime parameters for saledate column
    - Convert string to categories
    - Fill missing values
    - Turn categorical variables into numbers
    - Split data into train/validation sets
2. Building a model
    - Build a machine learning model using random forest regressor
3. Training a model
    - Train a model using trained dataset
4. Model evaluation
    - Evaluate a model with root mean squared log error (RMSLE) metric
5. Tuning hyperparameters
    - Tune hyerparameters with RandomizedSearchCV
    - Train a model with the best hyperparamters
6. Deployment
    - Make predictions on test data
    - Extract Feature Importance

<!-- ## Usages:
- Open notebook in Colab and run the code cells
- Use the trained model to make predictions on new data
- Extract feature importance to understand the factors influencing the sale price of bulldozers -->

## Data:
- The dataset is downloaded from Kaggle [Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers/data), and contains information about bulldozer sales, including features such as year, make, model, and various specifications.

## Outcomes:
- A trained model capable of predicting bulldozer sale prices based on input features
- Insights into feature importance, helping to identify key factors influencing sale prices
<br><br>

<p align="center"><b>Prediction the sale price of bulldozers</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds1a.png"/>
</div>
<br><br>
<p align="center"><b>Top of feature importance</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds1b.png"/>
</div>
<br>
