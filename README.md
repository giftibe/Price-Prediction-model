# Predicting Bulldozer Auction Prices (Submission for Kaggle competition)

This project aims to predict the sale price of heavy equipment, such as bulldozers, based on their usage, type, and configuration. The dataset is sourced from auction result postings and includes essential features like equipment configurations and usage history. The goal is to help build a reliable model to estimate auction prices for the heavy equipment industry.

## About Fast Iron

Fast Iron is a content-focused business that aids customers in creating enterprise data standards, cleansing, and maintaining data quality. By leveraging proprietary tools and a dedicated data team, Fast Iron has normalized over 2.5 million machine and customer records in the heavy equipment industry. They are building a "blue book for bulldozers" to allow customers to better assess their fleet's value at auction.

This competition is part of Kaggle's Startup Program. If your startup has a predictive modeling challenge, consider applying!

Photo credits: Antonis Lamnatos

## Problem Definition

> **How well can we predict the future sale price of a bulldozer based on its features, configuration, and historical auction data?**

## Data

The data for this project comes from the Kaggle competition "Bluebook for Bulldozers." There are three main datasets:

1. **Train.csv**: The training set, containing auction data through the end of 2011.
2. **Valid.csv**: The validation set, covering January 1, 2012, to April 30, 2012. Predictions made on this set contribute to the public leaderboard.
3. **Test.csv**: The test set, covering May 1, 2012, to November 2012. It is released in the final week of the competition and determines the final rankings.

## Evaluation

The competition uses **RMSLE (Root Mean Squared Logarithmic Error)** to evaluate predictions. The goal is to minimize the RMSLE between actual and predicted auction prices.

To participate:
- Download sample submission files from the [Kaggle competition page](https://www.kaggle.com/c/bluebook-for-bulldozers/data).
- Submission files must have a header: `SalesID,SalePrice` and contain two columns:
  - `SalesID`: The ID for the validation set, sorted in order.
  - `SalePrice`: Your predicted price for the sale.

## Features

A full data dictionary is provided by Kaggle, detailing the dataset's features. You can view it [here](https://www.kaggle.com/c/bluebook-for-bulldozers/data?select=Data+Dictionary.xlsx).

## Acknowledgements

This competition was launched under Kaggle’s Startup Program.

---

Feel free to explore and contribute to the project. Let's predict bulldozer prices with machine learning!
