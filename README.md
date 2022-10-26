# Supply-Chain-Analysis-Power-BI
As part of the October month codebaiscs resume Project challenge, I have performed data analysis and designed a dashboard in Power BI
# Problem statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

# Task List
Peter Pandey is the data analyst in the supply chain team who joined Atliq Mart recently. He has been briefed about the the task in the stakeholder business review meeting. Now Imagine yourself as Peter Pandey and play the role of the new data analyst who is excited to build this dashboard and perform the following task

- Create the metrics according to the metrics list.
- Create a dashboard according to the requirements provided by stakeholders in the business review meeting.(You will be provided with the transcript of this business review meeting in the form of a comic.)
- Create relevant insights that are not provided in the metric list/stakeholder meeting.

# Data Model

![image](https://user-images.githubusercontent.com/114512832/198085232-e423895b-013c-48d9-94d0-65c13717cf33.png)

# Dashboard

![Atliq_mart_Supply_chain_analysis_page-0001](https://user-images.githubusercontent.com/114512832/198085887-bd78bb32-d8e2-477f-8338-3acd29d45388.jpg)

# Some Major Insights
- All the Key Metrics (OT%, IF%, OTIF%) are far behind the target
- On an average, orders are delayed 0.42 days from the agreed date of delivery- 
- Lotus Mart, Coolblue, Acclaimed stores have the highest orders as well as delayed the most to deliver the products on time
  - Is it because we are not estimating the right delivery date?
  - Is it because we are receiving more orders than expected?
- Ghee, curd and butter products are most delayed to deliver.
- There is no noticeable improvements in any of the key metrics in the last few months
- There is a huge gap in IF% for most of the customers. Is it because of less production?

# created following KPI's using Dax
- Total Order Lines
- Line Fill Rate [ LIFR ]
- Line Fill Rate % [ LIFR% ]
- Volume Fill Rate [ VOFR ]
- Volume Fill Rate % [ VOFR% ]
- Total Orders
- On Time Delivery % [ OT% ]
- In Full Delivery % [ IF% ]
- On Time In Full % [ OTIF% ]
- On Time Target 
- In Full Target 
- On Time In Full Target 
- Delayed Orders Count

