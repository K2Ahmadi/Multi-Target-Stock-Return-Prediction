# Multi-Target-Stock-Returns-Prediction
Developed multiple different machine learning models on Python to predict the stock returns for Apple, IBM, and Microsoft

The objective of this project is to identify the most accurate AI model for predicting returns of multiple assets in the stock market. The assets selected for this study are Apple, Microsoft, and IBM. The regression models used for this project are the following: 

 - Random Forest Regressor
 - XG Boost Regressor 
 - Extra-trees Regressor
 - LGBM Regressor
 - Stacking Regressor
 - Meta's Prophet
 - MLP Regressor

This project consisted of data preparation, which involves feature engineering (e.g., creating new indicators such as Bollinger Bands, EMA, ADX) and feature selection using Recursive Feature Elimination (RFE). Following this, model selection and implementation were carried out. I used Azure Automated-ML to identify the most suitable machine learning algorithms for the dataset. Once the Regression models were obtained, I further hyperparameter-tuned them. Finally, model evaluation was conducted to assess the effectiveness of the models.

It is important to note that the Python Shap library was used to increase model transparency and interpretability. This allowed for a better understanding of which specific features had the greatest impact on the model outputs. 
