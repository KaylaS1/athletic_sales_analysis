# Analysis of 2020 and 2021 athletic sales data

## Logic
1. I used concat() function to combine athletic sales data from 2020 and 2021.
1. I used both groupby() and pivot_table() functions to determine the region with the most units sold and the highest total sales amount.
1. I used both groupby() and pivot_table() functions to determine the retailer with the most units sold and the highest total sales amount.
1. To determine which retailer sold the most women's athletic footwear, I first used a unique() function to ensure that I was using the correct column and filter value. Then I used both groupby() and pivot_table() functions to determine the top women's retailer.
1. I used resample() function with Date and Week arguments to determine the top sales date and week.

## Summary of findings
1. New York city in New York state in the Northeast region sold the most units.
1. New York city in New York state in the Northeast region also had the highest sales amount.
1. Retailer West Gear in San Francisco city in California state in the West region sold the most units.
1. Retailer West Gear in San Francisco city in California state in the West region also sold the most number of women's athletic footwear.
1. The date with the highest sales amount across all retailers was July 16, 2021.
1. The week of December 19, 2021 had the highest sales amount across all retailers.

## Sources of code
* Most of my code is based on code provided in Week 5 Pandas Data Preparation Activities
* I got the to_datetime() function from a Google search