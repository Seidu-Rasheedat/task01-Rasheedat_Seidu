# E-Commerce Data Analysis Project

## Overview

This project presents a comprehensive analysis of an e-commerce dataset through data understanding, data cleaning, and exploratory data analysis (EDA). The objective was to examine the dataset's structure, assess data quality, handle missing values, and uncover meaningful insights into customer purchasing behavior, product performance, sales trends, payment preferences, and order outcomes.

## Project Structure

* **Data Understanding and Cleaning**

  * Dataset inspection and structure assessment
  * Missing value identification and treatment
  * Data quality checks and validation
  * Creation of a cleaned dataset for analysis

* **Exploratory Data Analysis (EDA)**

  * Customer purchasing behavior analysis
  * Product and category performance analysis
  * Sales trend exploration
  * Payment method analysis
  * Order outcome analysis
  * Data visualization and business insights

## Dataset

The dataset contains e-commerce transaction records, including information related to products, customers, payment methods, order status, pricing, and purchasing activity.

## Tools and Libraries

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Outcomes

The analysis revealed important patterns in customer behavior, product demand, sales performance, and order outcomes. Through data cleaning and visualization, the project provides a clearer understanding of the dataset and demonstrates a complete data analysis workflow from raw data to actionable insights.

## EDA Insights

The exploratory data analysis revealed several notable patterns within the e-commerce dataset:

* Product categories, payment methods, and referral sources were relatively balanced, indicating that no single category overwhelmingly dominated customer activity.

* Among all products, **Printers** generated the highest total sales, while **Phones** and **Desks** recorded comparatively lower sales performance.

* Monthly sales and quantity sold exhibited closely related trends, suggesting a strong relationship between sales revenue and purchasing volume.

* Sales performance varied across years, with **2023** displaying greater fluctuations in both sales and quantity sold than **2024**, including a notable peak in **October 2023**.

* Referral channels influenced order outcomes differently. **Instagram** generated the highest number of pending orders, whereas **Email** campaigns resulted in the highest number of delivered orders.

* Payment methods were associated with varying order outcomes. **Online payments** recorded the highest number of delivered orders, while **Credit Card** transactions showed relatively higher cancellation rates.

* Correlation analysis identified a strong positive relationship between **unit price** and **total price**, while relationships involving cart-related variables were comparatively weak.

* Outlier analysis revealed only a small number of unusually high transaction values, indicating that the dataset maintained relatively stable purchasing patterns overall.


## Files Included

* `Data_Understanding_and_cleaning.ipynb`
* `Exploratory_Data_Analysis.ipynb`
* `Cleaned_orders_data.csv`
