# E-Commerce-Sales-Customer-Experience-Delivery-Performance-Analysis
E-commerce data analysis using the Olist dataset. Includes data cleaning, preprocessing, sales and customer analysis, delivery performance, business insights, recommendations, and an interactive Looker Studio dashboard using Python and Pandas.

## Q1 — Dataset Selection
### 1. Dataset Name
 Brazilian E-Commerce Public Dataset by Olist

### 2. Source and URL

Source: Kaggle — Olist
- Olist Brazilian E-Commerce Dataset
- The dataset was provided by Olist and contains anonymized real commercial e-commerce data.

### 3. Number of rows and columns
 The dataset consists of multiple related CSV files, rather than one single table.
| Dataset | Approx. Rows |
|---------|-------------:|
| Orders | 99,441 |
| Customers | 99,441 |
| Order Items | 112,650 |
| Payments | 103,886 |
| Reviews | ~99,000+ |
| Products | 32,951 |
| Sellers | 3,095 |
| Geolocation | 1,000,163 |
This multi-table structure is particularly useful for demonstrating data joining and relational analysis.

### 4. Brief Description
 The dataset contains anonymized e-commerce transactions from Olist, a Brazilian online marketplace. It covers approximately 100,000 orders made between 2016 and 2018 and contains information about orders, customers, products, sellers, payments, reviews and logistics.

### 5. Why I selected this dataset?
 I selected this dataset because it contains a large volume of real-world commercial data and multiple related tables. It allows analysis across sales, customers, products, payments, delivery performance and customer satisfaction. The dataset is sufficiently complex to demonstrate data cleaning, joining, feature engineering, exploratory analysis and business-oriented visualization.

### 6. Business opportunities/problems
The dataset can help investigate:
Sales and revenue trends
Product/category performance
Customer purchasing behavior
Regional performance
Delivery delays
Customer satisfaction
Payment behavior
Seller performance
Repeat-customer behavior
Opportunities to improve customer experience

# Q2 — Business Problem
## A. Business Problem :How can an e-commerce company improve revenue and customer satisfaction by understanding product performance, customer behavior and delivery performance?
The analysis will focus on identifying areas where management can improve sales while reducing operational problems such as late deliveries and poor customer experiences.

## B. Five Questions
### Question 1 Which product categories generate the highest sales and revenue?
### Question 2 Which customer regions contribute the most revenue and orders?
### Question 3 How does delivery performance affect customer review scores?
### Question 4 What are the major sales trends over time?
### Question 5 Which customer/product/seller segments represent the greatest opportunity for improvement?

## Hypotheses
### H1
-Late deliveries are associated with lower customer satisfaction.
-We will compare review scores between on-time and late deliveries.
-This is particularly promising because existing analysis of this dataset reports average review scores of approximately 4.29 for on-time deliveries and 2.57 for late deliveries.

### H2
-Sales are concentrated among a relatively small number of product categories and geographic regions.
-We will test this using revenue/order contribution by category and state.

