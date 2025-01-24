# Transformer-Based-Feature-Representation-Technique-For-Building-A-Robust-Classifier
This project implements a robust classifier for network intrusion detection using transformer-based feature representation. It involves advanced data preprocessing, feature selection, and Transformer model.

#Methodology
Data Preprocessing: Handled missing values, balanced data using SMOTE, and encoded categorical features.
Feature Selection: Used Correlation Analysis, Chi-Square tests, and Random Forest for selecting the most important features.
Model Architecture: Adapted DistilBERT for tabular embeddings and used a classification layer for final predictions.

#Results 
Results are in the form of confusion matrix and classification report which helps us to analyze the performance of the model, subsequent fine tunning can be done based on these metrics.

#Model details 
DistilBERT Model 
which is a light weight model with less parameters and efficient for the available resources.
Transformer model is used because for their ability to capture patterns from the sequential data.

#Dataset Deatils 
The dataset used id UNSW-NB-15 which is publically availbale in Kaggle and linl is provided below to access it.
https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15

Files train.py provides a code for training and test.py provides a code for testing and UI.
