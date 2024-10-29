# Customer Shopping Preferences Analysis

## Project Overview
This project analyzes customer shopping preferences to help a business understand its customer base, optimize product offerings, and improve marketing strategies. Using Python, we explore various patterns in the dataset, including demographic insights, spending habits, product popularity, seasonal trends, and the impact of discounts on purchases.

## Objectives
- To identify key customer demographics and spending patterns.
- To determine the most popular products and categories.
- To examine seasonal trends in customer spending.
- To assess the influence of discounts on customer purchasing behavior.

## Dataset
The dataset used in this analysis includes various customer attributes such as:
- **Age** and **Gender**
- **Purchase Amount (USD)**
- **Item Purchased** and **Category**
- **Location**, **Size**, and **Color** preferences
- **Review Rating**
- **Subscription Status**, **Payment Method**, and **Shipping Type**
- **Discount Applied** and **Promo Code Used**

## Analysis Summary

### 1. Demographic Insights
- **Age Distribution**: The age distribution is relatively balanced across all age groups, indicating no single age range dominates the customer base.
- **Gender Distribution**: There is a higher representation of male customers compared to female customers.

### 2. Spending Patterns
- **By Age**: Average spending fluctuates significantly across all age groups, with some isolated peaks, particularly around age 50. There is no clear pattern indicating higher spending concentrated in specific age ranges.
- **By Gender**: While both genders have similar spending patterns, females slightly outspend males on average.

### 3. Popular Products and Categories
- **Top Items**: Blouse, Jewelry, and Pants are among the most popular items.
- **Top Categories**: Clothing and Accessories dominate customer purchases.

### 4. Seasonal Trends
- **High-Spending Seasons**: Fall and winter see the highest spending, indicating potential for seasonal marketing campaigns during these periods.

### 5. Discount and Promotion Effects
- **Discount Usage**: 43% of purchases involve discounts, suggesting that promotions play a significant role in customer purchase decisions, though a majority of purchases are made without discounts.

## Recommendations
Based on the findings, the following recommendations are suggested:
1. **Target Marketing**: Focus on high-spending age groups (30-50), particularly in fall and winter seasons.
2. **Inventory Optimization**: Stock popular items like Blouses, Jewelry, and Pants to meet demand.
3. **Seasonal Promotions**: Plan targeted promotions for clothing and accessory items during peak seasons to maximize sales.
4. **Discount Strategy**: Continue offering discounts, as 43% of customers are influenced by them, but explore optimizing discount amounts for profitability.

## Dataset
The dataset used for this analysis is publicly available on Kaggle and can be found [here](./shopping_trends.csv).

## Python Codes
The Python Codes used for this analysis can be found in the [.ipynb file](./EDA_Sales_Analytics.ipynb).

## Technologies Used
- **Python**: Data manipulation and visualization
  - `Pandas` for data handling
  - `Matplotlib` for plotting
- **Google Colab**: For organizing and presenting the analysis
