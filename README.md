💳 Credit Card Transaction & Customer Analytics Dashboard

📌 Project Overview

The Credit Card Transaction & Customer Analytics Dashboard is an end-to-end data analytics project built using MySQL and Microsoft Power BI to analyze credit card transactions, revenue performance, and customer demographics.
The project uses SQL to create and manage structured credit card and customer tables, followed by Power BI dashboards to visualize key performance indicators (KPIs), quarterly trends, spending patterns, card category performance, and customer characteristics.
The objective is to convert raw credit card and customer data into meaningful business insights that support data-driven decision-making, customer analysis, and financial performance monitoring.

🎯 Project Objectives

•	Analyze total revenue, transaction amounts, transaction volumes, and interest earned.

•	Monitor quarterly revenue and transaction trends.

•	Compare performance across different credit card categories.

•	Analyze transaction methods, including swipe, chip, and online payments.

•	Understand customer demographics, education, employment, income, and marital status.

•	Evaluate customer acquisition costs across card categories.

•	Monitor customer satisfaction and identify opportunities for business improvement.

•	Develop interactive dashboards for business reporting and analysis.


🛠️ Tools & Technologies

Technology	Purpose

MySQL	Database creation, table creation, and data retrieval

Microsoft Power BI	Interactive dashboards and data visualization

Power Query	Data cleaning and transformation

DAX	KPI calculations and analytical measures

CSV	Data import and dataset storage

Data Analytics	Trend analysis and customer insights

🗂️ Dataset Description

The project uses two datasets: credit card information and customer information.

1. Credit Card Data — cc_info
The SQL script creates the cc_info table with the following fields:

•	Client_Num — Customer reference identifier

•	Card_category — Credit card category

•	Anual_fees — Annual card fees

•	Activation_30_days — Card activation information

•	Customer_Acq_cost — Customer acquisition cost

•	Week_start_date — Start date of the reporting week

•	Week_Num — Week identifier

•	Qtr — Quarter

•	Current_Year — Reporting year

•	Credit_limit — Credit limit

•	Total_Revolving_Bal — Total revolving balance

•	Total_trans_Amt — Total transaction amount

•	Total_Trans_Vol — Total transaction volume

•	Avg_Utliization_Ratio — Average credit utilization ratio

•	Use_chip — Transaction method

•	Exp_Typee — Expenditure category

•	Intrest_Earned — Interest earned

•	Delinquent_Acc — Delinquency indicator

3. Customer Data — cust_info
The SQL script creates the cust_info table with the following fields:

•	Client_Num — Customer reference identifier

•	Customer_Age — Customer age

•	Gender — Customer gender

•	Dependent_Count — Number of dependents

•	Educational_Level — Education category

•	Marital_status — Marital status

•	State_id — State identifier

•	Zip_Code — ZIP code

•	Car_Owner — Car ownership indicator

•	House_owner — House ownership indicator

•	Personal_loan — Personal loan indicator

•	Contact — Contact information field

•	Customer_Job — Customer occupation

•	Income — Customer income

•	Cust_Satisfaction_Score — Customer satisfaction score

🖥️ Dashboard Preview

1. Credit Card Customer Report
This dashboard provides an overview of customer characteristics, revenue, interest, transaction amount, and customer satisfaction.

Key KPIs displayed:

•	Total Revenue: 56.52M

•	Total Interest: 7.98M

•	Transaction Amount: 46M

•	CSS (Customer Satisfaction Score): 3.19

Visualizations included:

•	Gender-wise revenue trends by quarter

•	Customer distribution by age group

•	Customer job-wise revenue, transaction amount, and income

•	Customer distribution by state

•	Educational-level analysis

•	Marital status analysis

•	Dependent count analysis

•	Income group analysis

Interactive filters:

•	Gender: F and M

•	Card category: Blue, Gold, Platinum, and Silver

Business value: Helps stakeholders understand customer demographics, compare customer segments, and analyze revenue contributions across different customer groups.

3. Credit Card Transaction Report

This dashboard focuses on credit card transaction performance, revenue distribution, and card category analysis.

Key KPIs displayed:

•	Total Revenue: 56.52M

•	Total Interest: 7.98M

•	Transaction Amount: 46M

•	Transaction Count: 667K

Visualizations included:

•	Quarterly revenue and transaction amount

•	Revenue by transaction method: swipe, chip, and online

•	Revenue by educational level

•	Revenue by expenditure type, including bills, entertainment, fuel, grocery, food, and travel

•	Revenue by customer job

•	Card category performance

•	Customer acquisition cost by card category

Interactive filters:

•	Quarter: Q1, Q2, Q3, and Q4

•	Gender: F and M

•	Income group: High, Medium, and Low

•	Card category: Blue, Gold, Platinum, and Silver

Business value: Helps stakeholders compare quarterly performance, understand payment-method distribution, identify major revenue-contributing categories, and evaluate customer acquisition costs.

The KPI values above are transcribed from the supplied screenshots and may change when filters are applied.

📊 Key Performance Indicators (KPIs)

1.Total Revenue	Total revenue represented in the dashboard

2.Total Interest	Total interest earned from the available data

3.Transaction Amount	Aggregate transaction amount

4.Transaction Count	Number of transactions represented by the report

5.Customer Satisfaction Score	Customer satisfaction metric

6.Revenue by Quarter	Revenue performance across Q1–Q4

7.Revenue by Card Category	Revenue contribution from each card category

8.Revenue by Expenditure Type	Revenue distribution across expenditure categories

9.Customer Acquisition Cost	Cost associated with acquiring customers

10. Revenue by Customer Job	Revenue contribution by customer occupation

🗄️ SQL Implementation
The uploaded SQL script performs the following operations:

