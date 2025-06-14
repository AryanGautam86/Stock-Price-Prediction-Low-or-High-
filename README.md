# Stock-Price-Prediction-Low-or-High-
<br>
1-Data Loading
Tesla stock data is loaded from a CSV file containing Open, High, Low, Close, Volume, and Date.

2-Feature Engineering

open-close = Open - Close

low-high = Low - High

is_quarter_end = 1 if the month is a quarter-end (March, June, Sept, Dec), else 0

target = 1 if next day's close > current close, else 0

3-Exploratory Data Analysis

Time-series plotting of close price

Distribution plots & box plots for price features

Heatmaps to assess feature correlation

4-Model Training

Features scaled using StandardScaler

Train-test split (90/10)

Models:

Logistic Regression

Support Vector Classifier (SVM with polynomial kernel)

XGBoost Classifier

5-Evaluation Metrics

ROC AUC Score

Confusion Matrix
