# Superstore Sales Analysis

Exploratory data analysis of a retail Superstore dataset to find which categories, regions and products drive sales and profit.

## Dataset
- Source: Kaggle, "Superstore Dataset" (Vivek Chowdhury)
- 9,994 orders, 21 columns (sales, profit, discount, category, region, dates, etc.)

## Tools
Python, Pandas, Matplotlib, Google Colab

## What I did
1. Loaded and inspected the data (shape, data types, missing values, duplicates)
2. Cleaned it: converted date columns to datetime and created Year and Month columns
3. Used groupby to analyse sales and profit by category, region and sub-category
4. Compared average discount across Furniture sub-categories

## Key Insights
1. Technology has the highest sales (8.36 lakh) and the highest profit (1.45 lakh).
2. Furniture sales are high (7.42 lakh) but profit is only 18K (about 2.5% margin).
3. Inside Furniture, Tables (-17.7K) and Bookcases (-3.5K) are making losses.
4. Tables have the highest average discount (26%) and Bookcases 21%. High discounts are strongly associated with losses.
5. West region is the most profitable (1.08 lakh), Central is the lowest (39.7K).

## Fi
