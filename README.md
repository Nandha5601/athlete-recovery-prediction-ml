# Athlete Recovery Prediction

A machine learning approach to predicting athlete recovery from training, sleep, and biometric data, developed as part of an MSc dissertation investigating recovery prediction for state sports department contexts.

## Overview

This project uses the CRISP-DM methodology to clean, explore, and model a synthetic athlete recovery dataset, comparing five regression models (Linear Regression, Random Forest, XGBoost, Gradient Boosting, K-Nearest Neighbours) to predict a continuous Recovery Score (0–100) from training load, sleep, and biometric variables.

**Best model:** Gradient Boosting (R² = 0.895, MAE = 7.090, RMSE = 8.979)
**Key finding:** Heart Rate Variability (HRV) is the dominant predictor of recovery, accounting for ~68% of feature importance.

## Dataset

[Athlete Recovery & Biometric Performance Dataset](https://www.kaggle.com/datasets/sarveshchhetri/athlete-recovery-and-biometric-performance-dataset) (Chhetri, 2026) — synthetic, longitudinal dataset of ~8,300 daily records from 300 athletes over 28 days. Published on Kaggle under an Apache 2.0 licence.

## Contents

- `Athlete_Recovery_Prediction.ipynb` — full analysis notebook: data cleaning, exploratory data analysis, feature engineering, model training, evaluation, feature importance, and residual analysis.

## Tools

Python, pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost

## Author

Nandhakumaaran Karthikeyan — MSc Information Technology, Leeds Beckett University
