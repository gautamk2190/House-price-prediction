# Project Name
> to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
    - A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

- What is the background of your project?
    - data preprocessing, 
    - EDA
    - missing value imputations if required,
    - scaling,
    - train test split of the data,
    - modeling,
    - regularization tuning
    - model evaluation

- What is the business problem that your project is trying to solve?
    - Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.
    
- What is the dataset that is being used?
    - Housing data

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- R2 score using Ridge and Lasso
    - Ridge- Train:0.914459, Test:0.874812
    - Lasso- Train:0.916170, Test:0.875896

- Ridge Model top5 predictor variable
    - OverallQual_Excellent 0.370237
    - OverallQual_Very Good 0.265409
    - Neighborhood_NridgHt 0.253835
    - Neighborhood_Crawfor 0.243177
    - Neighborhood_Somerst 0.204905

- Lasso Model top5 predictor variable
    - OverallQual_Excellent 0.564182
    - OverallQual_Very Good 0.328329
    - Neighborhood_Crawfor 0.304465
    - Neighborhood_NridgHt 0.292958
    - Neighborhood_Somerst 0.248177

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.20.1
- pandas - 1.2.4
- matplotlib - 3.3.4
- seaborn - 0.11.1
- sklearn - 0.24.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by predicting the price of a house in Australian market.
- This project was based on [this tutorial](https://learn.upgrad.com/course/1994/).


## Contact
Created by [@gautamk2190] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->