# Pizza_Sales_Analysis
End-to-End Retail Sales Data Analytics Project using Python

## Project Overview
This project performs an end-to-end data analysis of pizza sales data to uncover business insights related to revenue trends, product performance, and customer preferences.

### Business Problem

A pizza retail company wants to:

-Identify high-performing pizza categories and sizes

-Understand revenue distribution patterns

-Optimize ingredient usage and inventory

-Detect low-performing segments

The analysis answers these questions using Python-based data analytics techniques.


### Tools & Technologies

-Python

-Pandas (Data Manipulation)

-NumPy (Numerical Computation)

-Matplotlib & Seaborn (Visualization)

-Jupyter Notebook

### Project Workflow

#### 1.Data Cleaning & Preparation

-Converted date/time columns

-Removed duplicate records

-Standardized ingredient formatting

-Created derived metrics (Total Revenue, Order Counts)

#### 2.Key Metrics Computed

-Total Revenue

-Total Orders

-Total Quantity Sold

-Revenue Contribution by Category

-Revenue Contribution by Size

#### 3.Pivot Table Revenue Analysis

Created a pivot table to evaluate revenue contribution across:

-Pizza Category

-Pizza Size

-A heatmap visualization highlights high-performing combinations and revenue concentration areas.

#### 4.Ingredient Frequency Analysis

-Used:

.str.split()

.explode()

.value_counts()

-To identify:

Most frequently used ingredients

Potential inventory optimization opportunitie

### Key Insights

-Large-sized pizzas contribute the highest percentage of total revenue.

-The Classic category generates a significant revenue share.

-Cheese dominates ingredient usage, appearing in the majority of orders.

-Certain size-category combinations disproportionately drive sales.

### Business Recommendations

-Focus promotional efforts on high-margin size-category combinations.

-Re-evaluate pricing for low-performing segments.

-Optimize procurement strategy for high-frequency ingredients.

-Consider introducing premium variations in top-performing categories.

### Results with Quantitative Metrics

#### Overall Performance

-Total Revenue Generated: $817,860.05

-Total Orders Processed: 21,350

-Total Pizzas Sold: 49,574

-Average Revenue per Order: $38.31

-Average Pizzas per Order: 2.32

#### Revenue Contribution by Pizza Size

-Large Size: 45.8% of total revenue

-Medium Size: 30.5% of total revenue

-Small Size: 21.8% of total revenue

-Extra Large: 1.7% of total revenue

#### Revenue Contribution by Category

-Classic: 26.8% of total revenue

-Supreme: 25.4% of total revenue

-Chicken: 24% of total revenue 

-Veggie:23.7 % of total revenue

#### Top Performing Category–Size Combination

-Large Classic Pizzas: 9.1% of total revenue

-Generated :$2,20053.1 in revenue

#### Ingredient Usage Analysis

-Most Used Ingredient: Garlic

-Second Most Used: Tomato

-Least Used Ingredient: Capocollo
