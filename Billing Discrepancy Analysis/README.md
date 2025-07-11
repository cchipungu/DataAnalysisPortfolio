# **ANALYSING BILLING DISCREPANCIES**
## Introduction
This analysis was done for a company that supplies scaffolding equipment to a client. The company also has staff at the client’s premises to attend to requests to erect scaffold towers of different heights. Scaffold towers have to be dismantled from one site on the premises to be erected at the site where they are requested because the client requested only a limited amount of equipment. Some sites are in states that cause difficulty in working. Staff complete daily timesheets for requests fulfilled and they are captured onto an excel spreadsheet by a data capturer.  

### Problem defintion
1.	The client raised concerns with discrepancies in billing e.g. the erection of smaller towers is sometimes billed higher than bigger towers.  
2.	The bill for March was higher than the bill for April, yet the number of hours worked in April was more.  
The company requested that I do an analysis to find out the reason for the discrepancies so that they can explain these and make recommendations to their client.  
## Data Analysis Process
### Data preparation done	
- Removed duplicates.  
- Handled missing data.  
- Standardised site status description.  
- Confirmed possibly misclassified tower sizes and other data capture errors with hard copy time sheets.  
- Ensured that overtime values recorded did not exceed the total time taken to complete the jobs.  

### Data Exploration:
From the information provided by the client, it appeared that the time taken on a job (Billed hours) could depend on the state of the site the staff is working in and size of tower being built. 
Billing for normal working hours is done using a fixed rate per hour, but billing for overtime is 1.5 times normal rate. The bill depends on how many hours were billed and whether billed hours are normal hours or overtime hours.  

I created 2 dashboards, one to answer each question.
### Tower size billing discrepancy dashboard
[See my work here](https://github.com/cchipungu/DataAnalysisPortfolio/blob/main/Billing%20Discrepancy%20Analysis/TowerBilling/TowerBilling%20Discrepancy%20Analysis.xls)

![TowerBilling](https://github.com/user-attachments/assets/669a2abe-5ca4-469e-b021-1e796feba010)

### Monthly billing discrepancy dashboard
[See my work here](https://github.com/cchipungu/DataAnalysisPortfolio/blob/main/Billing%20Discrepancy%20Analysis/MonthlyBilling/MonthlyBilling%20Discrepancy%20Analysis.xlsx)

![MonthlyBilling](https://github.com/user-attachments/assets/906f7c45-911f-4601-9d2a-e72a987a5756)


