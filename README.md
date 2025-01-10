# Insights_from_Failed_Orders

# Overview
This project aims to analyze failed orders to uncover underlying patterns and actionable insights. By leveraging data analysis and visualization techniques, the project identifies key factors contributing to order failures and proposes solutions to minimize them in the future.when the client clicks the Order button in the application, the matching system searches for the most relevant drivers and offers them the order. In this project, we would like to investigate some matching metrics for orders that did not completed successfully, i.e., the customer didn't end up getting a car.


# Objective

- Build up distribution of orders according to reasons for failure: cancellations before and after driver assignment, and reasons for order rejection. Analyse the resulting plot. Finding the category that has the highest number of orders.
- Plot the distribution of failed orders by hours. Looking for a trend that certain hours have an abnormally high proportion of one category or another. What hours are the biggest fails.
- Plot the average time to cancellation with and without driver, by the hour. If there are any outliers in the data, it would be better to remove them. Draw any conclusions from this plot.
- Plot the distribution of average ETA by hours.

# Dataset
We have two data sets: data_orders and data_offers, both being stored in a CSV format. The data_orders data set contains the following columns:

order_datetime - time of the order
origin_longitude - longitude of the order
origin_latitude - latitude of the order
m_order_eta - time before order arrival
order_gk - order number
order_status_key - status, an enumeration consisting of the following mapping:
4 - cancelled by client,
9 - cancelled by system, i.e., a reject
is_driver_assigned_key - whether a driver has been assigned
cancellation_time_in_seconds - how many seconds passed before cancellation

The data_offers data set is a simple map with 2 columns:

order_gk - order number, associated with the same column from the orders data set
offer_id - ID of an offer

# Tools and Libraries

Python, Jupyter Notebook, NumPy, Pandas, Scikitlearn.

# Methodology
1. Data Loading and Exploration

  Import necessary libraries.
  Load the dataset and examine its structure, dimensions, and summary statistics.

2. Exploratory Data Analysis (EDA)

  Visualize failure trends over time, by region, or by product category.
  Analyze correlations between key features and failure rates.
  Use heatmaps, bar charts, and scatter plots to identify patterns.

3. Feature Engineering

  Create new features (e.g., delivery time, order size) to enhance analysis.
  Handle missing or inconsistent data through imputation or removal.

4. Insights Extraction

  Analyze key factors causing failed orders, such as:
  Payment issues
  Inventory shortages
  Delivery delays
  Customer-related issues

5. Recommendations

  Provide data-backed solutions to reduce the frequency of order failures.

# Conclusion
This project identified critical areas for improvement in the order processing workflow, providing actionable insights to enhance customer satisfaction and reduce operational losses.

# Future Work
Integrate real-time monitoring of failed orders to act proactively.
Use predictive modeling to forecast potential order failures.
Expand analysis to include successful orders for a comparative study.

## Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanjay-karnati/)

---
