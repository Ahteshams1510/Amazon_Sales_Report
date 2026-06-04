# Amazon Sales Analysis using Python

## Project Overview

This project analyzes Amazon sales data to uncover business insights, customer purchasing behavior, product performance, and regional sales trends using Python and data visualization techniques.

The analysis includes data cleaning, preprocessing, exploratory data analysis (EDA), and visualization to help understand key sales patterns and support data-driven decision-making.

---

## Objectives

- Clean and preprocess raw sales data
- Handle missing values and incorrect data types
- Perform Exploratory Data Analysis (EDA)
- Analyze customer buying behavior
- Identify top-selling product sizes and categories
- Analyze courier and order status
- Study B2B vs Retail customer distribution
- Identify top-performing states and cities
- Generate actionable business insights

---

## Dataset Information

The dataset contains Amazon sales transaction records with information such as:

- Order ID
- Date
- Product Category
- Size
- Quantity
- Courier Status
- Order Status
- State
- City
- Postal Code
- B2B Indicator

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning Performed

### Missing Value Treatment
- Identified null values
- Removed unnecessary missing records

### Data Type Conversion
- Converted Postal Code to Integer
- Converted Date column to Datetime format

### Column Optimization
- Removed unwanted columns
- Renamed columns where necessary

---

## Exploratory Data Analysis (EDA)

### Size Analysis
- Analyzed customer preferences based on product size
- Identified the most purchased sizes

### Quantity Analysis
- Used GroupBy operations to calculate total quantity sold by size

### Courier Status Analysis
- Examined order delivery performance
- Compared courier status with order status

### Category Analysis
- Visualized product category distribution

### Customer Type Analysis
- Compared B2B and Retail customers using pie charts

### State-wise Sales Analysis
- Identified top-performing states
- Analyzed customer distribution across regions

### City-wise Analysis
- Evaluated sales concentration in major cities

---

## Key Insights

### Customer Preferences
- M Size products received the highest demand.

### Customer Segment
- Approximately 99% of buyers were retail customers.
- B2B customers represented a very small percentage of total sales.

### Regional Performance
- Maharashtra emerged as one of the top-performing states in terms of customer orders.

### Sales Trends
- Customer purchases were concentrated in a few major states and cities.
