Project Overview
This repository showcases an Exploratory Data Analysis (EDA) on eCommerce transaction data, enriched with customer segmentation using clustering and lookalike modeling techniques. The goal is to uncover actionable insights, understand customer behavior, and develop targeted business strategies.

Repository Contents
1. Datasets
The repository contains three key datasets:

Customers.csv: Customer demographics and region data.
Products.csv: Details about products, categories, and pricing.
Transactions.csv: Records of transactions, including dates, quantities, and total values.
2. Outputs
EDA Report:
A comprehensive PDF summarizing findings, including:

Customer analysis
Product trends
Regional performance
Sales insights
Clustering Results:
Segmentation of customers into distinct clusters for targeted marketing.

Lookalike Modeling:
Identification of potential high-value customers based on existing data patterns.

Code:
Python scripts for EDA, clustering, and lookalike modeling.

How to Use
Clone this repository:
git clone https://github.com/Shoaibzz/Zeotap_DataAnalysis


Install required Python libraries:
pip install -r requirements.txt
Run the EDA and analysis notebook:
jupyter notebook eda_analysis.ipynb
Analysis Highlights
EDA Summary
Key Metrics:
Total Transactions: 1,000
Unique Customers: 200
Unique Products: 100
Top Performing Regions:
South America is the leading contributor, generating $219,352.56 in revenue.
Popular Product Categories:
Books and Electronics dominate sales.
Clustering Analysis
Customers were segmented into 3 clusters based on purchasing behavior and regional data:

Cluster 1: High-value customers (focus group for premium offers).
Cluster 2: Mid-value customers (opportunity for upselling).
Cluster 3: Low-value customers (target with cost-efficient campaigns).
Lookalike Modeling
A predictive approach to identify potential high-value customers using data patterns from existing high-spenders.

Visualizations
Key visualizations include:

Region-wise Sales: Bar chart of revenue across regions.
Top Product Categories: Category-wise sales performance.
Customer Segmentation: Scatter plot of customer clusters.
Correlation Heatmap: Relationships among numerical features.
Sales Trends: Line chart of monthly sales over time.


Requirements
Python: 3.x
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter



Contact
For any queries or feedback:
Name: Mohammed Shoaib
Email: rmshoaib0196@gmail.com
