# My_First_Excel_Project

## INTRODUCTION
This project looks at the analysis of a dataset of a dataset consisting of  Gross sales, COGS and profit data sorted by market segment and country region. **This dataset was gotten from KEGGLE**.
### SKILLS DEMONSTRATED
- Data Cleaning
- Use of some advance excel function
- Use of some Excel tools
- Excel pivot table
- Data visualization
#### PROJECT OBJECTIVE
- Check for the different KPI's
- Analyze the different countries by sum of Gross sales
- Analyze the different Products by  sum of COGS
- Analyze the different Segments by sum of units sold
- Analyze the  profit of products in each year

**DATA CLEANING**

So after opening the dataset, it was looking like this at first;
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_iF0TgYaGt9.png)


Then I checked if there were any duplicate in the dataset by clicking on all the cells and clicking on the the DUPLICATE button on the ribbon. After i discovered there were no duplicate.

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/dNxJVEddA0%20(2).png)


The 'COGS', PROFIT and GROSS SALES column have some cells containing the '$' and ',' signs in the values. So I used the **Ctrl+H** shortcut key which opens the 'find and replace' tool to eliminate them by replacing those signs with a NULL value.

![Unclean Column ](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_eIRPzKlxnJ%20(2).png)  ![Clean Column](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_JjohoKpUpF%20(2).png)


Since there is a DATE column I had to delete the other MONTH NUMBER, MONTH NAME, and YEAR column to reduce the number of column in the dataset because they were containing the same month number, month name, and year with the DATE column.

**ANALYSIS**

The dataset now consist of the SEGMENT, COUNTRY, PRODUCT, DISCOUNT BAND, UNITS SOLD, MANUFACTURING PRICE, SALE PRICE, DISCOUNTS, GROSS SALES, COGS, PROFIT, and DATE column.
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_eXlUJgw7dP.png)

I used the **SUMIFS** and **AVERAGEIFS** function to calculate the sum and average cost of the product **Paseo** in **Canada**.
![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_KciyWeNODX~2.png)

![](https://github.com/festusaigbogun/My_First_Excel_Project/blob/main/Images/EXCEL_JjohoKpUpF.png)

Using the **Ctrl+T** shortcut key i was able to create a table for the dataset. The advantage of creating a table is that it helps create a column header and filter, make the dataset virtually appealing, for easy sorting and aggregation and lastly, tables work well with Excel's data visualization tools, like pivot tables and pivot charts which allow one to analyze and present data more effectively.

**PIVOT TABLE**

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

**SEGMENT BY SOME OF UNITS SOLD**

It is important to analyze for the sum of units sold  by segment. The results is shown in the pivot table and chart below:


**PROFIT OF PRODUCTS IN EACH YEAR**

Lastly, the profit of products in each year was also analyze using pivot table and the chart below:

**DATA VISUALIZATION**

Using different visualization chart I was able to create a dashboard for this analysis

**INSIGHTS**

* The product **Paseo** have the largest Gross sales and profit, while the product **Carretere** has the lowest sales.
* The **United State Of America** have the highest sum of Gross sales compare to the remaining four countries.
* The **Goverment** segment has the highest sum of units sold compare to the **Small business** which have the lowest.

**RECOMMENDATIONS**
  
* Capitalize on **Paseo** as it is evident that it have the hihest profit and gross sales generation. It would be beneficial to analyze the factors that contributed to the success and replicate those stategies to the other products.
* There should be more sales of **Paseo** and also more sales should be done in **Canada** because that's where more profit is been generated.



