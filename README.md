# My_First_Excel_Project

## INTRODUCTION
This project involves analyzing a dataset comprising gross sales, COGS, and profit data, organized by market segment and country region. The dataset contains 701 rows. **This dataset was gotten from KAGGLE**.
### SKILLS DEMONSTRATED
- Data Cleaning
- Use of some advance excel function
- Use of some Excel tools
- Excel pivot table
- Data visualization
### PROJECT OBJECTIVE
- Check for the different KPI's
- Analyze the different countries by sum of Gross sales
- Analyze the different Products by  sum of COGS
- Analyze the different Segments by sum of units sold
- Analyze the  profit of products in each year

### DATA CLEANING

So after opening the dataset, it was looking like this at first;
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_iF0TgYaGt9.png)


Then I checked if there were any duplicate in the dataset by clicking on all the cells and clicking on the the DUPLICATE button on the ribbon. After i discovered there were no duplicate.

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/dNxJVEddA0%20(2).png)


Some cells in the 'COGS,' 'PROFIT,' and 'GROSS SALES' columns include '$' and ',' symbols within their values. To remove these symbols, I utilized the Ctrl+H shortcut, which opens the 'find and replace' tool, replacing these symbols with NULL values.

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_eIRPzKlxnJ%20(2).png)
  ![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_JjohoKpUpF%20(2).png)


Given the presence of a DATE column, I opted to remove redundant columns such as MONTH NUMBER, MONTH NAME, and YEAR, as they duplicated the information already available in the DATE column. This streamlined the dataset by reducing the number of columns.

### ANALYSIS

The dataset now consist of the SEGMENT, COUNTRY, PRODUCT, DISCOUNT BAND, UNITS SOLD, MANUFACTURING PRICE, SALE PRICE, DISCOUNTS, GROSS SALES, COGS, PROFIT, and DATE column.
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_eXlUJgw7dP.png)

I employed the **SUMIFS** and **AVERAGEIFS** functions to derive the total and mean expenses for the product Paseo in the Canadian context.
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_KciyWeNODX~2.png)

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_JjohoKpUpF.png)

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_eiW2UH0Apb~3.png) 

Using the **Ctrl+T** shortcut key i was able to create a table for the dataset. The advantage of creating a table is that it helps create a column header and filter, make the dataset virtually appealing, for easy sorting and aggregation and lastly, tables work well with Excel's data visualization tools, like pivot tables and pivot charts which allow one to analyze and present data more effectively.

### PIVOT TABLE

The next step was creating a pivot table from the dataset to achieve my objectives
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_Cnxx755S6A.png) 

**KPI's**

Using pivot table I was able to get the Key Performance Indicator for this analysis
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_4XMwo9jErn~2.png) 

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_70O5BxgmBh~4.png) 

**COUNTRY BY SUM OF GROSS SALES**

It is important to analyze for the sum of Gross sales by country. The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_9HhoAjZN3Z~2.png) 

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_v950OurQTN~2.png) 

**PRODUCT BY SUM OF COGS**

It is important to analyze for the sum of COGS  by product. The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_dAXqiWu4x1~2.png) 

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_v950OurQTN~3.png) 

**SEGMENT BY UNITS SOLD**

It is important to analyze for the sum of units sold  by segment. The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_9HhoAjZN3Z~3.png) 

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_70O5BxgmBh~5.png) 


**PROFIT OF PRODUCTS IN EACH YEAR**

Lastly, the profit of products in each year was also analyze using pivot table and the chart below:
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_dAXqiWu4x1~3.png) 

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_v950OurQTN~4.png) 

### DATA VISUALIZATION

Using different visualization chart I was able to create a dashboard for this analysis
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_v950OurQTN~5.png) 

### INSIGHTS

* The product **Paseo** have the largest Gross sales and profit, while the product **Carretere** has the lowest sales.
* The **United State Of America** have the highest sum of Gross sales compare to the remaining four countries.
* The **Goverment** segment has the highest sum of units sold compare to the **Small business** which have the lowest.

### RECOMMENDATIONS
Based on the insights from the dataset, here are some business recommendations:

1. **Maximize Product Paseo**:
   - Given that Paseo has the largest gross sales and profits, consider expanding its product line or running promotions to further boost sales and profits.
   - Focus on marketing strategies that highlight the value and benefits of Paseo to attract more customers.

2. **Reevaluate Product Carretere**:
   - Since Carretere has the lowest sales, assess its performance and consider whether to optimize its marketing, pricing, or even potentially discontinue it if it's not profitable.

3. **Leverage the U.S. Market**:
   - As the United States has the highest sum of gross sales, allocate more resources and marketing efforts to this market.
   - Tailor your products and marketing campaigns to cater to the specific preferences and needs of U.S. customers.

4. **Government Segment Focus**:
   - Given that the Government segment has the highest sum of units sold, consider tailoring your products or services to better serve the needs of this segment.
   - Strengthen relationships with government clients and explore opportunities for long-term contracts or partnerships.

5. **Small Business Segment Growth**:
   - While the Government segment performs well, don't neglect the Small Business segment.
   - Develop targeted marketing strategies to attract and retain small business customers, potentially offering volume discounts or customized solutions.

6. **Market Diversification**:
   - Consider expanding into new markets or countries to reduce reliance on the U.S. market and tap into additional sources of revenue.
   - Perform market research to identify promising regions for expansion.

7. **Competitor Analysis**:
   - Analyze competitors in the market to understand their strategies and identify opportunities for differentiation and competitive advantages.

8. **Supply Chain Optimization**:
   - Ensure your supply chain is efficient to meet the demands of the high-performing products and segments.

9. **Continuous Data Monitoring**:
   - Continuously monitor sales data to stay responsive to changing trends and customer preferences.

10. **Customer Feedback**:
    - Gather feedback from customers in various segments to improve your product offerings and customer experience.

