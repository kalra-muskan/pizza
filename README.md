# Pizza Sales 
This is an Exploratory Data Analysis on the sales data of a fictional Pizza Outlet. The analysis has been done on the sales data composed of *48621 Entries* containing data of a total of *21350 orders*. The data was collected by tracking down the customers' orders for the period of a year starting from *January 2015* to *December 2015*. 

*Aim:* The project aims to provide insights into the business performance and customer behavior of the pizza chain, and to identify key trends and opportunities for improvement. ![introduction](https://github.com/kalra-muskan/pizza/assets/142618498/f2be37b1-4f50-437e-9b1d-98e4e415d832)

## Features

The project offers the following features:

- KPIs: The project calculates the following key performance indicators for the pizza sales data:
    - *Total Revenue*: The sum of the total price of all pizza orders.
    - *Average Order Value*: The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
    - *Total Pizzas Sold*: The sum of the quantities of all pizzas sold. 
    - *Total Orders*: The total number of orders placed. 
    - *Average Pizzas Per Order*: The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.
- Charts: The project creates various charts and graphs to visualize the pizza sales data, such as:
    - *Daily Trend for Total Orders*: A bar chart that displays the daily trend of total orders over a specific time period. This chart helps to identify any patterns or fluctuations in order volumes on a daily basis. 
    - *Monthly Trend for Total Orders*: A line chart that illustrates the hourly trend of total orders throughout the day. This chart allows to identify peak hours or periods of high order activity. 
    - *Percentage of Sales by Pizza Category*: A pie chart that shows the distribution of sales across different pizza categories. This chart provides insights into the popularity of various pizza categories and their contribution to overall sales.
    - *Percentage of Sales by Pizza Size*: A pie chart that represents the percentage of sales attributed to different pizza sizes. This chart helps to understand customer preferences for pizza sizes and their impact on sales. 
    - *Total Pizzas Sold by Pizza Category*: A funnel chart that presents the total number of pizzas sold for each pizza category. This chart allows to compare the sales performance of different pizza categories. 
    - *Top 5 Best Sellers by Revenue, Total Quantity and Total Orders*: A bar chart highlighting the top 5 best-selling pizzas based on the Revenue, Total Quantity, Total Orders. This chart helps to identify the most popular pizza options.
    - *Bottom 5 Sellers by Revenue, Total Quantity and Total Orders*: A bar chart highlighting the bottom 5 worst-selling pizzas based on the Revenue, Total Quantity, Total Orders. This chart helps to identify the underperforming or less popular pizza options.

## Data

The data used for this project is a synthetic dataset that simulates the pizza sales data of a fictional pizza chain. The dataset contains 21350 rows and 9 columns, with information such as order date, order time, pizza category, pizza size, quantity, unit price, total price, etc. The dataset was obtained from Kaggle⁴.

## Data Cleaning & Analysis

The data cleaning process involved the following steps:

- Checking for any missing, duplicate, or invalid values in the data and fixing them accordingly.
- Converting the data types of some columns, such as order date and order time, to the appropriate formats.
- Adding some calculated columns, such as order month, order hour, and order weekday, to facilitate the analysis and visualization.
- Creating a pivot table to summarize the data by different dimensions and measures.

The data cleaning was done using Excel.
The data analysis was done using SQL at Cloud platform- Big Query.

## Data Visualization

The data visualization was done using Google Looker Studio, a business intelligence tool that allows creating interactive dashboards and reports. The dashboard consists of several pages, each focusing on a different aspect of the data analysis. The dashboard also allows filtering and slicing the data by various criteria, such as pizza category, pizza size, order month, order hour, etc.

## Tools Used

The analysis is done using the following tools:

- Excel 2016
- Google Looker Studio
- SQL(Big Query Cloud Service)


## Analysis & Visualization
*__A.	KPI’s__*

* __Total Revenue:__ The sum of the total price of all pizza orders. 

![image](https://github.com/kalra-muskan/pizza/assets/142618498/583b8f42-318a-4670-81fd-b124ebb7f4c4)

* __Average Order Value:__ The average amount spent per order, calculated by dividing the total revenue by the total number of orders.

![image](https://github.com/kalra-muskan/pizza/assets/142618498/ec0e8033-674f-411b-904a-6b60fc0c9da0)

* __Total Pizza Sold:__ The sum of the quantities of all pizzas sold. 

![image](https://github.com/kalra-muskan/pizza/assets/142618498/f43812f0-a2b7-4cc9-a63c-7a4ec618515b)

* __Total Orders:__ The total number of orders placed. 

![image](https://github.com/kalra-muskan/pizza/assets/142618498/2a9b6677-38eb-4443-bf02-4d06935766fa)

* Average Pizzas Per Order: The average number of pizzas sold per order, is calculated by dividing the total number of pizzas sold by the total number of orders.

![image](https://github.com/kalra-muskan/pizza/assets/142618498/c3923fd6-aa3a-4ac4-b78f-055593117a15)

*__B. Stats__*

* __Daily Trends for Total Orders:__ Daily trend of total orders over a specific time period by identifying any patterns or fluctuations in order volumes on a daily basis.

![daily-trend](https://github.com/kalra-muskan/pizza/assets/142618498/a0217587-1b45-40f8-a32d-f801b3a7dbbe)

* __Monthly Trends for Total Orders:__ Illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high-order activity. 

![monthly-trends](https://github.com/kalra-muskan/pizza/assets/142618498/d6437dfa-7717-4348-9946-918893011b27)

* __Percentage of Sales by Pizza Category:__ Distribution of sales across different pizza categories. the popularity of various pizza categories and their contribution to overall sales.

![Sales-by-category](https://github.com/kalra-muskan/pizza/assets/142618498/422722cd-3d29-4565-90a5-a52baaaf5fcc)

* __Percentage Sales By Pizza Size:__ The percentage of sales attributed to different pizza sizes helps us understand customer preferences for pizza sizes and their impact on sales. 

![sale-by-size](https://github.com/kalra-muskan/pizza/assets/142618498/39e5f38e-9d5a-4712-bcf8-0880604995e5)

* __Top 5 Best Sellers by Revenue, Total Quantity, Total Orders:__ The top 5 best-selling pizzas based on the Revenue, Total Quantity, Total Orders. This will help us identify the most popular pizza options.

![top5](https://github.com/kalra-muskan/pizza/assets/142618498/7a27d9f8-9af0-4727-bc9e-a3e7764a0604)

* __Bottom 5 Best Sellers by Revenue, Total Quantity, Total Orders:__ The bottom 5 worst-selling pizzas based on the Revenue, Total Quantity, Total Orders. This will help us identify the underperforming or less popular pizza options.

![bottom5](https://github.com/kalra-muskan/pizza/assets/142618498/f8afe029-3322-48a4-beb0-0e2555470696)


### For a better understanding of these insights,
You can find the interactive Dashboard [Here](https://lookerstudio.google.com/u/1/reporting/cc2f4eaa-0417-4e31-a989-e996e701e237/page/lZQaD)




