# Customer Segmentation
## Project Overview
This project analyzes the performance of a Superstore by examining sales trends, customer acquisition trends, and the busiest day of the week for orders. Additionally, it includes customer segmentation analysis. This segmentation is performed using both existing geographical or categorical labels within the dataset and through Recency, Frequency, and Monetary (RFM) analysis. In the RFM analysis, each score is scaled from 1 to 5.

---

## Dashboard Insihgt
This analysis generates two main dashboards: Overview and RFM Analysis.

### **Overview** 
The goal of this dashboard is to provide a general overview of the company's performance, both in terms of sales generation and customer engagement (through orders and customer count).
* Dynamic total customer and sales trends can be viewed based on the selected year using a slicer.
* Visualization of peak order days within a week (whether on weekends or weekdays).
* Total orders categorized by customer segment: Consumer, Corporate, or Home Office.
* Total sales based on State, relevant as the data context is US consumers.
  
![image](https://github.com/user-attachments/assets/53f95b7c-467b-4192-94b7-df79ab792c19)

### **RFM Analysis**
This dashboard aims to display detailed RFM scores for each customer, including:
* A table showing customer names along with their RFM scores and their assigned segmentation category based on these scores.
* Distribution of RFM scores.

![image](https://github.com/user-attachments/assets/e372bdac-8228-406c-9c4d-d78636237782)

---

## Repo Content
This repository contains the main components of the project:
* Power BI Report: The Power BI .pbix file that you can open and explore.
* Export file of Dashboards: The file .pdf, which is an exported version of the Power BI Dashboards.
* EDA: This contains the Jupyter Notebook (.ipynb) file that documenting the Exploratory Data Analysis (EDA) process, including data cleaning and manipulation steps.

---

## Workflow
The project workflow is as follows:
1. Exploratory Data Analysis (EDA): Raw data is analyzed, cleaned, and manipulated using Python in a Jupyter Notebook. Details of this process can be found in the .ipynb file within the EDA/ folder.
2. Data Visualization: The clean data is subsequently used to build interactive visualizations in Power BI.
3. RFM Score Calculation: RFM scores were calculated using DAX within Power BI.

---

## Methodology
Using DAX, RFM analysis is calculated based on scores on a scale of 1 to 5. A higher score indicates better performance.
* Recency: A higher Recency score indicates a more recent transaction since the customer's last purchase or a specified date.
* Frequency: A higher Frequency score indicates how often a customer makes purchases within a given period.
* Monetary: A higher Monetary score indicates how much money a customer has spent within a given period.

---
 
## Tools
* Microsoft Power BI
* Python / Jupyter Notebook
* DAX
