# My_First_Excel_Project

## INTRODUCTION
This project looks at the analysis of a dataset of a dataset consisting of  Gross sales, COGS and profit data sorted by market segment and country region. *The dataset was gotten from KEGGLE*.
### SKILLS DEMONSTRATED
- Data Cleaning
- Making use of some advance excel function
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

Then I checked if there were any duplicate in the dataset by clicking on all the cells and clicking on the the DUPLICATE button on the ribbon. After i discovered there were no duplicate.

The 'COGS', PROFIT and GROSS SALES column have some cells containing the '$' and ',' signs in the values. So I used the **Ctrl+H** shortcut key which opens the 'find and replace' tool to eliminate them by replacing those signs with a NULL value.

Since there is a DATE column I had to delete the other MONTH NUMBER, MONTH NAME, and YEAR column to reduce the number of column in the dataset because they were containing the same month number, month name, and year with the DATE column.

**ANALYSIS**

The dataset now consist of the SEGMENT, COUNTRY, PRODUCT, DISCOUNT BAND, UNITS SOLD, MANUFACTURING PRICE, SALE PRICE, DISCOUNTS, GROSS SALES, COGS, PROFIT, and DATE column.

I used the **SUMIFS** and **AVERAGEIFS** function to calculate the sum and average cost of the product "Paseo" in "Canada".

Using the **Ctrl+T** shortcut key i was able to create a table for the dataset. The advantage of creating a table is that it helps create a column header and filter, make the dataset virtually appealing, for easy sorting and aggregation and lastly, tables work well with Excel's data visualization tools, like pivot tables and pivot charts which allow one to analyze and present data more effectively.

**PIVOT TABLE**

The next step was creating a pivot table from the dataset to achieve my objectives

**KPI's**

Using pivot table I was able to get the Key Performance Indicator for this analysis

**COUNTRY BY SUM OF GROSS SALES**

It is important to analyze for the sum of Gross sales by country. The results is shown in the pivot table and chart below:

**PRODUCT BY SUM OF COGS**

It is important to analyze for the sum of COGS  by product. The results is shown in the pivot table and chart below:

**SEGMENT BY SOME OF UNITS SOLD**

It is important to analyze for the sum of units sold  by segment. The results is shown in the pivot table and chart below:

**PROFIT OF PRODUCTS IN EACH YEAR**

Lastly, the profit of products in each year was also analyze using pivot table and the chart below:

**DATA VISUALIZATION**

Using different visualization chart I was able to create a dashboard for this analysis

**INSIGHTS**

* The product "Paseo" have the largest Gross sales and profit while the product "Carretere' has the lowest sales.
* United State Of America have the highest sum of Gross sales compare to the remaining four countries.
* The 'Goverment' segment has the highest sum of units sold compare to the 'Small business' which have the lowest.

**RECOMMENDATIONS**
  
* Strategy used in the product "Paseo" for each year should also be implemented for the product "Montana" so that more profit can be generated.
* There should be more sales of "Paseo" and also more sales should be done in Canada because that's where more profit is been generated.



