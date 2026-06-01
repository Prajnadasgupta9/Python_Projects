# Python_Projects

# Exploratory Data Analysis on Sales Data using Python

## Overview

This project performs Exploratory Data Analysis (EDA) on a sales dataset containing over 186,000 transactions from an electronics store in the USA. The analysis focuses on uncovering customer purchasing behavior, sales trends, seasonal patterns, city-wise performance, and product demand insights using Python.

The project includes:

* Data Cleaning & Transformation
* Feature Engineering
* Time-based Analysis
* Product Analysis
* City-wise Sales Analysis
* Seasonal Trends
* Data Visualization using Matplotlib & Seaborn


---

## Objectives

The main objectives of this project are:

* Clean and preprocess raw sales data
* Perform exploratory data analysis
* Identify top-performing products and cities
* Analyze customer purchase behavior
* Discover seasonal and hourly sales trends
* Visualize insights using charts and plots

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Dataset Features

| Column Name      | Description             |
| ---------------- | ----------------------- |
| Order ID         | Unique order identifier |
| Product          | Product purchased       |
| Quantity Ordered | Number of units ordered |
| Price Each       | Price per unit          |
| Order Date       | Date & time of purchase |
| Purchase Address | Customer address        |

---

## Data Cleaning & Feature Engineering

The following preprocessing steps were performed:

* Removed missing/null values
* Removed duplicate records
* Converted object data types into numeric types
* Converted Order Date into datetime format
* Extracted:

  * Day
  * Month
  * Year
  * Hour
  * Time
* Extracted:

  * City
  * PIN Code
* Rounded product prices
* Created Product Categories
* Label Encoded Product Names

---

## Exploratory Data Analysis Performed

### Sales Analysis

* Best month for sales
* Highest revenue-generating city
* Hourly purchase trends
* Seasonal sales analysis

### Product Analysis

* Most sold products
* Least sold products
* Most expensive headphones
* Wired vs Wireless headphone preference
* Bulk order analysis

### Time-Based Analysis

* Peak purchasing hours
* Month-wise dataframes
* Year-wise comparisons

---

## Key Insights Uncovered

### Best Month for Sales

* December recorded the highest sales revenue.

### Best Performing City

* San Francisco generated the highest number of sales.

### Customer Purchase Timing

* Most purchases occurred during evening hours.

### Product Trends

* Charging cables and headphones were among the most frequently purchased products.

### Seasonal Trends

* Different products showed higher demand in different seasons.

### Bulk Orders

* Wired Headphones were frequently ordered in larger quantities.

### Expensive Products

* Apple Airpods Headphones were identified as the most expensive headphone product.

---


# Recommendations

## Marketing Strategy

* Focus advertising campaigns during December and evening hours to target peak customer purchasing periods.

## City-Specific Promotions

* Develop targeted marketing strategies for San Francisco, as it generated the highest sales among all cities.

## Seasonal Inventory Planning

* Adjust inventory levels and promotional campaigns based on seasonal product demand trends to maximize revenue.

## Product Pricing Optimization

* Reevaluate pricing strategies for low-performing products such as the LG Washing Machine to improve sales performance.

## Product Bundling Opportunities

* Promote commonly bulk-ordered products like Wired Headphones and charging cables through bundle offers and discounts.

## Customer Behavior Insights

* Use hourly and seasonal purchasing patterns to optimize promotional timing and improve customer engagement.

----



## Visualizations Created

The project includes various visualizations such as:

* Bar Charts
* Histograms
* Distribution Plots
* KDE Plots
* Seasonal Sales Charts
* City-wise Sales Charts
* Product Frequency Charts

---

## Sample Visualizations

Examples include:

* Sales by City
* Distribution of Purchases by Hour
* Product Category Analysis
* Seasonal Sales Trends

---


## Learning Outcomes

Through this project, the following concepts were practiced:

* Data Cleaning
* Pandas Operations
* GroupBy Analysis
* Feature Engineering
* Data Visualization
* Exploratory Data Analysis
* Business Insight Generation


