# Maize Yield Prediction Project
**Overview**
This project aims to predict the yield of maize in Germany for future years using historical data on area harvested, production, precipitation, temperature, sun duration, and summer days. The project follows the data science and machine learning lifecycle, from data collection and cleaning to model training and evaluation.

**Table of Contents**
1. Project Description
2. Data
3. Data Cleaning
4. Exploratory Data Analysis
5. Modeling and Evaluation
6. Future Predictions
7. Usage
8. Requirements
9. Installation
10. Contributing

1. **Project Description**
The goal of this project is to develop and compare machine learning models for predicting maize yield in Germany. The models used include Linear Regression and Random Forest Regression. The performance of these models is evaluated using various metrics such as RMSE, MSE, and R-squared.

2. **Data**
The dataset includes maize data from 1961 to 2021 from FAOSTAT and climate data from DWD which was cleaned leaving the following features:

+ Year
+ Area harvested
+ Production
+ Yield
+ Precipitation (pre)
+ Temperature (tmp)
+ Sun duration (sun_d)
+ Summer days (sum_dys)

3. **Data Cleaning**
Data cleaning involved removing unnecessary columns, converting data types, pivoting from longer to wider format, merging the various datasets and ensuring consistency in the dataset. Visualizations and statistical analyses were performed to understand the data better.

4. **Exploratory Data Analysis**
Several visualizations were created to explore the data, including:

+ Time series plots of features
+ Heatmap using the correlation matrix to understand relationships between features
+ Correlation matrix
+ Line graph of the features
+ Box plot of the features

5. **Modeling and Evaluation**
Two models were trained and evaluated:

+ Linear Regression
+ Random Forest Regression

*Linear Regression Metrics*
+ Training RMSE: 5412.65
+ Test RMSE: 7845.39
+ Training MSE: 29,296,812.64
+ Test MSE: 61,550,094.18
+ Training R2: 0.927
+ Test R2: 0.890

*Random Forest Metrics*
+ Training RMSE: 2116.92
+ Test RMSE: 5936.79
+ Training MSE: 4,481,337.18
+ Test MSE: 35,245,438.38
+ Training R2: 0.989
+ Test R2: 0.937

**Comparison Plot**
Linear Regression
![View Graph](https://github.com/Som-diba/Maize_Yield_Prediction/blob/web/Linear_Regression.png)

Random Forest
![View Graph](https://github.com/Som-diba/Maize_Yield_Prediction/blob/web/Random_Forest.png)

6. **Future Predictions**
Predictions were made for future years using both models. These predictions can help in decision-making, risk assessment, financial planning, and more.

7. **Usage**
Prepare feature values for future dates.
Use the trained models to predict the yield.

8. **Requirements**
Python 3.7+

Libraries:
+ pandas
+ numpy
+ scikit-learn
+ matplotlib
+ seaborn

9. **Installation**
Clone the repository:

https://github.com/Som-diba/Maize_Yield_Prediction.git

10. **Contributing**
Contributions are welcome!

By following these steps above, you should be able to replicate the analysis, visualize the results, and make predictions for future maize yields using both Linear Regression and Random Forest models.