# House Prices Prdiction App

## 1. Description:
Thank you for checking out our App! An accurate prediction on the house price is important to prospective homeowners, developers, investors and other real estate market participants. The availability of a house price prediction model helps fill up an important information gap and improve the efficiency of the real estate market. The data is from Kaggle and it describes almost every aspect of the residential homes in Ames, Iowa. By including different explanatory variables chosen from 79, our App is able to predict the sale price of the house. 

+ Instruction: There are 3 sections. The first section shows the sale prices by different variables along with some geographic features. The second section shows the the importance of each variable when doing prediction using different models. The third section shows the variables selected by the user and the corresponding predicted price.

+ Prediction Models: Three models are used for prediction, including Random Forest, LASSO Regression, and classification and regression tree (CART). Random Forest and LASSO Regression predict the actual predicted price, while CART predicts whether the house has a high sale price or a low sale price. When CART returns a low sale price, a poor house picture will be displayed. When CART returns a high sale price, a luxury house picture will be displayed.

## 2. Packages:

Our App runs on flexdashboard/Shiny platform in statistical software R. Here is a list of packages or library required for running:

+ library(flexdashboard)
, library(plotly)
, library(ggplot2)
, library(tidyverse)
, library(leaflet)
, library(htmltools)
, library(kableExtra)
, library(glmnet)
, library(randomForest)
, library(rpart)
, library(rpart.plot)

## 3. Division of work:

+ Brian (Xinyu) Guo worked on LASSO regression prediction model.
+ Qier Meng worked on data rearrangement, data imputation and Random Forest prediction model.
+ Sindy Du worked on CART prediction model.
+ Xiaoyan Zhang worked on cleaning up the geographic features and map display.
+ All four members worked on putting up the plots and the results together.

## 4. Links:

+ Link to App: https://xinyu-guo.shinyapps.io/House_Prices_Prediction/

+ Link to video:

+ Reference:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview

