# Graduate Admit Predict and Analysis: Project Overview

## Introduction

Millions of Indians dream of studying in some of the top universities of the world but what is the procedure of getting into them? How do they take in students and what do they expect from them? Here, I have done some analysis on the dataset provided by [Mohan S Acharya](https://www.kaggle.com/mohansacharya)  from Kaggle. My attempt is to explain the neccesary features required to boost your chances for getting an admit. The details regrading the dataset is given below.

## Contents
The dataset contains several parameters which are considered important during the application for Masters Programs.
The parameters included are :
1. GRE Scores ( out of 340 )
2. TOEFL Scores ( out of 120 )
3. University Rating ( out of 5 )
4. Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
5. Undergraduate GPA ( out of 10 )
6. Research Experience ( either 0 or 1 )
7. Chance of Admit ( ranging from 0 to 1 )

## Acknowledgements
This dataset is inspired by the UCLA [Graduate Dataset](https://www.kaggle.com/mohansacharya/graduate-admissions). The test scores and GPA are in the older format.
The dataset is owned by [Mohan S Acharya](https://www.kaggle.com/mohansacharya) 

## Code and resources used
**Python version**: 3.7
**Packages**: numpy, sci-kit learn, pandas, seaborn, matplotlib
## Exploratory Data Analysis
Did some EDA to analyse how some features affect the chances for getting an admit through various visualisations. 

<img src="https://github.com/Vaibhavnaudiyal92/Graduate-Admit-Predict-and-Analysis/blob/master/__results___29_1.png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
     
 
<img src="https://github.com/Vaibhavnaudiyal92/Graduate-Admit-Predict-and-Analysis/blob/master/__results___33_1.png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
     
<img src="https://github.com/Vaibhavnaudiyal92/Graduate-Admit-Predict-and-Analysis/blob/master/__results___36_1.png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
<img src="https://github.com/Vaibhavnaudiyal92/Graduate-Admit-Predict-and-Analysis/blob/master/__results___67_0.png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
## Model Building
I split the data into train and test sets in ratio 75:25 for training and testing the models.
I have used both tree and non-tree based models to find out which one works better. Following are the models used:
1. XGBoost
2. Lasso Regression
3. Linear Regression

## Model Performance
XGBoost regression model outperformed other models with following scores:
1. XGBoost Regression: RMSE = 0.06300048380978601
2. Lasso Regression  : RMSE = 0.06426751371730151
3. Linear Regression : RMSE = 0.06457303441764758

## Custom Input
I have also added a section where user can input his/her details and get a prediction on the basis of those details.
