# Customer Segmentation for Online Retail

## Project Overview
This project aims to segment customers of an online retail store using clustering techniques. The analysis is based on the "Online Retail II" dataset, which contains transactions from 2010-2011.

## Goals
* Perform exploratory data analysis (EDA) to understand the data and its quirks.
* Prepare the data for clustering by handling missing values, anomalies, and feature engineering.
* Apply K-Means clustering to identify distinct customer groups.
* Interpret the clusters to derive business insights.

## Dataset
The dataset contains all the transactions occurring for a UK-based online retail between 01/12/2009 and 09/12/2011.

## Key Steps
1. **Data Exploration:** Understanding distributions, missing values, and anomalies (returns, adjustments, non-product codes).
2. **Data Preprocessing:** Cleaning data, filtering out non-product transactions, and aggregating data on a customer level.
3. **Feature Engineering:** Creating RFM (Recency, Frequency, Monetary) features.
4. **Clustering:** Applying K-Means and evaluating the results.

## Technologies Used
* Python
* Pandas
* Scikit-learn
* Matplotlib/Seaborn

## How to Run
1. Clone the repo.
2. Install requirements: `pip install -r requirements.txt`.
3. Place the `online_retail_II.xlsx` file in the `data/` directory.
4. Open and run the Jupyter notebook `notebooks/01_online_retail_eda_clustering.ipynb`.