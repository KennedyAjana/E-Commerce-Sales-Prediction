# E-Commerce-Sales-Prediction

## Table of Contents
- [Description](#description)
- [Problem Statement](#problem-statement)
- [Purpose](#purpose)
- [Dataset](#dataset)
- [Target Audience](#target-audience)
- [File Formats](#file-formats)
- [Packages Used](#packages-used)
- [Analysis and Insights](#analysis-and-insights)
  - [Findings](#findings)
  - [Supporting Data](#supporting-data)
- [Conclusion and Recommendations](#conclusion-and-recommendations)
  - [Conclusion](#conclusion)
  - [Recommendations](#recommendations)
- [Author](#author)

---

## Description
The **Ecommerce Sales Prediction** project analyzes sales data across various product categories in an e-commerce setting. The goal is to identify which categories drive the most revenue and provide actionable insights for effective resource distribution based on sales prediction patterns.

---

## Problem Statement
**Key Question:**  
How can resources be distributed across product categories to maximize revenue based on observed sales trends?

---

## Purpose
The project is designed to help management:
1. Understand sales contributions across different product categories.
2. Optimize resource allocation for maximum return on investment.
3. Develop data-driven sales strategies aligned with forecasted sales trends.

---

## Dataset
**Source:** [Kaggle: E-Commerce Sales Prediction Dataset](https://www.kaggle.com/datasets/nevildhinoja/e-commerce-sales-prediction-dataset)  
**File Name:** Ecommerce_Sales_Prediction_Dataset.csv  

The dataset includes:
- **Product_Category**: Type of product (e.g., Electronics, Fashion, etc.)
- **Price**: Average price of products in the category.
- **Marketing_Spend**: Amount spent on marketing.
- **Units_Sold**: Total units sold per category.

---

## Target Audience
This analysis is targeted at **Sales Managers** and **Business Strategists** seeking to optimize resource allocation and enhance sales strategies.

---

## File Formats
- **Data:** CSV  
- **Text Reports:** PDF, HTML  
- **Graphs and Visuals:** JSON  

---

## Packages Used
- **pandas**: For data manipulation and analysis.  
- **matplotlib**: For data visualization.

---

## Analysis and Insights

### Findings
The analysis provided the following insights:
- **Electronics**: The most significant revenue contributor with high average sales and marketing ROI.
- **Fashion**: Strong performance with consistent revenue contributions.
- **Toys**: Lower revenue contributions despite similar pricing structures, indicating underperformance.
- **Sports and Home Decor**: Moderate contributions but potential for growth with targeted strategies.

### Supporting Data
Using `df.groupby('Product_Category').describe()`, we derived:
1. **Electronics**:
   - Highest average sales and marketing spend.
   - Significant variability in units sold.
2. **Fashion**:
   - Moderate variability with stable revenue contributions.
3. **Toys**:
   - Lowest average sales, suggesting the need for strategic intervention.

---

## Conclusion and Recommendations

### Conclusion
- **Top Performers:** Electronics and Fashion drive the highest revenue.
- **Underperformers:** Toys and Home Decor require targeted marketing strategies.

### Recommendations
1. **Increase Marketing Spend:** Allocate additional resources to underperforming categories like Home Decor and Sports to boost sales.
2. **Price Optimization:** Adjust pricing strategies for Toys to increase competitiveness and sales volume.
3. **Dynamic Monitoring:** Implement regular tracking of sales trends to adapt strategies in real-time.

---

## Author
**Kennedy Ajana**  
**Email:** kennedyajana@gmail.com  

This project serves as a foundation for data-driven sales strategy development, focusing on maximizing revenue through optimal resource allocation and category-specific strategies.