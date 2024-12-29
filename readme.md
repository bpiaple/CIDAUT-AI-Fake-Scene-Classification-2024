# CIDAUT AI Fake Scene Classification 2024 - Brice Piaple Dada

## Introduction
This project is a fake scene classification project. The goal is to classify images of fake scenes into 2 categories: `real` and `fake`. The project is for the CIDAUT AI Fake Scene Classification 2024 competition on Kaggle. Link to the competition: [CIDAUT AI Fake Scene Classification 2024](https://www.kaggle.com/competitions/cidaut-ai-fake-scene-classification-2024/overview).

## Data Description

The dataset consists of 2 folders: `train` and `test`. The `train` contain all the images for training the model. The `test` folder contains the images for testing the model. The images are in `jpg` format. In order to link the images to their respective classes, a `train.csv` file is provided. The `train.csv` file contains 2 columns: `image` and `class`. The `image` column contains the name of the image file and the `class` column contains the class of the image. The `class` column has 2 unique values: `real` and `editada`.

## Evaluation Metric

The evaluation metric for this competition is the `F1 Score`. The `F1 Score` is the harmonic mean of precision and recall. The formula for the `F1 Score` is given by: `F1 Score = 2 * (precision * recall) / (precision + recall)`. The `F1 Score` ranges from 0 to 1. The higher the `F1 Score`, the better the model. The `F1 Score` is calculated for each class and then averaged to get the final score.

## Baseline Model

The baseline model for this project is RestNet50. The model is trained on the training data and then used to make predictions on the test data. The predictions are then evaluated using the `F1 Score`. The `F1 Score` is used to evaluate the performance of the model.

## Conclusion

In this project, we have built a fake scene classification model using RestNet50. The model is trained on the training data and then used to make predictions on the test data. The predictions are then evaluated using the `F1 Score`. The `F1 Score` is used to evaluate the performance of the model. The model can be further improved by using data augmentation, hyperparameter tuning, and ensembling techniques.