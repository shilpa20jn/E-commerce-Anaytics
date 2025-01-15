

# Olist-E-commerce-data-Analysis

## Introduction

I developed a comprehensive project in Excel, Power BI ,My SQL and Tableau creating multiple dashboards and tables to analyze the data using Olist store E-commerce dataset. This process involved several stages, including data preprocessing, data cleaning, and data visualization.


## Project Overview

Olist is a Brazilian e-commerce platform that connects small and medium-sized businesses with major online market places.
 By Providing a comprehensive suite of tools and services, Olist is a prominent e-commerce platform founded in 2015,based in Brazil.

It is the process to help shopkeepers and customers manage selling process smoothly.
Olist Store Analysis allows to view orders from multiple dimensions like order status,payment,product price, product attributes, freight price, customer location, review score given by customers, etc.

## Datasets
The Olist dataset comprises nine separate datasets, all of which are stored in CSV format:

1.olist_order_items_dataset                    
2.olist_orders_dataset  
3.olist_order_payments_dataset  
4.olist_order_reviews_dataset  
5.olist_products_dataset  
6.olist_customers_dataset  
7.olist_sellers_dataset  
8.olist_geolocation_dataset  
9.olist_category_dataset

## Challenges faced 
#### Data Quality and Cleaning : 

 The Dataset may contain inconsistencies such as duplicate entries, missing values, or incorrect data types, which require thorough cleaning.  

Combining data from different sources(e.g.,sales,customer reviews,product information) can be complex and time-consuming. 

 #### Handling Large volumes of Data :
           
  Analysing large datasets can lead to performance bottlenecks, especially when using tools that are not optimized for big data.

Efficiently storing and processing large volumes of data requires robust infrastructure and sometimes specialized tools.

####  Complex Data Relationships :
 Understanding and managing the relationships between different tables(e.g.,orders, customers, products) can be challenging.

 Deciding the right level of normalization to balance performance and complexity is crucial.
#### Visualization:

Creating visualizations that accurately represent the data and are easy to interpret can be challenging.

 Translating complex data analysis into actionable business insights requires a deep understanding of the business context and effective communication skills.

 ## Data Model

![Relationship between Files](https://github.com/user-attachments/assets/81f76781-c600-4ba9-9f61-f14b237cb0ce)

 
## PROJECT ANALYSIS 

This dashboard helps Olist store understand their customers better. It helps the Olist store know if their customers are satisfied with their services by identify insights and trends that can help improve the overall performance of the business.

Identifying top-performing products and categories.
Analysing customer behaviour and preferences.
Analysing sales and revenue trends over time.
Identifying factors that contribute to customer retention.
Developing recommendation for targeted marketing campaigns and promotions.


## Steps followed 

- Step 1 : Load data into Excel to create Excel dashboard, load data into Power BI Desktop to create Power BI dashboard and load data into Tableau to create Tableau dashboard, dataset is a csv file.

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

- Step 4 : It was observed that errors and null values were present in few columns.

- Step 5 : Visual filters (Slicers) were added for fields named "Year of order purchase", "Payment Type", "Review score" & "Product category" etc.

- Step 6 : Card visuals were added to the canvas, representing Total Sales, Average shipping days and Average Review score.
 
- Step 7 : Different types of chart Visual was used to represent the 5 KPI's.

- Step 8 : In the report view, under the insert tab, one text box was added to the canvas, where name of the project was mentioned.

- Step 9 : In the report view,  using image option company's logo was added to the report design area. 

- Step 10 : PDF button was added in Tableau dashboard which helps to download the dashboard in PDF format along with Navigation button which helps to navigate to another dashboard. 

        
Card visuals were used to represent Total Sales, Total Profit, Avg Shipping days and Total Unique customers.

 
 ![Total sales-card](https://github.com/user-attachments/assets/9be6a7c9-c07b-4c1b-8cca-bae229c4dbfa)
 
 ![Total Profit-Card](https://github.com/user-attachments/assets/2371fab5-5a4d-4934-a61a-60da8f07e86c)

 ![Avg ship days-card](https://github.com/user-attachments/assets/74e73a82-fabd-4b55-ae43-5c6c8158fda0)

 ![Total review score-card](https://github.com/user-attachments/assets/184b2aed-5095-43ec-90af-08f723e052b0)


 ## Data Visualization/Dashboard Snapshot (Power BI DESKTOP)

 
![Dashboard Screenshot](https://github.com/user-attachments/assets/ac541a4a-03fc-49c9-8cc7-1fcdd514e566)

 ## Data Visualization/Dashboard Snapshot (Excel)

 ![Excel dashboard snap](https://github.com/user-attachments/assets/33bc7299-7199-498f-b28f-89367a11826f)

  ## Data Visualization/Dashboard Snapshot (Tableau)

  ### 1. Executive Dashboard

  ![Tableau Dashboard](https://github.com/user-attachments/assets/46d3d381-04fc-421c-952f-f0d18a6657e9)

 ### 2. Map Visuals

 ![Tableau Map dashboard](https://github.com/user-attachments/assets/ab67b97f-8dcb-4140-b75c-5b247efe3b2c)

## Insights

Analysis of the KPIs provides valuable insights for optimizing marketing strategies, logistics, and customer engagement to enhance overall performance.

Identifying trends in customer behaviour, payment patterns, and regional preferences can drive targeted business decisions and resource allocation.

Delivery performance could also influence review scores and success rate could certainly be improved.



