# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
End-to-end data analysis project using Python, SQL, and Power BI to analyze 3,900+ customer transactions. The goal is to uncover actionable insights into customer spending patterns, preferences, and engagement to support data-driven business decisions.

---

## 🎯 Business Problem Statement
A leading retail company wants to better understand its customers’ shopping behavior to improve **sales, customer satisfaction, and long-term loyalty**.

The company has observed changes in purchasing patterns across:
- Customer demographics  
- Product categories  
- Sales channels (online vs. offline)  

Management aims to identify key factors such as **discounts, reviews, seasonal trends, and payment preferences** that influence purchasing decisions and repeat buying behavior.

### ❓ Key Business Question
**How can the company leverage customer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

## 📊 Dataset Summary
- **Total Records:** 3,900  
- **Total Features:** 18  

### Key Attributes:
- **Demographics:** Age, Gender, Location  
- **Purchase Details:** Item, Category, Amount, Season  
- **Behavior:** Discounts, Promo Codes, Frequency, Ratings  
- **Customer Loyalty:** Previous Purchases, Subscription Status  

### Data Cleaning:
- Handled missing values in `review_rating` using median imputation  
- Standardized column names (snake_case)  
- Removed redundant columns (`promo_code_used`)  

---

## 🧪 Exploratory Data Analysis (Python)
Performed using **Pandas, NumPy, Matplotlib, Seaborn**

### Key Steps:
- Data cleaning & preprocessing  
- Handling missing values  
- Feature engineering:
  - Age group segmentation  
  - Purchase frequency conversion  

### Visualizations:
- Category-wise sales  
- Customer demographics  
- Purchase behavior trends  

---

## 🗄️ SQL Analysis (PostgreSQL)
Executed advanced SQL queries to extract business insights:

- Revenue contribution by gender  
- High-spending customers using discounts  
- Top-rated products  
- Shipping type vs purchase behavior  
- Subscriber vs non-subscriber comparison  
- Discount dependency by product  
- Customer segmentation (New, Returning, Loyal)  
- Top products by category  
- Repeat buyers vs subscription behavior  
- Revenue by age group  

---

## 📈 Power BI Dashboard
Developed an **interactive dashboard** to visualize key insights.

### Dashboard Features:
- KPI Cards: Total Revenue, Avg Purchase Value, Total Customers  
- Category-wise sales distribution  
- Customer segmentation insights  
- Purchase trends by season  
- Payment method preferences  
- Filters for dynamic analysis (Gender, Category, Season)  

---

## 🔑 Key Insights
- A significant portion of revenue is driven by **repeat and loyal customers**  
- **Subscribers show higher average spending** compared to non-subscribers  
- Discounts increase purchase volume but may impact profit margins  
- Certain product categories dominate overall sales  
- Specific age groups contribute more to revenue and frequent purchases  

---

## 💡 Business Recommendations
- **Boost Subscriptions:** Introduce exclusive benefits to increase retention  
- **Loyalty Programs:** Convert returning customers into loyal customers  
- **Optimize Discounts:** Balance between sales growth and profitability  
- **Product Positioning:** Promote top-rated and high-selling products  
- **Targeted Marketing:** Focus on high-value customer segments  

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **SQL:** PostgreSQL  
- **Visualization:** Power BI  

---

## 🚀 Conclusion
This project demonstrates how end-to-end data analysis—from data cleaning and SQL querying to visualization and business reporting—can help organizations **understand customer behavior and drive strategic decisions**.
