# online-retail-customer-segmentation
The goal is to help businesses identify distinct customer groups—like loyal customers, high spenders, and at-risk users—for targeted marketing, personalized offers, and customer retention strategies.

This project focuses on customer segmentation using unsupervised learning techniques applied to the Online Retail dataset. The objective is to identify meaningful customer groups based on purchasing behavior using clustering models.

Problem Statement
Retail businesses deal with a large volume of transaction data. Without meaningful segmentation, personalized marketing and retention strategies are difficult to implement. This project builds a customer segmentation pipeline using machine learning to group similar customers based on key behavioral metrics.

Dataset
Source: UCI Online Retail Dataset

Fields: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

Total records after cleaning: 401,604

Approach
Data preprocessing and cleaning

RFM feature engineering (Recency, Frequency, Monetary)

Outlier handling and scaling

Clustering using:

K-Means

Agglomerative Clustering

DBSCAN

Cluster evaluation using Silhouette Score and Elbow Method

Cluster profiling for business insight

Results
K-Means produced the most interpretable and well-separated clusters

Customers were grouped into actionable segments such as high spenders, frequent buyers, inactive users, etc.

These segments can be used to guide marketing, promotions, and customer retention efforts

Folder Structure
notebooks/ – Jupyter notebooks for preprocessing, modeling, and evaluation

data/ – Raw and cleaned data files (excluded from repo if large)

plots/ – Visualizations and cluster profile charts

models/ – Serialized clustering models (optional)

Final Notes
This project demonstrates the application of unsupervised learning for customer analytics in a retail environment. It provides a framework for converting raw transaction data into insights that support data-driven business decisions.
