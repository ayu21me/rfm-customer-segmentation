\# Customer Segmentation using RFM Analysis



\## Project Overview

This project analyzes customer purchasing behavior using RFM (Recency, Frequency, Monetary) analysis to segment customers based on their transaction patterns.



The goal is to help businesses understand customer value and design targeted marketing strategies.



---



\## Dataset

Online Retail Dataset containing transactional records including:



\- CustomerID

\- InvoiceDate

\- Quantity

\- UnitPrice

\- Country



---



\## Methodology



\### 1 Data Cleaning

\- Removed cancelled orders

\- Removed negative quantities

\- Handled missing Customer IDs



\### 2 Feature Engineering

Created a revenue column:



Revenue = Quantity × UnitPrice



\### 3 RFM Metrics



Recency  

Days since last purchase



Frequency  

Number of purchases made by the customer



Monetary  

Total spending by the customer



\### 4 Customer Segmentation



Customers were segmented into:



\- Champions

\- Loyal Customers

\- Potential Loyalists

\- At Risk

\- Lost Customers



---



\## Dashboard



The Power BI dashboard provides:



\- Customer distribution by segment

\- Revenue contribution by segment

\- RFM scatter analysis

\- Key business insights



!\[Dashboard Preview](images/dashboard\_preview.png)



---



\## Key Insights



\- Champions contribute the highest revenue despite being fewer customers

\- Lost customers form the largest segment indicating potential churn

\- Loyal customers demonstrate consistent purchasing behavior

\- Potential loyalists can be converted to champions through targeted campaigns



---



\## Tools Used



Python  

Pandas  

Jupyter Notebook  

Power BI  



---



\## Business Impact



This segmentation helps businesses:



\- Identify high value customers

\- Improve retention strategies

\- Design targeted marketing campaigns

\- Increase overall revenue

