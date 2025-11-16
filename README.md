This repository contains work completed for Assignment 3: Build Non-Linear Models (Part 1) in the DDS-8555 Predictive Analysis course at National University. The project also demonstrates applied non-linear modeling techniques appropriate for predictive analytics and data science portfolios.

Overview

The objective of this project was to develop, evaluate, and compare two non-linear predictive models using the Kaggle Regression with Abalone Dataset. The assignment includes conceptual analysis, simulated polynomial modeling, and two full predictive pipelines submitted to Kaggle.

The repository includes:

Conceptual Question 1 responses

Applied Question 8 simulations

Two predictive models for Kaggle

A Python notebook containing all computational steps

A written summary and APA-formatted references

Methods Implemented
1. Simulation & Model Selection (Applied Question 8)

The simulation work includes:

Generating synthetic polynomial data

Fitting forward and backward stepwise selection models

Evaluating model fit using Mallows’ Cp

Fitting Lasso regression with cross-validation

Running an additional sparse-model simulation for comparison

This section supports foundational concepts in non-linear regression, multicollinearity, and variable selection.

2. Abalone Dataset Modeling

Two modeling pipelines were developed:

Regularized Regression

One-hot encoding for categorical variables

Standardization of predictors

LassoCV for selecting the optimal penalty

Predictions exported as abalone_regularized.csv

Principal Components Regression (PCR)

Standardization of all predictors

Dimensionality reduction with PCA

Cross-validated component selection

Predictions exported as abalone_pcr.csv

Both submissions follow the structure required by the competition.

Repository Contents
File	Description
Albury-BloomADDS8555-3.ipynb	Complete notebook including simulations, preprocessing, modeling, diagnostics, and Kaggle output generation
abalone_regularized.csv	Predictions from the regularized regression model
abalone_pcr.csv	Predictions from the principal components regression model
Assignment Document	Written responses and academic analysis
Reproducibility

To reproduce results, download the Kaggle data files and place them in your working directory before running the notebook in Jupyter.

Key Results

Regularized regression produced the strongest predictive performance.

PCR improved stability under multicollinearity but did not provide the lowest prediction error.

Stepwise selection aligned with the true generating process in the cubic simulation.

Lasso effectively identified the dominant terms when polynomial correlations were moderate.

These findings demonstrate proficiency in model selection, non-linear modeling, and applied predictive analysis.
