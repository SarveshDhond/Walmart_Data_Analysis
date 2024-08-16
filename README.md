# Walmart Sales Data Analysis - SQL
Exploratory Data Analysis of Walmart sales data to understand sales trends, product performance, and customer behavior patterns. 

#### DATA SOURCE
[Kaggle.com](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)

#### PROJECT AIM
The project aims to gain valuable insight into the sales data of Walmart to understand the different factors that affect sales of the different branches in specific cities. 

## SCHEMAS
The following dataset was obtained from the Kaggle Walmart Sales Forecasting Competition. This dataset contains sales transactions from three different branches of Walmart, respectively located in Mandalay, Yangon, and Naypyitaw. The raw data contains 17 columns and 1000 rows.

|  COLUMNS       |DATA TYPES|
|----------------|----------|
| Invoice_id     | VARCHAR  |
| branch         | VARCHAR  |
| city           | VARCHAR  |
| customer_type  | VARCHAR  |
| gender         | VARCHAR  |
| product_line   | VARCHAR  |
| unit_price     | DECIMAL  |
| quantity       | INTEGER  |
| vat            | DECIMAL  | 
| total          | DECIMAL  |
| date           | DATETIME |
| time           | TIME     |
| payment_method | VARCHAR  |
| cogs           | DECIMAL  |
| gross_margin   | DECIMAL  |
| gross_income   | DECIMAL  |
| rating         | DECIMAL  |
| Time_of_day    | VARCHAR  |
| Day_name       | VARCHAR  |
| Month_name     | VARCHAR  |
| Months_name    | VARCHAR  |

## TYPES OF ANALYSIS
- Product Analysis
- Sales Analysis
- Customer Analysis


## STEPS TAKEN
1. Data collection
   - Getting raw data from the source
   - Building a database and table
   - importing raw data into that table

2. Cleaning and Preparing
   - Filtering out Null values
   - Adding new columns

3. Exploratory Data Analysis (EDA)
   - Answering business-related questions

## BUSINESS QUESTIONS AND ANSWERS


### Generic Question

1. How many unique cities does the data have?
2. In which city is each branch?



### Product

1. How many unique product lines does the data have?
2. What is the most common payment method?
3. What is the most selling product line?
4. What is the total revenue by month?
5. What month had the largest COGS?
6. What product line had the largest revenue?
7. Which is the city with the largest revenue?
8. What product line had the largest VAT?
9. Which branch sold the most product?
10. What is the most common product line by gender?
11. What is the average rating of each product line?


### Sales

1. Which of the customer types brings the most revenue?
2. Which city has the largest tax percentage / VAT (Value Added Tax)?
3. Which customer type pays the most in VAT?


### Customer

1. How many unique customer types does the data have?
2. How many unique payment methods does the data have?
3. What is the most common customer type?
4. What is the gender of most of the customers?
5. What is the gender distribution per branch?
6. Which time of the day do customers give the most ratings?
7. Which day of the week has the best average ratings?
8. Which day of the week has the best average ratings per branch?
