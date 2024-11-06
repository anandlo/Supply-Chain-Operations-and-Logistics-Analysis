# Supply Chain Operations and Logistics Analysis

This project conducts a thorough analysis of supply chain data to explore various aspects, including sales performance, customer demographics, stock levels, manufacturing processes, defect rates, and shipping efficiency. Using Python for data analysis and visualization, this project provides insights into optimizing inventory, improving logistics, and reducing costs.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Sales Analysis](#sales-analysis)
  - [Customer Demographics](#customer-demographics)
  - [Stock and Availability](#stock-and-availability)
  - [Operations Analysis](#operations-analysis)
  - [Shipping Analysis](#shipping-analysis)
- [Results](#results)
- [License](#license)

## Overview
Effective supply chain management is crucial for reducing costs, meeting demand, and maintaining efficient production and delivery systems. This project leverages a structured dataset to analyze product sales, customer demographics, stock and inventory, operational efficiency, and shipping logistics.

## Dataset
The dataset consists of 100 records with 24 attributes, covering various aspects of supply chain management, including:
- **Product Type**: Category of products (e.g., skincare, haircare, cosmetics).
- **SKU**: Unique identifier for each product.
- **Price**: Price of each product.
- **Availability**: Availability levels.
- **Stock Levels**: Quantity of stock available.
- **Lead Times**: Time taken to restock products.
- **Manufacturing Costs**: Cost incurred during production.
- **Shipping Costs**: Costs associated with shipping methods and carriers.
- **Defect Rates**: Quality check metric for products.

## Data Preparation and Cleaning
1. **Data Loading**: Load the dataset using `pandas`.
2. **Data Overview**: Display data structure and column information to understand available attributes.
3. **Missing Values and Duplicates**: Check for missing and duplicate values, and handle them as necessary.
4. **Data Types and Descriptive Statistics**: Review column data types and generate summary statistics.

## Exploratory Data Analysis

### Sales Analysis
- **Objective**: Assess product performance by analyzing the number of units sold and revenue generated.
- **Insights**: Skincare products are the top-selling category, contributing the highest percentage of sales and revenue.
- **Visualizations**: 
  - Pie chart showing sales distribution by product type.
  - Bar chart comparing units sold to revenue generated for each product type.

### Customer Demographics
- **Objective**: Identify customer purchasing patterns by demographic group.
- **Insights**: Female and non-binary customers predominantly purchase skincare and cosmetics.
- **Visualization**: Stacked bar chart showing units sold per product type across different demographics.

### Stock and Availability
- **Objective**: Track stock levels and product availability for effective inventory management.
- **Insights**: Skincare products have a faster turnover with higher availability and lower stock levels, while cosmetics have higher stock but lower availability.
- **Visualizations**: 
  - Stacked bar chart illustrating stock levels vs. availability for each product type.

### Operations Analysis
- **Objective**: Analyze lead times, production volumes, and manufacturing costs to optimize production efficiency.
- **Insights**: Skincare products have the longest lead times and highest production volumes, indicating higher demand and complexity in manufacturing.
- **Visualization**: Bar chart comparing manufacturing lead times and costs for each product type.

### Shipping Analysis
- **Objective**: Optimize logistics by examining transportation modes, shipping routes, and carrier costs.
- **Insights**: Carrier B is the most cost-effective and efficient option across transportation modes, though it also incurs the highest overall costs due to high usage.
- **Visualizations**: 
  - Pie chart for cost distribution by shipping carrier.
  - Bar chart comparing shipping times by carrier and transportation mode.

## Results
- **Product Sales**: Skincare leads in both sales volume and revenue.
- **Demographics**: Key customer segments (female and non-binary) show a preference for skincare and cosmetics.
- **Stock and Availability**: Stock levels indicate efficient inventory turnover for skincare, while cosmetics and haircare products maintain higher stock.
- **Operations Efficiency**: Longer lead times and higher manufacturing costs for skincare imply complexity in production and high demand.
- **Shipping Costs and Efficiency**: Carrier B, especially in air and road modes, is the preferred option for efficient shipping, balancing both speed and cost.

## License
This project is licensed under the MIT License.
