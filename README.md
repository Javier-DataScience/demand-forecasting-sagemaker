# Demand Forecasting with SageMaker

## Project Overview
Baseline end-to-end demand forecasting project using AWS SageMaker.

## Dataset
- Kaggle: Store Sales – Time Series Forecasting (Corporación Favorita)
- Files used: train.csv, stores.csv

## Model
- XGBoost
- Basic lag features
- Evaluation metrics: RMSE, MAE

## Project Structure
demand-forecasting-sagemaker/
├─ data/
├─ notebooks/
├─ scripts/
├─ src/
└─ README.md

## Workflow
1. Local EDA in notebooks
2. Preprocessing scripts
3. SageMaker training job
4. Single deployed endpoint
5. Basic evaluation
