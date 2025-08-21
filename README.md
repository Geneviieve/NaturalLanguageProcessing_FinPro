# FinPro | NatrualLanguageProcessing 

Overview:
This repository contains two machine learning models. Model 1 is a binary classifier using TF-IDF + Logistic Regression to detect whether a quote is motivational. On the other hand, model 2 is a multiclass classifier using DistilBERT to predict a motivational category from 115+ predefined categories. Quotes that are predicted as not motivational will not go through the second stage.

Requirements:
  - Python 3.9+
  - transformers
  - torch
  - scikit-learn
  - pandas
  - numpy

Datasets:   
We use two different preprocessed datasets for each model, both from preprocessed the same original dataset:
  - Dataset 1: 'binaryDataFirstModel.csv' for model 1 (binary classification)
  - Dataset 2: 'cleanedDataSecondModel_merged.csv' for model 2 (motivational category classification with merged categories)
