# Rossmann Sales Prediction
Machine Learning : Regression Project

We are provided with historical sales data for 1,115 Rossmann stores. We have to create a Machine Learning model to predict the sales.

![68747470733a2f2f6d656469612d63646e2e7472697061647669736f722e636f6d2f6d656469612f70686f746f2d732f31362f65312f65632f66372f726f73736d616e6e2e6a7067](https://github.com/cltgoutham/Capstone-2-Retail-Store-Sales-Prediction/assets/124442638/4588ec03-2dde-462c-9d68-a952bc2b4021)

**Introduction**

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

This project include Exploratory data analysis, Data preprocessing, Feature Engineering, Model building and evaluation. The models we used are Lenear Regressor, Lasso Regressor, Ridge Regressor, DecisionTree Regressor, RandomForest Regressor, XGBoost . For evaluating the model we use MSE, RMSE, RMPSE, R2 score.

**DATASET INFORMATION**

This dataset consist of two csv files:
1. Rossmann.csv - Datat including sales [Rossmann.csv file](https://drive.google.com/file/d/1oOjFOVVZXZFyrHNwONTZIWfqZpqfryR0/view?usp=drive_link)
2. Store.csv  - Data about the store [Store.csv file](https://drive.google.com/file/d/1B4_0Xo7gahc0VjODzoKC6F_amz_KRcXk/view?usp=drive_link)


# Approach to the Project

## 1.**Data Collection and Cleaning**
* Check for duplicate values in the dataset
* Checking null values
* Examining the dataset to get basic informations
* Merging the two dataset.

## 2.**Exploratory Data Analysis**
* Using different interactive plots made needed analysis
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis

  
![newplot](https://github.com/cltgoutham/Capstone-2-Retail-Store-Sales-Prediction/assets/124442638/711454cf-190c-4355-a9fa-e8506aacb288)
![download](https://github.com/cltgoutham/Capstone-2-Retail-Store-Sales-Prediction/assets/124442638/3d65455c-85d0-4136-a5c4-f73426f7d54f)
![newplot (2)](https://github.com/cltgoutham/Capstone-2-Retail-Store-Sales-Prediction/assets/124442638/462db3a2-1a20-443e-83f4-8f4a7846f640)

## 3.**Feature Engineering**
* Nullvalue Treatment
* Outlier Treatment
* Encoding
* Multicolenearity
* Feature Scaling
* Feature Selection
![download (1)](https://github.com/cltgoutham/Capstone-2-Retail-Store-Sales-Prediction/assets/124442638/e653fa69-1093-4a4f-a4f7-495373354877)


## 4.**Model Building**

We used 6 moddels for the analysis : LinearRegressor, LassoRegressor, RidgeRegressor, DecisionTree, RandomForest, XGBoost.

![Screenshot (2)](https://github.com/cltgoutham/Capstone-2-Retail-Store-Sales-Prediction/assets/124442638/f9b8a1d7-b132-4fc3-9d19-e57665d2873a)
![Screenshot (4)](https://github.com/cltgoutham/Capstone-2-Retail-Store-Sales-Prediction/assets/124442638/1542aba4-9ced-433e-b85f-7892a847b846)


## 5.**Model Evaluation**
4 Evaluation matrics are used for the evaluation of the Models.
* MSE - Mean squared error
* RMSE - Root mean squared errod
* RMPSE - Root mean squared percentage error
* R2 - R squared

## 5.**Conclusion**
According to the Model performance and scores compared from the evaluation metrics XGBoost Regressor was found to be the best fit model.

