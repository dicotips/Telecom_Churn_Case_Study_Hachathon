# Telecom Churn Prediction - Study Case

## Table of Contents

* [Introduction](#Introduction)
* [Methods Used](#Method-Used)
* [Download and Setup](#Download-and-Setup)
* [Problem Statement](#Problem-Statement)
* [Business Goal](#Business-Goal)
* [Data Preparation](#Data-Preparation)
* [Model Building and Evaluation](#Model-Building-and-Evaluation)
* [Conclusions](#Conclusions)

## Introduction 

In this Study Case I built a predictions model predict the customers to be prone to leave the telecom service.

This repository contains the following files required by the assignment:

* Jupyter Notebook file with the Data Preparation and Model Building to predict the Telecom Churn case study.
* Submittion to Kraggle file (CSV)

### Methods Used
* Data Preparation
* Model Building

### Technologies
* Python
* Pandas
* Numpy
* Seaborn & matplotlib
* Statsmodels
* SkitLearn
* Jupyter Notebooks

## Download and Setup
### Prerequisites

This project needs Anaconda installed in the computer.

For more details about the instalation, go to:  https://docs.anaconda.com/anaconda/install/index.html
### How to Run

You can download the source code cloning this repository using Git:

1. Open your favorite Terminal app (Unix, Linux or Macos), such as Terminal, Command, Console, iTerm2, so on.

2. Clone the repository

```
git clone https://github.com/dicotips/Telecom_Churn_Case_Study_Hachathon.git
```

3. Open the ** *.ipynb** notebook file in Anaconda.

```
jupyter notebook TelecomChurnCaseStudy.ipynb
```

## Problem Statement

**Source:** UpGrad Study Case description

*In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.*

*For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.*

*In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.*

### Business Goal

*It is your job to predict if a customer will churn, given the ~170 columns containing customer behavior, usage patterns, payment patterns, and other features that might be relevant. Your target variable is "churn_probability"*

---

### Data Preparation:

1. Data Clearning and Missing Data Analysis.
2. Outlier Analysis & Treatment.
3. Deriving Categorical Columns.
4. Univariate Analysis.
5. Bivariate Analysis.
6. Multivariate Analysis.

### Model Building & Evaluation

1. Training and Test data split.
2. Feature Scaling - StandardScaler.
3. Feature Engineering & Selection using RFE and Variance Inflation factor.
4. Model preperation using OLS & Linear Regression.
5. Residual Analysis.
6. Model Evaluation & Assessment.
7. Prediction.
8. Final Conclusion & Analysis.

### Conclusions

TBD