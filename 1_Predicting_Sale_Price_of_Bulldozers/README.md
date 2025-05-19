# Project 1: Predicting the Sale Price of Bulldozer

## Objectives:
- To predict the sale price of bulldozers, given its characteristics and previous samples
- To build and train a model using a random forest regressor with time-series data
- To tune hyperparameters using RandomizedSearchCV
<!-- - To evaluate the model's performance using root mean squared log error (RMSLE) metric -->

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

## Usages:
- Open in Colab and run the [code](https://colab.research.google.com/github/OCR-tech/project-DataScience/blob/main/1_Predicting_Sale_Price_of_Bulldozers/notebook.ipynb)
- Use the trained model to make predictions on new data
- Extract feature importance to understand the factors influencing the sale price of bulldozers
<!-- - Save the trained model for future use -->
<!-- - Modify the code as needed to fit your specific use case or dataset -->

## Data:
- The dataset is downloaded from Kaggle and contains information about bulldozer sales, including features such as year, make, model, and various specifications (Link: https://www.kaggle.com/c/bluebook-for-bulldozers/data).

## Outcomes:
- A trained model capable of predicting bulldozer sale prices based on input features
- Insights into feature importance, helping to identify key factors influencing sale prices
<br><br>

<p align="center"><b>Top of feature importance</b></p>

![Alt text](https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds1a.png)

<!-- <br>
<div align="center">
    <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds1a.png" style="width:450px; height:auto; min-width:35%">
</div>
<br> -->
<br>