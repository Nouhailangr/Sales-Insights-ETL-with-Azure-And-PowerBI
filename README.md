# Sales Insights ETL with Azure and Power BI

## Table of Contents
1. Project Overview
2. Technologies Used
3. Dataset Overview
4. Data Pipeline
5. Repository Structure
7. Dashboard
8. Conclusion
9. Contacts

## Project Overview
This project is a comprehensive data engineering solution that extracts sales data from a Github Repository, uploads it in Azure Blob Storage, performs data transformations using Azure Data Factory, and visualizes the results through interactive dashboards in Power BI. The goal is to empower business analysts and decision-makers with actionable insights from the sales data, enabling improved sales strategies, customer targeting, and overall business performance.

## Technologies Used
- Azure Data Factory: Used for orchestrating data extraction, transformation and loading processes.
- Azure Blob Storage: Used as the initial data storage solution.
- Azure Data Factory Studio: Used for data transformation.
- Azure SQL Database: Used to store the cleaned sales data.
- Azure Data Studio: Used to verify the data success of the ETL process (Storing the data from Azure Blob Storage to Aure SQL Database).
- Power BI: Used for data visualization and dashboard creation.
- GitHub: Hosting the raw Sales data.

## Dataset Overview
The dataset includes the following columns:

1. **Order ID**: Unique identifier for each order.
2. **Order Date**: Date when the order was placed.
3. **Ship Date**: Date when the order was shipped.
4. **Customer ID**: Unique identifier for each customer.
5. **Ship Mode**: Method of shipping (e.g., Standard Class, Express).
6. **Customer Name**: Name of the customer.
7. **Segment**: Market segment (e.g., Consumer, Corporate).
8. **Country**: Country where the customer is located.
9. **City**: City where the customer is located.
10. **State**: State where the customer is located.
11. **Postal Code**: Postal code of the customer’s address.
12. **Region**: Region within the country (e.g., East, West).
13. **Product ID**: Unique identifier for each product.
14. **Category**: Category of the product (e.g., Furniture, Office Supplies).
15. **Sub-Category**: Sub-category of the product (e.g., Chairs, Binders).
16. **Product Name**: Name of the product.
17. **Sales**: Total sales amount for the order.
18. **Quantity**: Number of units sold.
19. **Discount**: Discount applied to the order.
20. **Profit**: Profit earned from the order.

## Data Pipeline
![Project Pipeline](https://github.com/user-attachments/assets/707ea45d-b7bf-4bb0-bed5-5e25bd512f16)

## Repository Structure


## Project Setup
### Steps Completed:
- [x] **Create a Storage Account**
- [x] **Create a Blob Container**
- [x] **Upload the Dataset**
- [x] **Create Azure SQL Database**
- [x] **Azure Data Studio**
- [x] **Create the SalesData Table**
- [x] **Set Up Azure Data Factory for ETL**
  - Create an Azure Data Factory Instance
  - Open the Azure Data Factory Studio
  - Create a Pipeline for ETL
    - Create Linked Services (Connections)
    - Create a Linked Service to Azure SQL Database
  - Create Datasets
    - Create a Dataset for Blob Storage
    - Create a Dataset for Azure SQL Database
  - Create the ETL Pipeline
- [x] **Transform and Save Data to Azure SQL Database**
- [x] **Connect Azure to Power BI**

## Dashboard
The data from Azure SQL Database is visualized using Power BI, enabling insightful analysis and reporting of sales data.
![SuperStore Overview Dashboard](https://github.com/user-attachments/assets/d1568319-1c78-4931-aa4e-2211f2913b89)


## License
This project is licensed under the MIT License.

## Acknowledgements
Thanks to Microsoft Azure for providing powerful cloud services and to Power BI for enabling effective data visualization.
