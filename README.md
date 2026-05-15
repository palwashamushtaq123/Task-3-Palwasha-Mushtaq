# **House Price Prediction using Machine Learning**

**Project Overview**

This project focuses on predicting house prices using Machine Learning regression models. The dataset contains 2000 house records with multiple housing features such as area, bedrooms, bathrooms, floors, year built, location, condition, garage availability, and property prices.
The main objective of this project is to analyze housing data, identify important patterns, and build regression models capable of estimating house prices.

**Dataset Information**
 - Total Records: 2000
 - Total Features: 10
 - Numerical Features
 - Area
 - Bedrooms
 - Bathrooms
 - Floors
 - YearBuilt
 - Price
   
**Categorical Features:**
 - Location
 - Condition
 - Garage
   
**Technologies Used**
 - Python
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn
 - Scikit-learn

**Workflow**
 - Data Preprocessing

    Checked dataset shape and structure
    Handled missing values
    Checked duplicate records
    Dropped unnecessary Id column
    Exploratory Data Analysis (EDA)
 - Statistical summary

    Distribution plots

    Countplots

    Boxplots
   
    Correlation heatmap
 - Feature Engineering
    Label Encoding

   One-Hot Encoding
 - Feature Scaling using StandardScaler
  
 - Machine Learning Models
    Linear Regression

    Random Forest Regressor

     Decision Tree Regressor
**Model Evaluation**
 - Model	MAE	RMSE	R² Score
 - Linear Regression	243241.97	279859.72	-0.0067
 - Random Forest Regressor	253075.57	292584.31	-0.1003
 - Decision Tree Regressor	338416.80	411411.20	-1.1756
**Key Insights**
 - Most features showed weak linear relationships with house prices.
 - House prices varied significantly across different locations and conditions.
 - Random Forest captured non-linear patterns better than Decision Tree.
 - The dataset may require additional real estate features for stronger predictions.
   
**Conclusion**

**This project demonstrates a complete Machine Learning regression workflow including preprocessing, visualization, feature engineering, model training, and evaluation for house price prediction.
The project also highlights the importance of feature quality and model selection in predictive analytics.**
