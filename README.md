# Personal_Finance Project Using PowerBI
In this project I develop a personal financial dashboard using Microsoft Power BI.

## Set Up
Though the dashboard is about Personal Finance but it's not mine. **Finance_Database.xlsx** is our source for data and the dashboard is in the file **Personal_Finance.pbix**. 

## Backgound Information
**Following are the highlights of this project:**
* Extracted data from an Excel File
* Transformed the data using Power Query
  * Unpivoted all the date columns
  * Changed to suitable data type
  * Added a Year Column
* Added **Key Performance Indicators(KPIs)** like Total Income, Total Savings, Total Expense, Savings %, Expense %, Income Change MoM %, Cumulative Net Worth, etc.
* Used **DAX Language** to make more powerful measures for our dashboard.
* Performed **Data Modeling** to develop relationship between measures and existing table.
## Dashboard
* **Tool Tip** - Whenever someone hovers over a Bar Chart, Net Worth Card or a Line Chart, a tool tip appears to provide deeper insights to data.
* **Slicer** - To select data yearwise and monthwise
* **Cards** - Show overall Income, Expense, Savings and Net Worth
* **Clustered Bar Chart** - To show category wise Expenditure and Savings
* **Line Chart** - Shows Month over Month change in Income, Expense, Savings and also shows whether Savings target was achieved or not
* **Detailed Statement Table** - A powerful table to show overall figures over time and category
