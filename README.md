This repository contains code for a machine learning model designed to predict the solubility and bioactivity class of compounds by generating and evaluating chemical descriptors.

Features:

Chemical Descriptors Generation: The code calculates various molecular descriptors such as molecular weight, logP, and others to represent compounds in a format suitable for machine learning models.

Prediction and Classification : Using the generated chemical descriptors, the classification-based machine learning model, classifies the compounds into different levels of the solubility from 1 to 5(lowest to highest).

data/: Contains the dataset used for training and testing the model (CSV or other formats).

scripts/: Python scripts for generating descriptors, training the machine learning model, and running predictions.

models/: Saved trained machine learning models.

notebooks/: Jupyter notebooks for experimentation and visualization of the results.

Requirements:

Python 3.x

Libraries: scikit-learn, rdkit, pandas, numpy, matplotlib, seaborn, xgboost and a few more.
