# AtliQ_Sales_Insights_PowerBI

Designed a Power BI dashboard to understand AtliQ hardware goods sales trend.

The final dashboard was effective at displaying the sales trend of AtliQ hardware, allowing users to understand the data and make informed decisions. 

Live DashBoard Link - https://app.powerbi.com/view?r=eyJrIjoiZDI1ZDAxMjYtNTZjYS00MDgwLWE1M2QtMmIyYjBmMzJlYTIyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9
Novypro Link - https://www.novypro.com/project/atliq-sales-insights--power-bi-1

**Problem statement:**

AtliQ hardware is a company which delivers computer hardware & peripheral Manufacturers to his clients, which has several branches throughout India. The sales director of the company is facing a lot of issues in terms of understanding how the business is performing and what are all the problem company is facing currently as the sales are not as expected and declining gradually. And whenever he calls the regional managers to get the current status of the sales and market, as a human behaviour, these people Humans are not comfortable in consuming numbers from excel files, which is obvious reason for the frustration.

**Solution:**

Sales director of the AltiQ hardware, decided to build a PowerBI Dashboard for converting the data into visual representation to make data driven decisions. So, he hired a team of data people to complete this task.

### AIMS Grid

By using the AIMS grid project management tool, we made sure what are the purpose, stakeholder, end result 
and success criteria  of our project.

<img src="https://github.com/Naveen-S6/AtliQ_Sales_Insigths_PowerBi/blob/main/DATASET/AIMS.jpg" width="550" class="center">
   
**Steps Followed in this project:**

1) Used MySQL for retrieving the data from the database into Power BI.
2) Data Cleaning in power query.
3) Performed ETL process (Extract Transform and Load)
4) Created measure for needs and used them for creating visuals in PowerBi.
5) In the currency there were two types of currencies in transactions, performed currency conversion to make all the currency type same
6) Data Validation
7) Data Modelling and Visualization.


**Major Changes/ Customizations Made:**
1) Solved the ‘(blank)’ problem for the products section by deleting the original products table and adding the self-modified products table (where I have added the Products ranging from Prod280 to Prod339 with their product type (random type- b/w ‘Own Brand’ and ‘Distribution’).
2) Merged the original modified ‘sales_transaction’ table with the new ‘sales_transaction’ table having profit margin, cost price, etc.

**Insights:**
1) In this dashboard, we can see company has generated total revenue in 4 years ₹ 985M, total profit margin ₹24.7M, Profit margin% 2.5%, Sales Qty ₹2M. in 2020 company has generated total revenue of ₹ 142M by selling a total of 350K and earned a profit of ₹ 2.1M.
2) In 4 years Delhi NCR is our largest market in terms of revenue with ₹ 520M and total contribution of 52.8% with total revenue but if you look at the profit margin Delhi NCR is generating only 2.3% profit margin.
3) If we check the profit margin then here In 2020 Bhubaneshwar comes into the picture which is generating the highest profit margin of 10.48%. Similarly, if we can check the Profit Contribution % by Market then here Mumbai is the largest player with 23.89% of total contribution in total profit.
4) In 4 years Bengaluru generating the lowest profit margin of -20.8%.if we can check the Profit Contribution % by Market then here also Bengaluru is the Lower with -0.3% of total contribution in total profit.
5) In our top 5 customers, the Electricalsara Stores is our biggest customer who has generated total ₹ 413 M revenue generated in 4 years.
6) In our top 5 products,the Prod318 is our highest product has generated total ₹ 69M revenue generated in 4 years.
7) In product type Distribution has generated the revenue of ₹494M and ownbrand revenue is ₹494M generated in entire 4 years.
8) Revenue Trend is showing that in June 2020 revenue has been decreased drastically compared to the revenue last year and the profit margin was the least in April 2020.

   
**Key Learnings:**
1) Learned about what real business data sets look like.
2) Learned about how to write some major analysis queries in MySQL.
3) how to connect the database’s tables to Power Bi and how to clean & modify the unwanted data in Power Query.
4) Learned about some major practical DAX functions and measures.
5) Learned about some major analytical visuals and reports.


**SKILLS**
1) SQL
2) PowerBI
3) Power Query
4) Exploratory Data Analysis(EDA)
5) Data Visualization.

**Concluion**
- Sales are declining due to COVID-19 Situation
- Total Revenue = ₹984.87M
- Total Sales Quantity = 2429K
- Total Profit Margin = ₹2.06M
- Revenue of Delhi is higher with 54.7% But Profit Margin % is 0.6% and Contribution in Profit is 22.1% in 2020 and Sales Quantity of Delhi is also highest with 989K
- Revenue of Mumbai is 14.2% But Contribution in Profit % is Highest with 23.9% Which makes it a Biggest Market in 2020
- Bhubaneshwar is also generating Highest Profit Margin % with 10.5% But in Total Profit Contribution is not performing well 0.8% in 2020
- Electricalsara Store tops the highest customer by revenue with ₹413.33M
- In 2020 Revenue is less than 2019 throughout the year


