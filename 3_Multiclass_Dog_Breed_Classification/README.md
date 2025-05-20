# Multi-class Dog Breed Classification

## Objectives:
- To identify the dog breed given a dog image using a multi-class image classifier
- To build a model using deep learning and transfer learning with TensorFlow and TensorFlow Hub
- To train and evaluate the model with prediction probabilities using 10000+ images of 120 dog breeds
<!-- - To deploy the model for making predictions on new images -->

## Steps:
1. Data pre-processing
    - Get data ready: images and labels
    - Create our own validation set
    - Preprocess images: turning into Tensors
    - Turn our data into batches
2. Building a model
    - Build a model using Keras sequential model and MobileNetV2
3. Training a model
    - Train a model using trained dataset
4. Model Evaluation
    - Make predictions on validation data using a trained model
5. Training a big dog model with full data
6. Deployment
    - Make predictions on test dataset and custom images


## Usages:
- Open [notebook](https://colab.research.google.com/github/OCR-tech/project-DataScience/blob/main/2_Multiclass_Dog_Breed_Classification/notebook.ipynb) in Colab and run the code cells
- Use the trained model to make predictions on new data
- Save the trained model for future use

## Data:
- The dataset is downloaded from Kaggle [Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/data), and contains information about dog breeds, including images and labels for 120 different breeds.

## Outcomes:
- A trained model capable of predicting dog breeds based on input images.
- A well-documented and structured project that can be used for similar image classification projects.
<br><br>

<p align="center"><b>Prediction the dog breed with prediction probabilities</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ds2a.png"/>
</div>
<br>