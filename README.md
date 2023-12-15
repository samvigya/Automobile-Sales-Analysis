# Automobile-Sales-Analysis
This project involves customer segmentation, exploratory data analysis (EDA), and visualization to derive insights from the 'Automobile Sales' dataset

# Overview
The primary goal of this project is to understand customer behavior, identify patterns, and segment customers based on Recency, Frequency, and Monetary (RFM) analysis. Additionally, exploratory data analysis and visualizations are employed to gain insights into the dataset.

# Tools and Libraries Used
NumPy and Pandas for data manipulation and analysis.
Matplotlib and Seaborn for data visualization.
Plotly for interactive visualizations.

# Data Description
ORDERNUMBER	This column represents the unique identification number assigned to each order.
QUANTITYORDERED	It indicates the number of items ordered in each order.
PRICEEACH	This column specifies the price of each item in the order.
ORDERLINENUMBER	It represents the line number of each item within an order.
SALES	This column denotes the total sales amount for each order, which is calculated by multiplying the quantity ordered by the price of each item.
ORDERDATE	It denotes the date on which the order was placed.
DAYS_SINCE_LASTORDER	This column represents the number of days that have passed since the last order for each customer. It can be used to analyze customer purchasing patterns.
STATUS	It indicates the status of the order, such as "Shipped," "In Process," "Cancelled," "Disputed," "On Hold," or "Resolved."
PRODUCTLINE	This column specifies the product line categories to which each item belongs.
MSRP	It stands for Manufacturer's Suggested Retail Price and represents the suggested selling price for each item.
PRODUCTCODE	This column represents the unique code assigned to each product.
CUSTOMERNAME	It denotes the name of the customer who placed the order.
PHONE	This column contains the contact phone number for the customer.
ADDRESSLINE1	It represents the first line of the customer's address.
CITY	This column specifies the city where the customer is located.
POSTALCODE	It denotes the postal code or ZIP code associated with the customer's address.
COUNTRY	This column indicates the country where the customer is located.
CONTACTLASTNAME	It represents the last name of the contact person associated with the customer.
CONTACTFIRSTNAME	This column denotes the first name of the contact person associated with the customer.
DEALSIZE	It indicates the size of the deal or order, which are the categories "Small," "Medium," or "Large."

# Exploratory Data Analysis (EDA)
The EDA phase involves:

Data loading and initial inspection.
Checking for missing values.
Handling outliers in sales-related metrics.
Exploring the distribution of key numerical features.
Analyzing sales trends over time.
Visualizing sales across different product lines.
Investigating the distribution of deal sizes.

# Visualizations
Several visualizations have been created to enhance the understanding of the dataset:

Horizontal bar plots for the top 10 customers based on total sales, recency, and frequency.
Funnel chart depicting the distribution of the top 10 countries.
Bar chart illustrating the distribution of deal sizes.
Pie chart showcasing the sales contribution by deal size categories.

# RFM Analysis
RFM analysis involves:

Calculating Recency, Frequency, and Monetary metrics for each customer.
Assigning RFM scores and segments based on quantiles.
Assigning RFM segments such as 'High Value,' 'Mid Value,' and 'Low Value.'
Creating a bar chart for RFM segmentation distribution.


# Usage
Explore the Jupyter notebooks in the notebooks/ directory for detailed analyses and visualizations. The processed dataset with RFM segments is available in Auto Sales data.csv and RFM_Segmentation.csv
