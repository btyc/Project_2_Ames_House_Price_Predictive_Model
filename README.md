# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Ames Housing Data and Kaggle Challenge

Benjamin Toh, DSIF2


**Problem Statement**

Longer time are taken to sell a house due to long negotiation of the sale price


**Executive Summary**

The number of sales in houses have increased over the years. However, a sale of one single house is a long process and the delay was caused due to the negotiation between buyer and seller. As a seller, they will want to sell their house at a higher price while buyers will want to get a better lower price. Being a new tech start up firm, the idea is to create an application (app) to resolve this long extended negotiation time by providing the most accurate sale price based on the features of the house.

This project will be ultilizing the Ames Housing Dataset which is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses Furthermore, the predicted sale prices based on the best model will be submitted to participte in the Kaggle Challenge to determine how the model does against unknown data. Exploration, cleaning, features engineering and modelling will be done using this data, to acheive the best model in predicting the sale prices. A full model with all the features will be produce. A prototype will be generated by implementing feature selection method to select the 10 best features for modeling.

During the exploration process, outliers were observed for features with mid to high correlations with sale price as well as missing values for some of the features. Cleaning of the data were done to remove the outliers and filled in the missing values. To further improve the model performmance, datas were selected and transform into features that better represent to predict sale price. Linear, Ridge and Lasso regressions together with scaling, train test split, cross validations were used in the modeling stage. The evaluation will be judged based on Root Mean Square Error (RMSE).


**Conclusions and Recommendations**

After modeling and Kaggle Challenge, Lasso regression using MixMaxScaler with cross validation is deemed to the be best model. However, there seems to be more outliers within the dataset alhough the distribution of the residuals are normally distributed but there a few large differences between actual and predicted sale price. The prototype model which 10 best features has a much higher root mean squared errors and is deem to be underfitting due to the simplicity of the model and the non-linearity between the actual and predicted sale price. 

After modeling and Kaggle Challenge, Lasso regression using MixMaxScaler with cross validation is deemed to the be best model. However, there seems to be more outliers within the dataset alhough the distribution of the residuals are normally distributed but there a few large differences between actual and predicted sale price. The prototype model which 10 best features has a much higher root mean squared errors and is deem to be underfitting due to the simplicity of the model and the non-linearity between the actual and predicted sale price.

For a better and more accurate prediction for the sale price, users on our app will be recommended to key in more feature details other than just the 10 basic features. 

In conclusion, further modeling will be carry out to minimise the underfitting problem and root mean squared error (RMSE). A deeper exploration will be needed on the dataset and enhanced feature engineering will be perform.  


**Data**

Data sources: 

https://www.kaggle.com/c/dsi-us-11-project-2-regression-challenge/data?select=train.csv
https://www.kaggle.com/c/dsi-us-11-project-2-regression-challenge/data?select=test.csv

Data Dictionary

http://jse.amstat.org/v19n3/decock/DataDocumentation.txt
