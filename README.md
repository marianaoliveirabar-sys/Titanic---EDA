# Titanic EDA

This repository contains an Exploratory Data Analysis of the **Titanic** dataset, focusing on understanding the data structure, quality, and key patterns related to passenger survival.

## Objective

The goal of this project is to perform a structured EDA that includes:

* Assessment of data quality and missing values
* Univariate analysis of numerical and categorical variables
* Multivariate analysis to explore relationships between variables
* Feature engineering insights, particularly from the **Name** and **Cabin** variables
* Statistical measures of association and correlation
* Dimensionality reduction using an MCA like approach via PCA on a one hot encoded matrix

## Dataset

The analysis is based on the public Titanic dataset from Kaggle (https://www.kaggle.com/competitions/titanic/data), which includes two files:

* `train.csv`  contains the target variable **Survived**
* `test.csv`  contains the same predictors but without the target

Each observation corresponds to a passenger and includes demographic, socio economic, and travel related information.

## Content of the Repository

* `Titanic_EDA.ipynb`  main Jupyter Notebook with the complete exploratory analysis
* `train.csv`  training dataset
* `test.csv`  test dataset

## Methods and Analysis

The notebook covers the following main steps:

1. Data loading and initial inspection
2. Analysis of duplicates and variable types
3. Missing values analysis, highlighting the high proportion of missing values in **Cabin**
4. Univariate analysis, divided into:
   * Categorical variables
   * Discrete numerical variables
   * Continuous numerical variables
5. Multivariate analysis, including:
   * Variables versus target
   * Variables versus variables
   * MCA like analysis using PCA on one hot encoded categorical variables

## Key Findings

* Survival is associated with **Sex**, **Pclass**, and **Fare**
* **Cabin** has a very high proportion of missing values
* Useful information can be extracted from **Name** through passenger titles
* The training and test sets show similar distributions for most key variables

## Requirements

The notebook was developed in Python using the following main libraries:

* pandas
* numpy
* matplotlib
* scipy
* scikit learn

## Author

**Mariana Oliveira**
