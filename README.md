# E-commerce
An e-commerce platform that provides a seamless online shopping experience, featuring user-friendly navigation, secure transactions, and comprehensive product management.
## Project over view
In the dynamic world of e-commerce, data-driven insights are key to staying competitive. Our Power BI project provides an in-depth analysis of the O-List store's performance, offering valuable insights into sales trends, customer behavior, and product performance.

With interactive dashboards and detailed visualizations, we can track key metrics such as total sales, product-wise performance, and customer demographics. These insights enable us to optimize inventory, enhance customer experience, and drive strategic growth.
#### 1. In this project scenario, I have been asked to create a dashboard for Olist, an e-commerce website. The stakeholder wants to know the insight of specific KPIs and any other valuable insights to share on the dashboard. The KPIs to show are given in the image below:

![Screenshot 2024-05-30 175719](https://github.com/Paila-Lalit/E-commerce/assets/160754393/2ac5fc9b-8fdc-4c1b-a7da-d52c56d6217e)

### 2. Dataset
1.Domain:ecommerce 

2.Project Name: Olist store Analysis

3.Dataset Name:Total 9 Files

4.Data Type:CSV Data

5.Data set zip Folder Size: 45 MB


### 3. Data Cleaning
I cleaned the data in Excel before importing it to PowerBI, I explored the data to find any inconsistencies, duplicates, incorrect format, or missing values. I’ll share some of the inconsistencies and incorrect format I found and how I corrected them, for example in the customer dataset city names were in lower case I used the proper formula and with the help of the helper column I replaced the values. Then in the geolocation dataset, geolocation_city column names are in incorrect format and have special characters e.g £ and Ã , to check all the inconsistencies I used spell check and filter features. characters replaced:
*,-, 4o. 4Âº ¡ © Â ³ “§ replaced with s” ¢ ª º.

![image](https://github.com/Paila-Lalit/E-commerce/assets/160754393/d0e6a982-765b-482c-aacc-f8ced1694fe1)

In the product dataset, there was some empty product category name, and each product id is unique hence I removed those blank rows. In this way, I cleaned the dataset and then imported the files into PowerBI.
### 4. Transforming
After importing all the files, I created some extra columns while referencing the order purchase timestamp column to get insight into the day, month, and year of order like day of week, weekend/weekday in the order dataset.

![image](https://github.com/Paila-Lalit/E-commerce/assets/160754393/0be0fdd6-91c0-4f86-a06d-3edd85462e86)

### 5. Data Modelling 
![Joins](https://github.com/Paila-Lalit/E-commerce/assets/160754393/1c586e9f-3d75-4dce-9077-333d45b05f3b)

# Insights

## Weekday Vs Weekend Payment Statistics:

The Analysis of Payment Will give you an Idea of understanding of buying behaviour of Customer. Here Majority of sales occurs on Weekdays which is 77% and Weekends accounts for the remaining 22% . here overall donut chart shows that weekdays are the most important time to focus on sales.

## Average Shipping days for Petshop Category :

The average shipping days Time for Petshop Category takes 11 days for Shipping, these chart helps to identify areas where they can improve their delivery time and maintain customer satisfaction and meet the expectations of their customers.

## Review scores and Payment Type:

Here the visual shows the distribution of orders by payment types. the most Used Payment type is Credit card 74% of orders, debit card is 2nd Payment type and boleto , vouchers are the least used Payment types This analysis helps in understanding How customer Satisfaction and their payment preferences use this information to identify satisfied customers and encourage them to make repeat purchases. 

## Average Price and Average payment Value of Sao Paulo City:

average price and average payment value both are higher in the city of sao paulo than other cities this suggests that the cost of Living is high in sao paulo city.

## Average shipping days vs Review Scores :

The average shipping days for products with a review of 1,2 stars are higher than the average shipping days for products with reviews of , 3, 4, and 5 stars.
This Analysis suggests that customers who receive their products late are more likely to leave negative reviews.

## Year Wise Sales:

Sales have been increasing steadily each year bcoz of the global economy is growing, *more people using digital payments, 

![Screenshot 2024-06-03 181649](https://github.com/Paila-Lalit/E-commerce/assets/160754393/595959f4-f761-46a0-a436-1c4dc30ffada)
