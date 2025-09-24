# Customer_Churn
A data science/machine learning project predicting customer churn using a random forest classifier.

## Project Overview
This project builds a **Random Forest Classifier** to predict customer churn.  
The model can be used to:
- Identify at-risk customers for targeted retention campaigns  
- Understand the key drivers of churn to inform business strategy  

The model achieves an ROC-AUC of ~0.84 while being weighted to reduce false negatives.

## Project Structure
- **Section 2**: Data cleaning, encoding categorical variables, and removing unnecessary columns  
- **Section 3**: Train/test split, Random Forest model training, and hyperparameter tuning (including class weighting to account for churn costs)  
- **Section 4**: Visualisation of feature importance and model performance metrics  
- **Section 5**: Business insights and conclusions

## Google Colab Link
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nV8d742xNV_z_n_O61QrVK3jCjFG8d2A?usp=sharing)

## Data Source
This project uses the [IBM Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), available publicly on Kaggle.

