# Data Science Projects

A collection of standalone machine learning and data science projects, built as coursework/practice for Conestoga's ML Programming 1. Each project lives in its own folder with its dataset(s), a Jupyter notebook, and a dedicated README.

## Projects

### [KMeanClusteringFifaDataSet](KMeanClusteringFifaDataSet)
Implements the K-Means clustering algorithm from scratch in Python/pandas using the FIFA 22 players dataset (`players_22.csv`), clustering players on features like overall rating, potential, wage, value, and age. The custom implementation is then compared against scikit-learn's reference `KMeans`.

**Tech:** Python, pandas, NumPy, scikit-learn

### [OlympicMedalPredictor](OlympicMedalPredictor)
A linear regression model that predicts the number of medals a country/team will win, trained on historical Olympic Games data. Includes a data-preparation notebook (`data-preparation.ipynb`) that aggregates raw athlete-event records into per-team, per-year summaries (athletes, age, height, weight, medals) and a modeling notebook (`machine-learning.ipynb`) that trains and evaluates the regression.

**Tech:** Python, pandas, scikit-learn, Seaborn

### [TimeForcastingXGBoost](TimeForcastingXGBoost)
An energy consumption forecasting project using XGBoost (gradient-boosted decision trees) on hourly power usage data (`AEP_hourly.csv`). Uses time-series cross-validation for more reliable training, forecasts one year into the future, and persists the trained model (`model_V01.json`) for reuse elsewhere.

**Tech:** Python, pandas, NumPy, XGBoost, scikit-learn, Seaborn, Matplotlib, Time Series Split

## Getting Started

Each project is self-contained. To run one:

1. Navigate into the project folder.
2. Install the dependencies listed in that project's README (pandas, numpy, scikit-learn, xgboost, seaborn, matplotlib as applicable).
3. Open the notebook(s) with Jupyter and run the cells in order.

```bash
pip install pandas numpy scikit-learn xgboost seaborn matplotlib jupyter
jupyter notebook
```
