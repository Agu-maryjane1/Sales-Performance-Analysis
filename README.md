# Sales Performance Analysis: Abstract

## Context  
This project analyzes sales data from a supermarket with branches in three different cities. The dataset includes information on products sold, customer types, payment methods, and the amount spent, giving a full picture of sales activities over time.

## Problem Statement  
The supermarket operates across multiple cities and offers a wide range of products to a diverse customer base. However, without proper data analysis, the company lacks insight into key performance areas such as product sales trends, customer preferences, revenue distribution, and pricing efficiency. This makes it challenging to make informed decisions about inventory management, marketing strategies, and customer targeting.

## Goal  
The aim is to find useful patterns in customer behavior, top-selling products, and how sales change over time. This includes identifying the best-performing product lines, monthly sales trends, and areas where the business can improve. The results can help the business make better decisions, such as which products to stock more, how to target different types of customers, and when to plan sales or promotions. This helps improve sales, customer satisfaction, and overall business performance.

## Methods / Tools  
This analysis was done using **Python** with **Pandas** for data handling, and **Seaborn** and **Matplotlib** for visualizations. Techniques used include grouping, pivot tables, and time-based analysis to look at revenue, quantity sold, and profit.

---

## Results / Insights  

### 1. Which city or branch performs best in sales?  
- Branch C (Naypyitaw City) produces the highest revenue, making it the best-performing branch.  

### 2. Which product lines are selling the most? (By Quantity and by Revenue)  
- **By Quantity**: Electronic accessories are the most popular, while Health and Beauty is the least.  
- **By Revenue**: Food and Beverages generates the most revenue, likely due to higher prices.  

**Insight**: Hair and Beauty remains the lowest in both categories, suggesting a need for advertisements and promotions.  

### 3. What hours, days, or months bring the most revenue?  
- **Months**: January records the highest revenue. Daily trends show mid-month sales spikes, possibly linked to salary payments.  
- **Days**: Saturdays bring in the highest revenue, followed by Tuesdays.  
- **Hours**: Evenings (7 PM) record the most customer visits.  

**Insight**: Promotions during weekdays and working hours, plus delivery options (e.g., food and beverages), could boost sales.  

### 4. Who are the customers (Gender, Customer Type) and what do they buy?  
- **Members**:  
  - Females buy more fashion accessories, food & beverages, home & lifestyle, and sports & travel.  
  - Males buy more electronics and health & beauty products.  
- **Normal Customers**:  
  - Females buy more fashion accessories, food & beverages, and electronics.  
  - Males buy more sports & travel, and health & beauty.  
  - Both buy home & lifestyle at the same rate.  

**Insight**:  
- Males buy fewer fashion accessories and food & beverages.  
- Females buy fewer health & beauty products.  
- Marketing should target these gaps with gender-focused campaigns.  

### 5. What is the average customer rating per product line or branch?  
- **Product lines**:  
  - Highest: Food & Beverages (7.1), Fashion Accessories (7.02), Health & Beauty (7.00).  
  - Lowest: Home & Lifestyle (6.8), Sport & Travel (6.91), Electronics (6.92).  
- **Branches**:  
  - Highest: Naypyitaw (7.07), Yangon (7.02).  
  - Lowest: Mandalay (6.8).  

**Insight**: Investigations needed for low-rated product lines and Mandalay branch, possibly via customer satisfaction surveys.  

### 6. What are the top payment methods used?  
- Customers prefer **E-wallet** and **cash** over credit cards, likely due to convenience.  

### 7. Checking the gross profit across all product lines  
- Products have **moderate margins and profits** across the board, preventing low profits and avoiding overpricing.  

---

## Key Takeaways  
- **Branch C (Naypyitaw)** generates the highest revenue.  
- **Hair and Beauty** products underperform and need targeted promotions.  
- **Gender-based marketing** can drive more sales (e.g., male-focused ads for fashion and F&B, female-focused for health & beauty).  
- **Weekday deals and delivery services** could increase sales.  
- **Branch B (Mandalay)** and certain product lines need quality/customer experience reviews.  
- **E-wallets and cash** are the preferred payment methods.  
- Profit margins are stable, avoiding risks of overpricing or low profitability.  
