# Diwali Sales Analysis

## Project Overview

This project aims to analyze sales data from Diwali, one of the biggest shopping festivals. Using Python, we explore various aspects of the sales data, including customer demographics, purchasing patterns, product performance, and overall sales trends. The insights derived from this analysis can help businesses optimize their strategies for future sales events.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Data Preprocessing](#data-preprocessing)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [License](#license)

## Dataset

The dataset used in this project contains transactional data from Diwali sales. It includes the following columns:
- **User_ID**: Unique identifier for each customer.
- **Cust_name**: Name of the customer.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Gender of the customer.
- **Age Group**: Age group of the customer.
- **Age**: Exact age of the customer.
- **Marital_Status**: Marital status of the customer.
- **State**: State where the transaction took place.
- **Zone**: Geographic zone of the transaction.
- **Occupation**: Occupation of the customer.
- **Product_Category**: Category of the product purchased.
- **Orders**: Number of orders placed by the customer.
- **Amount**: Total amount spent by the customer.
- **Status**: Status of the transaction (e.g., Completed, Pending).
- **unnamed1**: Miscellaneous or unnamed data.

## Requirements

- Python 3.8 or higher
- Jupyter Notebook or any Python IDE
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

You can install the required libraries using:
```bash
pip install -r requirements.txt
```


## Data Preprocessing

In the `Sales_Analysis.ipynb` notebook, we clean and prepare the dataset for analysis. This includes:
- Handling missing values
- Converting data types
- Dropping irrelevant columns (e.g., `unnamed1`)
- Feature engineering (e.g., creating new columns like total spend)

## Analysis

The `Sales_Analysis.ipynb` notebook covers the following:
- **Customer Demographics Analysis**: Gender, age group, marital status, and geographic distribution.
- **Purchasing Patterns**: Frequency of purchases, average spend, and top-selling categories.
- **Product Performance**: Best and worst-performing products.
- **Sales Trends**: Time-based analysis to identify peak sales periods.
- **Occupation-Based Analysis**: Understanding the purchasing power of different occupational groups.



## Conclusion

Married women age group 26-35 yrs from UP, Maharastra and Karnataka working in IT, Healthcare and Aviation are more likely to buy products from Food, Clothing and Electronics category

