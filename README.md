# Predicting Customer Purchasing Behavior

## Overview

This project focuses on predicting customer purchasing behavior in a coffee shop by analyzing various features such as product preferences, transaction amounts, and visit frequency. The primary goal is to develop a machine learning model that can accurately forecast sales outcomes and provide insights into the factors driving these sales. The insights derived from this analysis can help optimize marketing strategies and improve inventory management.

## Dataset

The dataset used in this project contains 149,116 transactions recorded at a coffee shop. The key features include:

- **transaction_id**: Unique identifier for each transaction.
- **transaction_date**: Date of the transaction.
- **transaction_time**: Time of the transaction.
- **transaction_qty**: Number of items purchased in each transaction.
- **store_id**: Identifier for the store where the transaction occurred.
- **store_location**: Location of the store.
- **product_id**: Identifier for the product sold.
- **unit_price**: Price per unit of the product.
- **product_category**: Category of the product (e.g., Coffee, Tea).
- **product_type**: Specific type within the product category (e.g., Gourmet brewed coffee).
- **product_detail**: Detailed description of the product.

The goal is to leverage these features to predict sales outcomes, such as the quantity of items purchased or to identify patterns in customer purchasing behavior.

## Data Exploration and Cleaning

- **Missing Values**: The dataset has no missing values.
- **Transaction Quantity**: The quantity purchased per transaction ranges from 1 to 8 items, with most transactions involving 1 or 2 items.
- **Unit Price**: The unit price varies from $0.80 to $45.00, with an average price of around $3.38.

The data is clean and ready for feature engineering and model training.

## Model Training

After preparing the data, several machine learning models were trained to predict purchasing behavior. The model's performance was evaluated using appropriate metrics, and the best-performing model was selected for further analysis.

## Conclusion

The project successfully developed a predictive model for customer purchasing behavior, which can be used to enhance decision-making in areas such as marketing and inventory management within the coffee shop.
