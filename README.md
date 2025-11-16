# Customer Behavior Analysis Dashboard

A complete end-to-end data analysis project exploring customer shopping behavior using Python, SQL, and Power BI. This project is based on 3,900 purchase records and focuses on understanding spending trends, customer segments, product performance, and behavioral patterns.

---

## 1. Project Overview
This project analyzes customer shopping behavior across various demographics and product categories. The goal is to uncover insights related to:

- Spending patterns  
- Product preferences  
- Subscription and discount behavior  
- Customer segmentation  
- Revenue analysis  

The project includes data cleaning, SQL-based analysis using MySQL, and a final Power BI dashboard.

---

## 2. Dataset Summary

Dataset size:  
- 3,900 rows  
- 18 columns  

Key features:  
- Demographics: age, gender, location, subscription status  
- Purchase details: category, amount, season, size, color  
- Behavior: discounts, promo usage, review ratings, shipping type  
- History: previous purchases, frequency  

Missing data:  
- 37 missing values in the review_rating column (handled during preprocessing)

---

## 3. Exploratory Data Analysis (Python)

### Data Cleaning and Preparation
- Loaded data with pandas  
- Used df.info() and df.describe() for initial inspection  
- Imputed missing review_rating using the median per category  
- Standardized column names to snake_case  
- Removed redundant column promo_code_used  

### Feature Engineering
- Created age_group by binning ages  
- Calculated purchase_frequency_days  
- Ensured consistency between discount-related columns  

### MySQL Integration
- Cleaned DataFrame exported into a MySQL database  
- Used for structured SQL analysis  

---

## 4. SQL Analysis (Business Insights)

Key business questions addressed through SQL:

1. Revenue by gender  
2. High-spending customers who also use discounts  
3. Top 5 products based on average review rating  
4. Comparison of average spending between standard and express shipping users  
5. Revenue contribution and average spending of subscribers vs non-subscribers  
6. Products that rely heavily on discounts  
7. Customer segmentation: New, Returning, Loyal  
8. Top 3 most purchased products within each category  
9. Subscription likelihood among repeat buyers  
10. Revenue contribution by age group  

---

## 5. Power BI Dashboard

The Power BI dashboard includes:

- Customer demographics  
- Revenue and spending trends  
- Category-level performance  
- Review rating analysis  
- Subscription patterns  
- Discount usage patterns  
- Customer segmentation visuals  

Interactive filters allow analysis by gender, age group, category, season, and shipping type.

---

## 6. Key Insights and Recommendations

### Business Recommendations
- Increase subscription conversions by promoting unique benefits  
- Implement loyalty programs to convert returning buyers into loyal customers  
- Optimize discount strategy to maintain profitability  
- Highlight top-rated and best-selling products in marketing campaigns  
- Focus marketing efforts on high-value customer groups  

### Data Observations
- Express shipping users tend to spend more  
- Subscribers contribute significantly more revenue  
- Discount usage varies across product categories  
- Middle-aged groups are major contributors to total revenue  

---

### 6. Screenshots / Demos

Show what the dashboard looks like. - ![alt text](https://github.com/username/repo/assets/image.png)

Example: [![Dashboard Preview]()
