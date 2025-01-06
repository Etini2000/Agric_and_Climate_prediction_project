# Agric_and_Climate_prediction_project

This repository contains a project focused on predicting Crop Production Index in Nigeria based on agricultural and climatic variables.
The project involved data cleaning, EDA, visualization and then model development.

## Aim
The aim of this project is to evaluate the impact of climate change on agricultural production in Nigeria

## Objective
1. To visualize how climatic, agricultural and economical variables has changed in Nigeria from 1961 to 2022
2. To evaluate the correlation/relationship between climatic variables and agricultural variables, and agricultural variables and economic variables
3. TO build and train model that can predict crop production index based on climatic variables

## Dataset
The <a href = "https://github.com/Etini2000/Agric_and_Climate_prediction_project/blob/main/nigeria_agricultural_economic_indicators_1950_2023.csv">Dataset</a> was downloaded from kaggle and it contain several features:

### Climatic Variables
1. Average temperature
2. Precipitation
3. Relative humidity

### Agricultural Variables
1. Crop Production Index
2. Livestock Production Index
3. Total Fisheries Production
4. Agricultural Land

### Economic Varibles
1. Gross Domestic Product
2. Inflation Rate

## EDA
Each of those variables were visualized
Additionally, correlation analysis was conducted to compare the relationships between variables

## Model Development and Evaluation
A **Linear Regression** and **Decision Tree Regressor** algorithm were used separately to build the model.

**Crop Production Index** was the predictor (y) variable.
The dataset was divided into 2; 20% testing set and 80% training set.

### Model Evaluation
 **R-squared = 96%**
 **MSE = 46.40**

Prediction was performed using random scenarios.

The project is summarise <a href = "https://github.com/Etini2000/Agric_and_Climate_prediction_project/blob/main/3MTT%20HACKATHON%202.0%20TECH%20FOR%20GOOD!%20(1).pdf">here</a>  




