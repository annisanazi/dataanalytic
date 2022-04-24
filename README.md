# Data Analytics
These are some of my projects in the field of data analytics. I work on some data related to HR, Procurement, and Finance data.

I automate data and create dashboards for data visualization using several tools, namely Power Query, Power BI, Power Automate, MySQL, and Hive Hadoop.

### Power Automate
I use power automate to retrieve daily data received from email. The data is used as additional data for the use of the dashboard.

The process is when a trigger email is received, Power Automate will run automatically and save the data from the email into a shared folder.

This is the preview of the process
![Power Automate Email](https://github.com/annisanazi/datanalytics/6.png)

### Power Query
I use power query to do ETL (Extract, Load and Transform) for data cleansing before doing data visualization or dashboard creation.

The following is an example of a project that I did use Power Query, namely making a daily report for the Actual Cashflow used by the Finance Team.

The data used comes from an SQL database that has been previously queried. The data has been automated so that there is no need for ETL every time reporting. The report will be auto-generated if you select the required month.

This of course will save the time needed to make weekly reports.

This is the preview of the process
![ACF Report](https://github.com/annisanazi/datanalytics/5.png)

### Power BI
Data analytics cannot be separated from the existence of visualization data. Here I use Power BI as a tool for data visualization.

The following is an example of using Power BI for monitoring reports in the Finance division, one of which is for calculating SLA and monitoring cooking oil sales, as is the current trend.

Another feature is the presence of DRLS (Dynamic Role Level Security) to limit the use of the dashboard according to the user.

The data sources used are data from Power Automate, Excel, SQL Database, and Hex Hive Hadoop shared folders.

This is the preview of high level summary - Operasi Pasar Minyak Goreng
![ACF Report](https://github.com/annisanazi/datanalytics/1.png)

This is the preview of SLA chart
![ACF Report](https://github.com/annisanazi/datanalytics/2.png)

This is the preview of billing reporting
![ACF Report](https://github.com/annisanazi/datanalytics/3.png)
