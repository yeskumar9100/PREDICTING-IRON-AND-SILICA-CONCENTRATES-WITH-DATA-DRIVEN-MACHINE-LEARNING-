# PREDICTING-IRON-AND-SILICA-CONCENTRATES-WITH-DATA-DRIVEN-MACHINE-LEARNING-

Data-Driven Prediction of Fe and Silica Concentrate
This repository contains code, data, and models for predicting iron and silica concentrate percentages using machine learning (XGBoost, Lasso) from mineral processing plant data.

Features
Full data exploration, cleaning, and preprocessing workflow

Predictive models for %Iron and %Silica Concentrate using XGBoost and Lasso

Performance evaluation with visualizations

Example results and metrics

Ready-to-use notebooks

Dataset
Large industrial dataset (CSV) with variables such as % Iron Feed, % Silica Feed, reagent flows, pH, air flows, levels, and target variables (% Iron Concentrate, % Silica Concentrate).

All sensitive data anonymized.

Notebooks
MINING.ipynb, MINING-30-code.ipynb, and checkpoints with step-by-step EDA and model building.

Walk-throughs from data import to final predictions.

Requirements
Python 3.7+

pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, joblib

Install all dependencies with:

bash
pip install -r requirements.txt
Usage
Clone the repository:

bash
git clone https://github.com/your-username/mining-ml-prediction.git
Place your data files in the data/ folder.

Open and run Jupyter Notebooks in notebooks/.

(Optional) Use scripts in src/ for automation.

Results
Best model:

XGBoost Regressor

MSE: 0.2859, MAE: 0.3857, R²: 0.7725

Lasso

MSE: 1.1130, MAE: 0.8397, R²: 0.1144
