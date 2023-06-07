# MS-EXCEL-AtliQ-hardware-sales-finance-excel-report
I present to you one of my major MS Excel Project's based on AtliQ Hardwares SALES AND FINANCIAL PERFORMANCE



-Why does one need Sales Dashboard?

➡ To improve sales 

➡ Customer Performance Report gives more insight on what all months sales have been maximum. Eg Time of Festivals

➡ To understand which region is doing better in terms of sales



***PROJECT DATAFLOW***

➡ ETL PROCESS (Extract ,Transform, Load)

-Ensure no missing values

-Ensure all dimension table contain unique column

-Ensure no errors



➡ STEPS IN CLEANING

-Removing spaces with "NA"

-Correcting Spellings 

-Removing Duplicates



➡ ADDING ALL TABLES TO DATA MODEL



➡ DATA MODELLING IN POWER PIVOT

-As per star schema



➡ CREATING DATE TABLE IN POWER QUERY 

-Creating a Fiscal date column For AtliQ hardware company from month of September to August.

 -Adding 4 months to date column to get fiscal date.

 

➡ Customer Performance Report

 -Using CALCULATE function to calculate net sales per year to create a measure to add in pivot table

 

➡ USER EMPATHETIC REPORT DESIGN

-Changing number formatting (Net sale numbers to Millions rather than huge number)

-Conditional Formatting

-Formatting Borders Of Cells

 

➡ MARKET PERFORMANCE VS TARGET

-Bringing in Target file, data modelling and adding the column into pivot table after creating required measures.

 

 ➡ FINANCE ANALYTICS

P&L STATEMENT

-Gross Margin=Net Sales - COGS (Cost of goods sold)

-Gross Margin% =(gross margin/net sales) *100

 

➡ ADDING FINANCE DATA TO DATA MODEL

 

➡ CREATING P&L By Year Report

 

➡ FINE TUNING OF P&L REPORT

-Creating a customized Pivot table

 

➡ ADDING MONTHS AND QUARTERS IN DATA

 

➡ CREATING P&L BY MONTH REPORT

-Adding quarters as per fiscal year (By adding 4 months to the original date month)

.Then converting fiscal month to calendar month

.Dividing Month Numbers by 3 and rounding them up [Use roundup function] and concatenate "Q" to it.

 

➡ FINE TUNING OF END REPORT BY CONDITIONAL FORMATTING
