# Understanding the demand for Bike Sharing
> This project aims to help US bike-sharing company, BoomBikes, identify the factors (variables) affect the demand of shared bikes in the US market. The aims of this project is to identify the variables which are significant in predicting the demand for shared bikes, and how well do these variables describe the bike demand for BoomBikes.


## Table of Contents
* [0. Business Problem](#0-business-problem)
* [1. Data Understanding](#1-data-understanding)
* [2. Data Cleaning](#2-data-cleaning)
* [3. Data Analysis](#3-data-analysis)
    * [3.1 Categorical Variables](#31-categorical-variables)
    * [3.2 Numerical Variables](#32-numerical-variables)
    * [3.3 Final Summary](#33-final-summary)
* [4. Model Building](#4-model-building)
    * [4.1 Feature Engineering](#41-feature-engineering)
    * [4.2 Forward Selection](#42-forward-selection)
    * [4.3 RFE Method](#43-rfe-method)
    * [4.4 Residual Analysis of Training Data](#44-residual-analsis-of-training-data)
* [5. Making Predictions](#5-making-predictions)
* [6. Model Selection](#6-model-selection)

## General Information
### Business Problem
- This project aims to help US bike-sharing company, BoomBikes, identify the factors (variables) affect the demand of shared bikes in the US market, and how are each variables significant in predicting the demand for shared bikes, and how well do these variables describe the bike demand for BoomBikes.
### Business Background
- BoomBikes is bike-sharing company in the US that has seen its revenue drop due to the coronavirus pandemic and thus, is fidning the business very difficult to sustain in the US under such circumstances. As the US is gradually reopening as we move towards an endemic strategy in combatting the virus, BoomBikes wants to better understand the demand for shared bikes so as to better optimize their business strategy.
### Project Objective
- In this project, the project objective is to better understand the factors which impact the demand for shared bikes so as to understand the questions to the business problem above and better optimize their business strategy using the received the dataset.
- Dataset used is one on bike sharing, which contains feature columns such as date, season, year, month, holiday, weekday, working day, weather situation, temperature, feeling temperaiton, humiditiy, windspeed, count of casuaul counters, count of registered. The target column is the count of total rental bikes. 

## Conclusions
The three features that contribute strongly to the model are.
1. Year. This means that year is a important feature because more bikes are rented out during the second year (2019) when the company became more established and well-known in USA.
2. Not Spring. When the season is not spring, more bikes are rented out as Spring is a season when temperatures are lower and snow and dangerous weather conditions are more frequent. Note that this feature was featured engineered and not from the original dataset. 
3. Weather is not snow. When the weather is snowing, far fewer bikes are rented out as it is safer to ride, and there is a strong inverse relationshp, as indicated by high negative beta coefficient value. Note that this feature was featured engineered and not from the original dataset. 

## Technologies Used
python:  3.8.8
numpy:  1.19.5
pandas:  1.2.4
matplotlib:  3.3.4
seaborn:  0.11.1
plotly:  5.5.0
statsmodels:  0.12.2
sklearn:  0.24.1

## Contact
Created by [@bengcheo] - feel free to contact me!