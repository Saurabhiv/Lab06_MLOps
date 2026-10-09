## Overview
This repository contains the implementation of Practical 06 for SCSE3040 (MLOps), focused on tracking and managing machine learning experiments using **MLflow**.
The practical uses a delivery-time prediction task to demonstrate how experiment parameters, evaluation metrics, and trained models can be recorded and compared.

## Objectives
* Track machine learning experiments using MLflow.
* Log model parameters and evaluation metrics.
* Compare multiple model runs using Mean Absolute Error (MAE).
* Identify the best-performing experiment.
* Register and load a trained model using the MLflow Model Registry.
* Track Linear Regression and Decision Tree experiments.

## Technologies Used
* Python
* MLflow
* pandas
* NumPy
* scikit-learn
* SQLite

## Experiments
The practical includes:
* Random Forest models with different hyperparameter settings.
* A Linear Regression baseline.
* Decision Tree models with different maximum depths.
* MLflow run tracking and metric comparison.
* Model registration and loading for prediction.

## Evaluation Metric
**Mean Absolute Error (MAE)** measures the average absolute difference between actual and predicted delivery times. A lower MAE indicates smaller prediction errors.

## How to Run
1. Clone or download this repository.
2. Set up and activate a Python virtual environment.
3. Install the required libraries, including MLflow, pandas, NumPy, and scikit-learn.
4. Open `P06.ipynb` in VS Code or Jupyter Notebook.
5. Run the notebook cells in order.
6. Start the MLflow UI using the tracking database path configured in the notebook.
7. View experiment runs, parameters, and metrics in the MLflow interface.

## Learning Outcome
This practical demonstrates how MLflow helps organize machine learning experiments, compare model performance, preserve experiment details, and manage trained models.

## Author
**Saurabhi**
