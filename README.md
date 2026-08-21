# FMCG Distribution Analysis — Python

## Project Overview

This project analyzes product distribution performance across FMCG outlets using Python.

The purpose of the analysis is to understand how effectively products are distributed across targeted outlets and identify products that are performing above or below the distribution target.
The project uses a small sample FMCG dataset containing products, product categories, targeted outlets, and outlets where the product is currently available.
## Business Objective
The main objective is to measure product distribution and identify opportunities for improvement.
The analysis answers questions such as:
* Which products have the highest distribution?
* Which products have the lowest distribution?
* What are the Top 3 performing products?
* What are the Bottom 3 performing products?
* Which products are below the 70% distribution target?
* Which product category has the highest average distribution?
* What is the overall distribution performance
* 
## Key KPI
### Distribution %
Distribution is calculated using:
Distribution % = Outlets With Product / Outlets Targeted × 100
## For example:
If a product is targeted at 500 outlets and is available in 425 outlets:
425 / 500 × 100 = 85%

The product therefore has an **85% distribution**.

## Tools & Technologies
* Python
* Jupyter Notebook
* Pandas
* Seaborn
* Matplotlib

## Python Skills Demonstrated
This project demonstrates the following Python and data-analysis skills:
* Importing libraries
* Creating DataFrames
* Working with columns
* Creating calculated columns
* Mathematical calculations
* Sorting data
* Filtering data
* `head()`
* `groupby()`
* `nlargest()`
* `nsmallest()`
* Data aggregation
* Data visualization
* Business KPI analysis


## Analysis Performed
### 1. Distribution Calculation
A new `Distribution_%` column was created to calculate the percentage of targeted outlets carrying each product.
### 2. Top 3 Products
The three products with the highest distribution were identified.
### 3. Bottom 3 Products
The three products with the lowest distribution were identified.
### 4. Low Distribution Products
Products below the **70% distribution target** were identified for further investigation.
### 5. Category Analysis
Average distribution was calculated for each product category using `groupby()`.
### 6. Overall Distribution
The overall distribution level across the dataset was calculated.

## Data Visualization
Seaborn was used to create a bar chart showing product distribution.
The visualization makes it easier to identify:
* High-performing products
* Low-performing products
* Products below the 70% target
* Distribution gaps between products

## Business Value
## Distribution is an important FMCG sales KPI because strong distribution increases product availability and creates more opportunities for sales.

The analysis can help a sales team identify:
* Products requiring additional distribution
* Distribution gaps
* Underperforming products
* Strong-performing products
* Categories requiring additional sales focus

A sales representative could use this type of analysis to prioritize outlets where products are currently missing.

## Author
**Mario Booysen**
This project was created as part of my Python and data analytics portfolio to demonstrate practical business analysis using FMCG distribution data.
