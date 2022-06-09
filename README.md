# Iowa-Liquor-Sales

## About the Dataset
- This dataset contains the purchase information of Iowa Class "E" liquor licensees by product and date of purchase from January 1, 2012 to current (April 1, 2022 3:03 PM PDT).

## Data Provided by:
- Iowa Department of Commerce, Alcoholic Beverages Division

## What's in this Dataset?
- 23.6M Rows
- 24 Columns
- Each row is an individual product purchase

## Project Purpose
- Focused on Hy-vee stores and took a look at total sale to see if pricing strategy can be improved.
- Used Apriori algorithm to conduct a market basket analysis.

## Findings
- Some neighboring counties share the top 5 frequently purchased items but some counties have a lower profit compared to the others. 
- Interesting to see that the median household income for Linn county as reported by the 2020 census is higher than Johnson county but the retail price for the same item is lower than Johnson county. 
  - Just by matching Johnson's retail price for items like Fireball Whiskey, the stores in Linn could make $3.25 more per unit which would definitely increase the overall profit
- Overall, it seems expected to see people who purchase an item also purchase another item that's similar to it. 
  - For example you can see that someone who like fruit flavored alcohol also tends to buy another item that is also fruit flavored. We also see that if someone purchases a particular brand, they're also more likely to buy another item from that brand
- When you sort the results by Lift descending we see that for Spring, Summer and Winter, we see somewhat similar items. What I find interesting is that when you sort by lift the taste notes for the top 5 rows for each season is on the sweeter side. 
  - We see fruit flavors like cranberry, peach, and watermelon but we also see purchases of white dog products which have taste notes of apples and tropical fruit, which seems to match the other purchasing patterns.
  - I suggest Hy-Vee stores to possibly expand their sweeter and fruity alcohol selections to see if customers will purchase more. 
