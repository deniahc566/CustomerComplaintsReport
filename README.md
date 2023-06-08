# CustomerComplaintsReport
## About the dataset
[The original dataset](/master/"Insurance - Complain Administration.xlsx")  
Contains the complaints historical data from a large insurance company undergoing their internal audit process.
## Objectives
Analyze the complaints historical data, key objectives includes:  
- The most recent 2 years of data is what most stakeholders are interested in.  
- The ability to see status changes and when they happened.  
- Complaints broken down by the dimensions.  
- Display Client Satisfaction.  
- Present the Worst offending brokers.  
## Schema 
![Schema](/images/Schema.png)
The dataset includes ComplainsData_Tbl as fact table and other tables as dimension tables.  
The Calendar Table and Short Month Table were added via Power Query and DAX expressions.
## Dashboard Content
The complete dashboard can be found here  
[Complaints Dashboard PowerBI File](/ComplaintsDashboard.pbix)  
### Table of Content
![Table of Content](/images/Table_of_Content.png)  
The first page of the dashboard is the Table of Content page presenting other pages of the dashboard with links to them for easy navigations.
### General Overview
![General Overview](/images/General_Overview.png)
The General Overview page presents some of the most important metrics, the distribution of complaints overtime as well as how the percentage of clients varies by states and their population.
### Complaints Distribution
![Complaints Distribution](/images/Complaint_Distribution.png)
This page digs deep into how the number of complaints is distributed by different dimensions.
### Complaints Handling Days
![Complaints Handling Days](/images/Complaints_Handling_Days.png)
This page looks for insight in how the complaints handling process are performing by different dimensions.
### Complaints Status
![Complaints Status](/images/Complaints_Statuses.png)
This page looks into how each stages of the complaints handling process is performing to identify problems with them.
### Clients Satisfaction
![Clients Satisfaction](/images/Clients_Satisfaction.png)
Clients Satisfaction Level is extremely important and this page is intended for exploring how Clients Satisfaction Level varies between dimensions. However, a big part of clients satisfaction data seems to be missing.
### Brokers Performance Measurement
![Brokers Performance Measurement](/images/Brokers_Performance.png)
This page divides brokers into different segments base on their performance.
### Key Findings
![Key Findings](/images/Key_Findings.png)
This page summarize all the most important insights discovered by the visualization as well as giving practical suggestions to resovle the problems.
