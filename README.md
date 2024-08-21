# Automobile Sales Analysis Visualization EDA

This project performs a comprehensive exploratory data analysis (EDA) on a dataset of automobile sales. The analysis includes univariate, bivariate, and multivariate visualizations, revealing key insights into sales patterns, customer behavior, and product performance.

## About the Data

The dataset contains **2747 entries** with **20 columns**. Key characteristics include:

- **Order Details**: Sales transaction details, including order numbers and dates.
- **Customer Information**: Details about the customers placing the orders.
- **Product Details**: Information about the products sold, including product lines and categories.
- **Order Status**: The current status of each order.
- **Recency Information**: How recently the orders were placed.

**Note**: The dataset is free of missing values, and all columns have non-null values.

## Handling Missing and Duplicate Values

- **Missing Values**: Since no missing values were present in the dataset, no imputation or removal was necessary.
- **Duplicate Values**: The dataset was checked for duplicate records, and no duplicates were found.

## Univariate Analysis

### Numerical Features

- **Sales Amount**: The average sales amount per transaction is approximately \$3,553, with a range from \$482.13 to \$14,082.80.
- **Quantity Ordered**: Customers order an average of 35 items per transaction, with a minimum of 6 and a maximum of 97 items.
- **Price Each**: The average price per item was analyzed to understand pricing patterns.

### Categorical Features

- **Product Line**: Distribution across different product lines was examined to identify which product lines contribute the most to sales.
- **Order Status**: The status of orders was analyzed to understand the completion and cancellation rates.

## Bivariate Analysis

- **Sales Amount vs. Quantity Ordered**: A positive correlation was observed between the number of items ordered and the total sales amount.
- **Country vs. Sales**: The United States leads in sales, followed by Spain and France. Significant contributions were also noted from Australia and Singapore.
- **City vs. Sales**: Madrid tops the sales among cities, with significant contributions from San Diego and New York City.

## Multivariate Analysis

- **Product Line vs. Sales Trends over Time**: The analysis revealed seasonal trends, with peak sales occurring in October and November each year.
- **Country vs. Product Line vs. Sales**: A multivariate analysis across country, product line, and sales highlighted the importance of classic car parts, which generate approximately 40% of revenue.

## Key Insights

1. **Sales Overview**:
   - **298 orders** were placed by **89 customers** from **19 countries** over the last **2.5 years**.
   - **United States** is the leading country in sales, followed by **Spain** and **France**.
   - **Madrid** is the top city for sales, with notable sales from **San Diego** and **New York City**.

2. **Product and Revenue**:
   - The company manufactures **109 automobile parts** across **7 product lines**.
   - **Classic Car parts** account for the majority of sales, contributing to **40%** of the revenue.

3. **Sales Trends**:
   - Sales show an upward trend with **monthly seasonality**.
   - Peak sales occur in **October and November** each year.
   - A significant sales increase was observed in the **US** and **France** in **2019**.

4. **Customer Retention**:
   - **No new customers** have been added since **September 2019**.
   - Despite this, a good **customer retention rate of approximately 90%** was observed in **2019**.

5. **Key Customers**:
   - **Euro Shopping Channel** and **Mini Gifts Distribution Ltd.** are the best customers, characterized by high spending, frequency, and recency of orders.

## Conclusion

This analysis provides a clear view of the sales landscape, customer behavior, and product performance in the automobile sector. By identifying key trends and insights, businesses can make informed decisions to optimize their sales strategies. Continuous monitoring and analysis are essential for sustaining growth in a competitive market.

Created by Azarudeen, happy learning!

