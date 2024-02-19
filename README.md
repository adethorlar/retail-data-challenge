# Retail Data Challenge: Customer Segmentation and Lifetime Value Analysis

### Overview
This project focuses on exploring customer segmentation and customer lifetime value to enhance sales forecasting for a UK-based gift supplier. The goal is to understand customer behaviors and patterns from over 1 million transactions spanning from 2009 to 2011, enabling targeted marketing and improved sales strategies.

### Business Context
The client is a gift supplier in the UK, dealing with wholesalers and resellers. They face challenges with high-volume sales, cancellations, and bulk orders, especially during peak seasons. The objective is to analyze customer data to optimize sales forecasting and business profitability.

### Project Objectives
- Data Understanding: Delve into the dataset to identify sales patterns and customer behaviors.
- Customer Segmentation: Use RFM analysis to segment customers based on their purchasing behaviors.
- Sales Forecasting: Apply SARIMA and Prophet models for accurate sales forecasting.

### Dataset Overview
- Size: 1 million rows and 8 columns
- Coverage: Transactions from 41 countries, with 90% from the UK
- Challenges: Data preprocessing required due to missing values, duplicate rows, and anomalies

## Methodology

### Data Cleaning and Preprocessing
- Addressed missing values and duplicate rows
- Created a new column to indicate cancelled orders
- Removed outliers and standardized the data for analysis

### Exploratory Data Analysis (EDA)
- Analyzed sales patterns, identifying seasonality and top-selling products.
- Investigated the geographical distribution of orders.

### Feature Engineering for Customer Segmentation
- Developed features based on RFM (Recency, Frequency, Monetary) analysis.
- Performed PCA for dimensionality reduction.

### Customer Segmentation
- Applied K Means Clustering to segment customers into three distinct groups.
- Evaluated the silhouette score to assess the quality of clustering.

### Sales Forecasting
- Utilized SARIMA and Prophet models to forecast sales for each customer cluster.
- Assessed model performance using MAPE (Mean Absolute Percentage Error).

## Results and Recommendations

- Customer Segmentation: Identified three unique customer segments, providing insights into different spending behaviors.
- Sales Forecasting: Demonstrated the effectiveness of Prophet model in handling seasonal trends, with competitive forecasting accuracy.
- Recommendations:
  - Develop a retention plan for high-value customers.
  - Further divide Cluster 0 using microsegmentation.
  - Continue refining forecast models for better accuracy.

## Conclusions
This project successfully segments customers into distinct groups and applies advanced forecasting models to predict sales. The findings offer valuable insights for targeted marketing and sales strategy optimization, demonstrating the potential for significantly improved business outcomes.
