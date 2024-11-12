
# Sales-Management-Dashboard

## Business Request & User Stories
The business request for this data analyst project was an executive sales report for sales managers. Based on the request that was made from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria’s were maintained throughout the project.
1	Sales Manager	To get a dashboard overview of internet sales	Can follow better which customers and products sells the best	A Power BI dashboard which updates data once a day
2	Sales Representative	A detailed overview of Internet Sales per Customers	Can follow up my customers that buys the most and who we can sell more to	A Power BI dashboard which allows me to filter data for each customer
3	Sales Representative	A detailed overview of Internet Sales per Products	Can follow up my Products that sells the most	A Power BI dashboard which allows me to filter data for each Product
4	Sales Manager	A dashboard overview of internet sales	Follow sales over time against budget	A Power Bi dashboard with graphs and KPIs comparing against budget.


## Data Cleansing & Transformation (SQL)
To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using SQL.

One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the SQL statements for cleansing and transforming necessary data.
DIM_calender:

![image](https://github.com/user-attachments/assets/8d6ccd81-c90f-474d-9c64-9e9f0aae23d8)

DIM_Customers:

![image](https://github.com/user-attachments/assets/44734e88-da21-495c-afa1-5fc8e6c898a6)

DIM_Products:

![image](https://github.com/user-attachments/assets/1e5ab71c-4339-447e-be19-c8a1ae40d3f9)

FACT_InternetSales:

![image](https://github.com/user-attachments/assets/0f80db62-1c4a-48cd-85b0-7ec0eddaa6ab)

#Data_Model
Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.

This data model also shows how FACT_Budget hsa been connected to FACT_InternetSales and other necessary DIM tables.

![image](https://github.com/user-attachments/assets/7a5cad47-2b80-462b-8d2a-b51ecd2d22cf)


#Sales Management Dashboard
The finished sales management dashboard with one page with works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.
![image](https://github.com/user-attachments/assets/62637a07-1a23-4950-93f1-2528ec6e78b2)


