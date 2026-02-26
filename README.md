# Forage-Job-Simulation (Grocery Transactions 2019)
The objective of this analysis is to help the Quantium Grocery Data team get insights regarding their transactions during the year 2019: Customer behavior Products performance  Sales performance across the different.
## Overview
The workbook(shared via email) contains 2 sheets (Purchase behaviour, Transactions) for the year 2019.
1. Purchase Behaviour(sheet 1) - contains 3 columns (LYTLY_CARD_NBR, LifeStage, Premium Customers)
    - LYLTY_CARD_NBR: contains unique numbers that identify each customer
    - LifeStage: refers to the customer's current stage in life (retirees, mid-age, older, etc.)
    - Premium customers: contains the 3 customer categories (budget, mainstream, premium customer)
2. Transactions (sheet 2)- Contains transaction data of the purchases made for the year 2019.
    - It has 8 columns; column LYLTY_CARD_NBR links the two sheets to indicate which customer made the purchase.
    - Columns: Date, Store_NBR, LYLTY_CARD_NBR, TXN_ID, PROD_NBR, PROD_NAME, PROD_QTY, TOT_SALES.

<img width="1762" height="807" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/fe1bab82-ace2-46bb-a348-85ad2af1a3eb" />


## Questions that the analysis aims to answer
### Sales
1. What were the total sales made?
2. What’s the customer category with the highest sales?
3. What’s the Lifestage with the highest sales?
4. Which product category had the highest sales?
5. Which top 10 products had the highest sales volume?
6. The month with the highest sales?

## Data Source
- Forage Job simulation: [Download Here](https://www.theforage.com/simulations/quantium/data-analytics-rqkb)
- Complete workbook with analysis [download here](https://docs.google.com/spreadsheets/d/1Oze-Br03hHldSoHG1f8FhslT1wfHacLn/edit?usp=drive_link&ouid=118205423473191044596&rtpof=true&sd=true)
## Tools used
Excel;
  - Power Query for data cleaning.
  - Pivot tables for summarization.
  - Visualization.
## Data cleaning and preparation
- Changed the data type in the date from a general number to match the date format.
- Total sales from number to currency to help make the sum.
- Two columns were added.
    1. Product abbreviation: this represents the abbreviated names of the products 
    2. Categories: This contains the different categories of the abbreviated product names
- Pivot tables are used to summarize the data.

## Key findings
## Overview
1. Total sales made: **$1.9Million** in sales
2. Total quantity sold: **505.1K**
3. Total number of customers: **72.6K**
4. Total products sold: **264.8K**

### 1. What’s the customer category with the highest sales?
- Mainstream was the leading category with: $750, 745 in sales
- Budget: $676, 212 in sales
- Premium: $507,459 in sales
### 2. Which product category had the highest sales?
- The undefined category had the highest sales volume: **$566, 173**

### 3. What’s the Lifestage with the highest sales?
- Older Singles/Couples generated the highest sales among all lifestage segments, with sales amounting to: $402.4K
Insight:
    - Older customers are the strongest revenue drivers, suggesting loyalty and consistent purchasing behaviour.

### 4. Which month had the highest sales 
- Dec **$167,913**
    -This may be as a result of the festivities within this month that drove the sales to peak.
--
## Recommendations
1. During the festive season and different holidays, as seen in December.
    - The store could consider giving discounts and promotions to attract a larger number of customers.
2. To retain customers;
    - The store could consider using loyalty points that will encourage customers to shop, and later, the points can be used to purchase certain items.
3. For the products that had fewer sales;
    - The store could carry out a survey and determine why the products performed poorly. The questions should be MCQs to save time during analysis.
    - Review the pricing on the same product.




