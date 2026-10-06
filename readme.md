# Amazon Product Price Prediction using Machine Learning

## Project Overview
This repository contains an end-to-end Machine Learning solution designed to predict the selling price of products listed on Amazon. In competitive e-commerce markets, pricing strategies are heavily influenced by product category, customer ratings, discounts, seller dynamics, and user reviews. 

The goal of this project is to analyze historical product data, perform feature engineering, and train robust regression models to accurately estimate product prices and identify key factors driving price variations.

---

## Features & Workflow
- **Data Preprocessing & Cleaning:** Handling missing attributes, stripping currency/unit symbols, converting discount percentages, and cleaning text data.
- **Exploratory Data Analysis (EDA):** Visualizing price distributions, correlation heatmaps, category-wise average pricing, and rating-to-price dynamics.
- **Feature Engineering:** Text processing on product titles and descriptions using Natural Language Processing (NLP) techniques like TF-IDF and Sentiment Analysis.
- **Model Training:** Evaluating multiple regression algorithms including Linear Regression, Decision Trees, Random Forest, and XGBoost.
- **Evaluation Metrics:** Assessing model accuracy using Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and $R^2$ Score.

---

## Tech Stack
- **Programming Language:** Python 3.x
- **Libraries & Tools:** 
  - `Pandas` & `NumPy` for Data Manipulation
  - `Matplotlib` & `Seaborn` for Data Visualization
  - `Scikit-Learn` for Machine Learning & Evaluation
  - `XGBoost` for Gradient Boosting Models
  - `Jupyter Notebook` / `VS Code` for Development

---

## Project Structure
```text
├── data/
│   ├── raw_amazon_data.csv
│   └── processed_data.csv
├── notebooks/
│   └── Amazon_Price_Prediction.ipynb
├── src/
│   ├── preprocess.py
│   └── train_model.py
├── README.md
└── requirements.txt
