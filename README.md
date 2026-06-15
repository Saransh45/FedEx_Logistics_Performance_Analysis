# FedEx Logistics Performance Analysis

## Project Type

Exploratory Data Analysis (EDA)

## Contribution

Individual Project

### Team Member

**Saransh Chahar**

---

# Project Summary

This project performs Exploratory Data Analysis (EDA) on a FedEx logistics dataset to understand shipment and delivery performance. The analysis focuses on identifying delivery patterns, shipment delays, transportation costs, vendor performance, and operational trends.

Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, the dataset was cleaned, transformed, and analyzed to uncover meaningful business insights related to shipment modes, freight costs, delivery timelines, and product distribution.

The objective of this project is to identify key factors affecting logistics performance and provide data-driven recommendations that can help improve operational efficiency and customer satisfaction.

---

# GitHub Repository

Repository Link:
https://github.com/Saransh45/fedex-logistics-performance-analysis

---

# Problem Statement

Logistics companies such as FedEx manage thousands of shipments across multiple countries, vendors, and transportation modes. Ensuring timely deliveries while maintaining operational efficiency is critical for customer satisfaction and business success.

However, factors such as shipment delays, high freight costs, inefficient transportation methods, and vendor dependencies can negatively impact logistics performance.

The goal of this project is to analyze FedEx shipment data and identify patterns related to shipment volume, freight costs, delivery timelines, and vendor performance through Exploratory Data Analysis.

---

# Business Objective

The primary business objectives of this analysis are:

* Understand shipment distribution across countries and transportation modes.
* Analyze freight cost patterns and factors influencing transportation expenses.
* Identify top-performing vendors and product groups.
* Examine the relationship between shipment weight and freight cost.
* Detect operational inefficiencies and areas for cost optimization.
* Provide actionable insights to improve logistics planning and decision-making.

---

# Dataset Information

The dataset contains shipment and supply chain information including:

* Shipment Mode
* Country
* Vendor
* Product Group
* Freight Cost (USD)
* Weight (Kilograms)
* Line Item Value
* Delivery Dates
* Manufacturing Site
* Insurance Cost
* Shipment Quantity

Dataset Size:

* Rows: 10,324
* Columns: 33

---

# Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# Data Cleaning & Feature Engineering

The following preprocessing steps were performed:

* Handled missing values in categorical columns using "Unknown".
* Replaced missing numerical values with median values.
* Converted date columns into datetime format.
* Created a new feature called **Delivery Days**.
* Extracted **Year** and **Month** from delivery dates.
* Performed data quality checks for duplicates and inconsistencies.

---

# Key Analysis Performed

### Univariate Analysis

* Shipment Mode Distribution
* Country-wise Shipment Distribution
* Freight Cost Distribution
* Shipment Weight Distribution
* Product Group Analysis

### Bivariate Analysis

* Freight Cost by Shipment Mode
* Weight by Shipment Mode
* Weight vs Freight Cost
* Product Group vs Line Item Value
* Vendor Performance Analysis

### Multivariate Analysis

* Correlation Heatmap
* Pair Plot Analysis
* Country vs Shipment Mode Analysis

---

# Key Insights

### Shipment Mode Analysis

* Air transport is the most frequently used shipment mode.
* Shipment mode selection significantly impacts freight cost.

### Country Analysis

* South Africa, Nigeria, and Côte d'Ivoire account for a large share of shipments.
* Shipment demand is concentrated among a limited number of countries.

### Freight Cost Analysis

* Freight cost distribution is highly right-skewed.
* A small number of shipments contribute disproportionately to transportation expenses.

### Vendor Analysis

* Vendor activity is concentrated among a few major suppliers.
* SCMS from RDC contributes the highest shipment value.

### Weight vs Freight Cost

* Freight cost generally increases with shipment weight.
* Several outliers indicate unusually expensive shipments.

---

# Business Recommendations

1. Optimize shipment modes with consistently high transportation costs.
2. Focus logistics planning on high-volume destination countries.
3. Strengthen relationships with high-performing vendors.
4. Monitor heavy shipments to control freight expenses.
5. Investigate high-cost outlier shipments for operational improvements.
6. Use shipment data to improve cost forecasting and resource allocation.

---

# Conclusion

This analysis provides valuable insights into FedEx logistics operations by identifying key shipment patterns, cost drivers, vendor dependencies, and transportation trends.

The findings can support data-driven decision-making, improve operational efficiency, reduce logistics costs, and enhance customer satisfaction through better shipment planning and execution.

---

## Project Status

Completed

---

### Author

**Saransh Chahar**
