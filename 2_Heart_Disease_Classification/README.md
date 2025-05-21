# Heart Disease Classification

## Objectives:
- To classify the presence of heart disease in patients based on various health metrics using a classification model
- To build a model using machine learning techniques, including hyperparameter tuning and model evaluation
- To compare different classification models and select the best one based on performance metrics for heart disease prediction

## Steps:
1. Data pre-processing
    - Load data
    - Data exploration (Exploratory Data Analysis: EDA)
2. Modelling
    - Model comparison
    - Hyperparameter tuning
3. Hyperparameter tuning with RandomizedSearchCV
4. Hyperparameter tuning with GridSearchCV
5. Model evaluation
    - Calculate evaluation metrics using cross-validation
    - Feature importance
5. Experimentation
    - Evaluation metric

## Usages:
- Open [notebook](https://colab.research.google.com/github/OCR-tech/project-DataScience/blob/main/2_Heart_Disease_Classification/notebook.ipynb) in Colab and run the code cells
- Use the trained model to make predictions on new data

## Data:
- The dataset is downloaded from [file](heart-disease.csv) or Kaggle [Heart Disease UCI](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset), and contains information about heart disease patients, including various health metrics.

## Outcomes:
- A trained model capable of predicting heart disease presence based on patient health metrics.
<br><br>

<p align="center"><b>Confusion Matrix for Prediction of Heart Disease Presence</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds2a.png"/>
</div>
<br><br>
<p align="center"><b>Comparison of cross-validated classification metrics</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds2b.png"/>
</div>
<br><br>
<p align="center"><b>Feature Importance</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds2c.png"/>
</div>
<br>