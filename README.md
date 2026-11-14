# YES Bank Stock Closing Price Prediction

A Machine Learning Regression project focused on analysing historical YES Bank stock prices and predicting monthly closing prices using Python and Scikit-learn.

## Project Overview

The objective of this project is to analyse historical YES Bank stock-price data, identify patterns and relationships between stock-price variables, and develop regression models to predict the closing stock price.

This project follows a structured Machine Learning workflow, starting with data understanding and cleaning, followed by exploratory data analysis, feature engineering, model development and evaluation.

## Business Objective

To investigate historical YES Bank stock-price behaviour and build a regression model that estimates the closing stock price using available historical data.

## Dataset Description

The dataset contains 185 records and 5 columns representing monthly stock-price information.

| Feature | Description |
|---|---|
| Date | Date of the stock-price record |
| Open | Opening stock price |
| High | Highest stock price during the period |
| Low | Lowest stock price during the period |
| Close | Closing stock price (Target Variable) |

**Target Variable:** Close

**Machine Learning Type:** Supervised Learning – Regression

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Git and GitHub

## Project Workflow

The project follows these stages:

1. **Know Your Data** – Dataset loading, initial inspection and understanding.
2. **Understanding Variables** – Identifying features, data types and statistical characteristics.
3. **Data Wrangling** – Date conversion, sorting, duplicate checks and OHLC validation.
4. **Exploratory Data Analysis (EDA)** – Distribution analysis, visualisation and correlation analysis.
5. **Feature Engineering** – Preparing relevant features for regression.
6. **Data Preprocessing** – Preparing the dataset for model training.
7. **Model Building** – Training and comparing regression algorithms.
8. **Model Evaluation** – Evaluating model performance using suitable regression metrics.
9. **Hyperparameter Tuning** – Optimising model parameters and comparing results.

## Current Progress

### Completed

- Loaded the YES Bank stock-price dataset.
- Inspected dataset dimensions and column information.
- Performed statistical analysis using Pandas.
- Checked missing values and duplicate records.
- Converted the Date column into datetime format.
- Sorted records chronologically.
- Checked duplicate dates.
- Performed initial OHLC price validation.

### Upcoming

- Exploratory Data Analysis.
- Feature engineering.
- Regression model development.
- Model comparison and evaluation.
- Hyperparameter tuning.
- Final insights and conclusions.

## Repository Structure

```text
yes-bank-stock-price-prediction/
│
├── README.md
├── Yes_bank_data_project.ipynb
├── data_YesBank_StockPrices.csv
└── .gitignore
```

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/Emmanue775/yes-bank-stock-price-prediction.git
```

2. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Open the notebook using Google Colab or Jupyter Notebook.

4. Make sure the CSV dataset is available in the working directory and load it using:

```python
import pandas as pd

data = pd.read_csv("data_YesBank_StockPrices.csv")
```

5. Execute the notebook cells sequentially.

## Project Status

**In Progress**

This project is being developed as part of my practical learning in Data Analysis and Machine Learning, with a focus on regression techniques and financial time-series data.

---

*Developed by S. Emmanuel Godston Isaac*

[GitHub Profile](https://github.com/Emmanue775) · [LinkedIn Profile](https://www.linkedin.com/in/s-emmanuel-godston-isaac-ba149a308/)
