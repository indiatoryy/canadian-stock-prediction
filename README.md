# Canadian Stock Price Prediction Project

## Project Overview

This project aims to develop a machine learning model to predict stock prices for the top Canadian companies. The project involves multiple phases, including data collection, exploratory data analysis (EDA), feature engineering, and the integration of sentiment analysis from news articles to improve the model's accuracy.

## Current Progress

### Data Collection
I have collected historical stock price data for the top Canadian companies. The data spans from January 1, 2010, to April 30, 2024. The list of companies includes:

* Royal Bank of Canada (RY.TO)
* Toronto-Dominion Bank (TD.TO)
* Bank of Nova Scotia (BNS.TO)
* Enbridge Inc. (ENB.TO)
* Canadian Natural Resources Limited (CNQ.TO)
* Shopify Inc. (SHOP.TO)
* Bank of Montreal (BMO.TO)
* BCE Inc. (BCE.TO)
* TC Energy Corporation (TRP.TO)
* Canadian National Railway Company (CNR.TO)
* Alimentation Couche-Tard Inc. (ATD.TO)
* Suncor Energy Inc. (SU.TO)
* Fortis Inc. (FTS.TO)
* Metro Inc. (MRU.TO)
* Magna International Inc. (MG.TO)
* Manulife Financial Corporation (MFC.TO)
* Power Corporation of Canada (POW.TO)
* Sun Life Financial Inc. (SLF.TO)
* National Bank of Canada (NA.TO)
* Brookfield Asset Management Inc. (BAM.TO)

### Exploratory Data Analysis (EDA)
I performed an extensive EDA to understand the dataset, uncover patterns, detect anomalies, test hypotheses, and check assumptions. The key steps included:

* Data Overview: Examined the structure and summary statistics of the data.
* Data Cleaning: Handled missing values and ensured data integrity.
* Descriptive Statistics: Calculated mean, median, standard deviation, and other summary statistics.
* Visualization: line plots for closing prices, histograms for distribution, box plots for outlier detection, and heatmaps for correlation analysis.

### Sentiment Analysis
I performed sentiment analysis to better inform my model predictions. I started by gathering new headlines that related to the top Canadian companies. I gathered headlines based on company names, nicknames, and other keywords. I then used textblob to perform sentiment analysis and extract sentiment scores for each company. Finally, these sentiment scores were combined with the stock data to create a final dataset to train the model.

## Next Steps
Model Development:

* Split the data into training and testing sets.
* Develop and train machine learning models (e.g., Linear Regression, Random Forest, LSTM).
* Evaluate the performance of the models using appropriate metrics.
  
Model Evaluation and Optimization:

* Fine-tune hyperparameters to optimize model performance.
* Validate the model with unseen data to ensure generalizability.
