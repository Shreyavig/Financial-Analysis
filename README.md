
# Financial Analysis Dashboard

## Problem Statement

This dashboard helps to understand the revenue analysis for the year 2019-2020. This dashboard will help access the financial performance with key metrics such as total revenue, average revenue, total transactions presented in intuitive visualizations.It gives the analysis for different stores,region and also according to different quarters.
###Steps Followed

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 :Check the columns and delete the empty columns.
- Step 4 : The data type for years and month were changed to text.
- Step 5 :After transforming the data , clicked on close and apply from home tab.
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : As there is only one table, a new table named "Measures" was created for measures so that a relation can be established between the given table and new table.
- Step 8 : Visual filters (Cards) were added for four fields named "Total Revenue", "Average Revenue", " Total Transactions","Total Countries" using measures .
- Step 9 : Visual filters (Slicers) were added for three fields named "Years", "Quarters", "Rank".
- Step 10 : A Donut Chart was added  to the report design area representing the Total Revenue By Region. While creating this visual, field named "Region" was also added to the Legends bucket, thus revenue was seggregated according to the region. Formatting for this visual was done.

- Step 11 : Line and stacked column chart was used to show "Total Revenue by Country" where Average Revenue was taken on line and field named "Region" was also added to the Column Legend, thus seggregating the total and average revenue by country and region.
- Step 12 : A tree map was created depicting the Total Revenue for different stores.
- Step 13 - Area chart was used to represent "Total Revenue By Quarter".
- Step 14 - Ribbon chart was created to show the Total Revenue according to the Products and in legend "Rank" was taken which sorted the data according to the products of different stores.
- Step 15 - Matrix table was used to analyze Sales Represntatives according to Total Transactios, Total Revenue and Average Revenue which was taken in values and formatting was done.
- Step 16 -Comparison of Total revenue and Average Revenue monthly was done using Line and Clustered Column Chart.

###DAX Expressions used for creating Measures for Card Visuals.
- 1) Total Revenue = SUM('DataSet xlsx - Sheet1'[Revenue (USD)]).
Snap of Total Revenue:
![Total Revenue](https://github.com/Shreyavig/Financial-Analysis/assets/158707069/f09bad26-c2d1-4f92-aaa1-40b3b41b805a)

- 2)Average Revenue = AVERAGE('DataSet xlsx - Sheet1'[Revenue (USD)]).
Snap of Average Revenue :
![Average Revenue](https://github.com/Shreyavig/Financial-Analysis/assets/158707069/defc4761-2022-4fde-98f2-93a52f2a9123)
- 3) Total Transaction = COUNT('DataSet xlsx - Sheet1'[First Name]).
Snap of Total Transaction : 
![Total Transaction](https://github.com/Shreyavig/Financial-Analysis/assets/158707069/38e8177b-9ecb-4f42-81a0-eb83231ff8d4)

-4) Total Countries = COUNT('DataSet xlsx - Sheet1'[Country]).
Snap of Total Countries :
![Total Countries](https://github.com/Shreyavig/Financial-Analysis/assets/158707069/22ef2f92-4e6f-412b-b3e3-c832854c3793)

### SNAP OF POWER BI DASHBOARD 
![Financial Analysis Dashoboard](https://github.com/Shreyavig/Financial-Analysis/assets/158707069/db47d14c-fb7b-4744-afc9-92cc3bf572e1)





