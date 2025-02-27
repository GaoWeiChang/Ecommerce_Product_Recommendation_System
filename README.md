# Ecommerce Product Recommendation System
 
## Overview
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project we will create a recommendation system by using a dataset from a UK-based retailer available at the UCI Machine Learning Repository(https://archive.ics.uci.edu/dataset/352/online+retail). This dataset includes all transactions occurring between 2010 and 2011, providing developing powerful customer segmentation and recommendation systems to enhance marketing strategies.
## Problem 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this project, we aim to transform transactional data into a customer-centric dataset by creating new features that will facilitate the segmentation of customers into distinct groups. This segmentation will allow us to understand the unique profiles and preferences of various customer groups, thus amplifying the efficiency of marketing strategies and fostering increased sales.
## Objectives
- **Data Cleaning & Transformation**: Undertake data cleaning by handling missing values, duplicates, and outliers to prepare the dataset for effective clustering.
- **Feature Engineering**: Develop new features based on the transactional data to create a customer-centric dataset, setting the stage for customer segmentation.
- **Data Preprocessing**: Conduct feature scaling and dimensionality reduction to streamline data, enhancing the efficiency of the clustering process.
- **Customer Segmentation using K-Means Clustering**: Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies.
- **Cluster Analysis & Evaluation**: Analyze and profile each cluster to develop targeted marketing strategies and assess the quality of the clusters formed.
- **Recommendation System**: Develop a system to recommend best-selling products to customers within the same cluster who haven't purchased those products, aiming to enhance sales and marketing effectiveness.
## Dataset Description
| __Variable__ | __Description__ |
|     :---      |       :---      |      
| __InvoiceNo__ | Code representing each unique transaction. If this code starts with the letter 'c', it indicates a cancellation. |
| __StockCode__ | Code uniquely assigned to each distinct product. |
| __Description__ | Description of each product. |
| __Quantity__ | The number of units of a product in a transaction. |
| __InvoiceDate__ | The date and time of the transaction. |
| __UnitPrice__ | The unit price of the product in sterling. |
| __CustomerID__ | Identifier uniquely assigned to each customer. |
| __Country__ | The country of the customer. |