1.	Creates the credit_card_project database.

2.	Selects the database using USE.

3.	Creates the cc_info table for credit card data.

4.	Creates the cust_info table for customer data.

5.	Retrieves table data using SELECT *.

6.	Documents the CSV import process and date-format preparation for additional reporting data.

🔄 Project Workflow

1.	Database Setup: Created the MySQL database credit_card_project.

2.	Table Creation: Designed separate tables for credit card transactions and customer details.

3.	Data Import: Prepared CSV data for import into MySQL.

4.	Data Preparation: Addressed date-format requirements for reporting data.

5.	Data Modeling: Used customer reference information to support transaction and customer analysis.

6.	Dashboard Development: Built two Power BI dashboards for customer and transaction reporting.

7.	KPI Analysis: Displayed revenue, interest, transaction amount, transaction count, and customer satisfaction.

8.	Business Analysis: Used charts, tables, and filters to explore revenue trends and customer segments.

The workflow describes the overall project. Validate table relationships, cleaning steps, and calculations against your actual Power BI implementation.


💡 Business Questions Answered
This project supports analysis of questions such as:

1.	What are the overall revenue, interest, and transaction amounts?

2.	How does revenue change across quarters?

3.	Which card categories contribute the most revenue?

4.	How is revenue distributed across swipe, chip, and online transactions?

5.	Which expenditure categories contribute most to revenue?

6.	How does revenue vary by customer occupation?

7.	Which educational groups contribute to revenue?

8.	How are customers distributed across age groups, gender, and marital status?

9.	Which states have the largest customer representation in the report?

10.	How does customer acquisition cost vary across card categories?

11.	How does the customer satisfaction score appear in the dashboard?

12.	How do revenue and customer characteristics change when dashboard filters are applied?


📈 Business Insights and Recommendations
The dashboards enable users to explore the following areas:

•	Revenue performance: Compare revenue across reporting quarters and card categories.

•	Payment methods: Examine the revenue distribution among swipe, chip, and online transactions.

•	Customer segmentation: Compare customer characteristics by age, gender, education, occupation, and income.

•	Expenditure analysis: Identify expenditure categories with higher revenue contributions.

•	Acquisition cost: Compare customer acquisition costs across card categories.

•	Customer satisfaction: Monitor the displayed satisfaction metric alongside revenue and transaction indicators.

Potential Business Recommendations

•	Review card categories with lower revenue contributions to identify opportunities for improvement.

•	Use customer segmentation to develop relevant customer engagement campaigns.

•	Monitor quarterly revenue and transaction activity to support performance planning.

•	Evaluate customer acquisition costs alongside revenue contribution.

•	Investigate customer satisfaction patterns to identify potential service improvements.

These are analytical opportunities and recommendations, not independently verified findings. Further analysis is needed before drawing conclusions about profitability, customer behavior, or business performance.

🚀 How to Run the Project

Prerequisites

•	MySQL Server

•	MySQL Workbench or another compatible MySQL client

•	Microsoft Power BI Desktop

•	The required credit card and customer datasets

Step 1: Clone the Repository
git clone https://github.com/YOUR-USERNAME/Credit-Card-Analytics-Dashboard.git
Navigate to the repository:
cd Credit-Card-Analytics-Dashboard
Replace YOUR-USERNAME with your GitHub username and the repository name with your actual repository name.

Step 2: Create the Database
1.	Open MySQL Workbench.
2.	Open CREDIT CARD PROJECT FILE.sql.
3.	Execute the SQL script.
4.	Confirm that the database and both tables are created successfully.

Step 3: Import the Data
1.	Prepare the credit card and customer CSV files.
2.	Import the datasets into cc_info and cust_info, respectively.
3.	Ensure the CSV columns match the table schema and the date fields use the required format.
4.	Validate the imported data using SELECT statements.

Step 4: Open the Power BI Dashboard
1.	Open the Power BI .pbix file, if included in the repository.
2.	Update the data source paths if required.
3.	Refresh the datasets.
4.	Verify the table relationships and KPI calculations.
5.	Explore the customer and transaction reports using the available filters.

🔮 Future Enhancements
•	Add SQL queries for quarterly revenue, card category comparisons, and customer segmentation.

•	Improve data validation and duplicate-record handling.

•	Develop a dedicated Date table and time-intelligence measures in Power BI.

•	Add transaction success, failure, refund, and chargeback analysis if the required data is available.

•	Perform deeper customer segmentation and retention analysis.

•	Add automated refresh and reporting where supported.

•	Introduce Python-based exploratory analysis and anomaly detection as a separate enhancement.

🔐 Data Privacy
This project is intended for educational and portfolio purposes.

•	Use public, synthetic, or appropriately anonymized datasets.

•	Do not upload real card numbers, CVV values, PINs, authentication credentials, or confidential customer details.

•	Remove sensitive information from contact and ZIP code fields before publishing datasets.

•	Check the dataset's licensing and redistribution permissions before sharing it publicly.

👨‍💻 Author

Sachin Jadhav

Aspiring Data Analyst | Business Analyst

Skills Demonstrated: MySQL | Power BI | SQL Database Design | Data Visualization | KPI Reporting | Customer Analytics | Business Intelligence
This project demonstrates practical experience in organizing relational data, creating analytical dashboards, tracking business KPIs, and presenting customer and transaction insights.

⭐ Acknowledgements
This project was developed for learning and portfolio purposes to demonstrate SQL database fundamentals and Power BI dashboard development.
If you find this project useful, consider giving the repository a ⭐ on GitHub.
________________________________________________________________________________________________________________________________________________________________
Thank you for visiting my Credit Card Transaction & Customer Analytics Dashboard project!


