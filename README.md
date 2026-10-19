# DATA4381 Capstone Project 1 — Fertility Rate Analysis

## Project Title
**Analyzing Regional Differences in Fertility Rates Using Global Health Indicators, 2000–2024**

**Team:** Angela R., Dat D., Ishaq A., Oluwateniola T.

## Research Question
How do health and socioeconomic indicators explain regional differences in fertility rates across world regions from 2000 to 2024?

## Project Overview
This project uses global health indicator data to examine regional fertility patterns and build predictive models for fertility rate. The analysis includes data validation, exploratory data analysis, preprocessing, baseline modeling, machine-learning model comparison, holdout evaluation, country-grouped cross-validation, feature importance, and regional error analysis.

## Repository Contents
- `Fertility_Capstone_Analysis.ipynb` — fully executed Jupyter Notebook with saved outputs, plots, metrics, and analysis.
- `health_indicators.csv` — dataset used by the notebook.
- `Fertility_Capstone_Presentation.pptx` — project presentation.
- `requirements.txt` — Python packages needed to run the notebook.

## Models Evaluated
- Mean Baseline
- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Evaluation
Models are compared using MAE, RMSE, and R². The notebook uses a 2020–2024 holdout period and GroupKFold validation by country to evaluate generalization.

## Preliminary Result
Random Forest produced the strongest preliminary fertility-rate performance in the saved holdout results, with MAE 0.276, RMSE 0.376, and R² 0.905. These results are predictive and do not establish causation.

## How to Run
1. Clone or download this repository.
2. Keep `health_indicators.csv` in the same folder as the notebook.
3. Install the packages in `requirements.txt`.
4. Open `Fertility_Capstone_Analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
5. Run all cells from top to bottom.

The submitted notebook is already fully executed, so its plots and model outputs should be visible directly in GitHub.
