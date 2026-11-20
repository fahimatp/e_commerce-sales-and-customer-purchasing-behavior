# E-Commerce Sales and Customer Purchasing Behavior: Online Retail Transaction Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of an Online Retail transactional dataset to understand sales performance, customer purchasing behavior, product performance, and revenue trends.

The dataset contains **541,909 transaction records** with 8 attributes, including Invoice Number, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country.

The analysis aims to identify meaningful business insights that can help improve inventory management, customer retention, marketing strategies, and overall business performance.

## 🎯 Project Objectives

- Understand the structure and characteristics of the dataset.
- Perform data cleaning and preprocessing.
- Identify missing values, duplicate records, and invalid transactions.
- Analyze product sales and revenue patterns.
- Identify top-performing countries and customers.
- Examine monthly sales trends.
- Perform customer segmentation using RFM analysis.
- Generate actionable business insights and recommendations.

## 📂 Dataset Description

The dataset consists of 541,909 records and 8 columns.

| Column | Description |
|---|---|
| InvoiceNo | Unique invoice number |
| StockCode | Product identification code |
| Description | Product description |
| Quantity | Number of items purchased |
| InvoiceDate | Date and time of transaction |
| UnitPrice | Price per unit |
| CustomerID | Unique customer identification |
| Country | Customer's country |

## 🛠️ Tools and Technologies

- **Python** – Programming language
- **Google Colab** – Development environment
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization

## 🧹 Data Cleaning and Preprocessing

The following preprocessing steps were performed:

- Inspected dataset structure, data types, and summary statistics.
- Identified and removed duplicate records.
- Filtered out transactions with non-positive quantities and unit prices.
- Examined missing values.
- Handled missing product descriptions.
- Converted InvoiceDate into datetime format.
- Removed records with missing CustomerID for customer-level analysis.
- Created new features for further analysis.

### Feature Engineering

The following features were created:

- **Total_Revenue:** Quantity × UnitPrice
- **YearMonth:** Extracted year and month from InvoiceDate.
- **DayOfWeek:** Extracted the day of the week.
- **Hour:** Extracted the transaction hour.

## 📊 Exploratory Data Analysis (EDA)

The project includes three major types of analysis.

### 1. Univariate Analysis

- Distribution of item quantities per transaction.
- Unit price distribution and outlier detection.
- Top 10 countries by transaction count.
- Top 10 most frequent customers.

### 2. Bivariate Analysis

- Top 10 revenue-generating products.
- Monthly gross revenue trends.
- Top 10 revenue-generating customers.

### 3. Multivariate Analysis

- Correlation analysis using a heatmap.
- Customer RFM analysis using Recency, Frequency, and Monetary values.

## 🔍 Key Findings

1. Most transactions involve small retail orders, particularly between 1 and 12 units.
2. Most products have unit prices below 10.
3. The United Kingdom accounts for the majority of transactions, followed by Germany, France, and EIRE.
4. Customers 17841 and 14911 have high transaction frequencies.
5. Paper Craft, Little Birdie and Regency Cakestand 3 Tier are among the top revenue-generating products.
6. Monthly revenue shows a significant increase from August 2011, reaching its peak in November 2011.
7. Customer 14646 generates the highest total revenue.
8. RFM analysis indicates that high-monetary customers tend to have lower recency and higher purchase frequency.
9. The correlation between Quantity and Total_Revenue is approximately 0.91.

## 💡 Business Insights and Recommendations

### Sales and Seasonal Trends
Prepare inventory and supply chain operations ahead of the Q4 holiday shopping season to take advantage of increased purchasing demand.

### Inventory Management
Maintain sufficient stock of top revenue-generating products to reduce stockouts and maximize sales opportunities.

### Customer Retention
Introduce loyalty programs, exclusive discounts, and personalized offers for high-frequency and high-value customers.

### Geographic Segmentation
Focus on the United Kingdom while exploring opportunities to expand sales in other international markets.

### Customer Segmentation
Use RFM analysis to identify valuable customers and develop targeted marketing strategies.

## 📈 Conclusion

This project demonstrates how exploratory data analysis can transform raw transactional data into meaningful business insights.

By analyzing sales patterns, customer purchasing behavior, product performance, and revenue trends, the study identifies important opportunities for improving business performance.

The findings can support better decision-making in inventory management, customer relationship management, and sales strategy development.

## ▶️ How to Run the Project

1. Download or clone this GitHub repository.
2. Download the Online Retail dataset (`Online_Retail.csv`).
3. Open the Jupyter Notebook in Google Colab.
4. Upload the dataset to Google Colab.
5. Install the required Python libraries if necessary.
6. Run the notebook cells sequentially to perform data cleaning, analysis, and visualization.

## 📚 Project Type

**Exploratory Data Analysis (EDA) | Data Analytics | Python | Business Intelligence**

---

*This project was developed for learning and portfolio purposes to demonstrate practical data analytics skills.*
