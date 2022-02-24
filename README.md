# Amazon Sales Data Analysis with Python and Power BI

### Problem Statement:
The management team of Amazon currently looking to understand market behavior and sales trend to gain a competitive advantage. The objective of the project is to create a report on Sales trend year-wise, month-wise to understand the factors directly affecting the sales. This project aims apply Business Intelligence tool such as Power BI to get a visual understanding the sales data.

### Data Description:

The Dataset consists of following columns:

1.	Discount Amount: Discount on every ordered item
2.	Date: Ordered Date
3.	Item: Name of the item ordered
4.	List Price: The price at which the item is listed.
5.	Sales Amount: Total amount of sales for particular item.
6.	Sales Cost Amount: Amount spent for conversion of Sale
7.	Sales Margin Amount: Margin amount on each item sold
8.	Sales Quantity: Total number of items sold
9.	Sales Representative: Representative under whom sale is completed.

### Tools Used
- **Programming Language: Python**
- **Python Libraries: Numpy, Pandas**
- **Business Intelligence Tools: Excel, Power BI**

### Project Steps

##### Data Import & Data Cleaning
Given Data was in excel file with impurities. We import Data in Jupyter Notebook for cleaning. Data Cleaning is a crucial stage before we start creating visuals. The dataset given some time has impurities such as missing values or incorrect data types. Data cleaning is performed in Python with Pandas library to remove missing values and make dataset ready for building visuals.

##### Data Importing in Power BI
In Power BI, we have options to connect to our dataset via various options such as SQL Server, MYSQL, excel or CSV files. We have our clean data in CSV file. We will import it in Power BI with import data option and start working with it. 

##### Data Transformation in Power BI
Once the data is imported in Power BI, we do ‘transform data’ i.e. using Power Query editor to perform certain operation on to the data. Ensuring correct data types, creating custom/conditional columns are some fundamental task performed in Power Query.

##### Creating a Report in Power BI
A report is created in Power BI with various charts depicting Sales insights for particular year, month and so on. We created Slicers, Data Cards, Sales Trend for Year and Month, Table for top ordered item, top performing sales representatives and relationship between different variables that directly or indirectly impact sales.

##### Deployment in Power BI
In Power BI, You can directly publish the report online to your workstation. If you do not have the work email-id then you can save the file in ‘.pbix’ version. This helps another viewer see your work and understand the story or insights you’re communicating.

