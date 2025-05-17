# Target – Retail Operations and Performance Analysis Using SQL

This project explores the operations of Target’s Brazilian e-commerce business using SQL. With data spanning over 100,000 orders across multiple dimensions (orders, payments, products, reviews, geography), the goal is to generate actionable insights on customer behavior, sales trends, delivery efficiency, and payment patterns.

---

## 📊 Problem Statement

Target Brazil aims to optimize order logistics, improve customer satisfaction, and grow sales. As a data analyst, I explored the data using SQL to uncover patterns in order trends, delivery timelines, economic impact, and payment preferences from 2016 to 2018.

---

## 📁 Dataset Overview

The dataset consists of 8 interrelated tables:

- `orders.csv` – order status, purchase & delivery timestamps
- `order_items.csv` – price & freight details
- `customers.csv` – customer location details
- `payments.csv` – payment type and value
- `reviews.csv` – customer satisfaction and review scores
- `products.csv` – product characteristics
- `sellers.csv` – seller locations
- `geolocation.csv` – ZIP-level lat/lon

---

## 🛠️ Tools & Skills Used

- PostgreSQL / MySQL
- Subqueries, Joins, CTEs, Date functions
- Grouping, Aggregation, Window functions
- Data Storytelling
- EDA across temporal, geographical, and categorical dimensions

---

## 🔍 Analysis Highlights

1. **Initial Exploration**
   - Verified schema & datatypes across all 8 tables
   - Mapped order timestamps to date & time buckets
   - Counted distinct customers, cities, and states

2. **Order Trends**
   - Found a monthly growth pattern in orders (esp. in 2017–2018)
   - Identified that most orders were placed in the **afternoon (13–18h)**

3. **Geographical Performance**
   - São Paulo (SP), Rio de Janeiro (RJ), and Minas Gerais (MG) were top ordering states
   - Visualized order volume by state over time

4. **Economic Impact**
   - +18% rise in total order value from Jan–Aug 2017 to Jan–Aug 2018
   - Calculated state-wise total & avg `payment_value` and `freight_value`

5. **Delivery & Logistics**
   - Computed actual delivery time and deviation from estimated delivery
   - Ranked top 5 states by:
     - Fastest delivery
     - Highest/lowest avg freight cost
     - Delivery accuracy vs estimated date

6. **Payment Insights**
   - Most payments were made via **credit cards**
   - Majority of EMI-based purchases had **3–4 installments**

---

## 📌 Key Insights

- Afternoon is the peak order time in Brazil.
- Delivery speed varies drastically by state — targeted logistics planning is needed.
- Freight costs are notably high in northern states compared to southern ones.
- Reviews generally align with delivery speed — delays impact satisfaction.
- Credit card is the most trusted payment method in Brazilian e-commerce.

---

## 💡 Business Recommendations

- **Invest in last-mile logistics** in slower regions (e.g., AM, RR)
- Promote **multi-installment EMI plans** for higher-value products
- Use **fast-delivery performance as a differentiator** in major cities
- Build **geo-specific pricing strategies** for freight or promotions
- Track **review scores in sync with delivery delays** to improve satisfaction

---

## 📂 Files Included

- `Target_Retail_Analysis.sql` – SQL queries
- `ERD_Schema.png` – Dataset structure diagram
- (Optional) `Target_Report.pdf` – Business summary
- `README.md` – Project documentation

---

## 🔗 Links

- [Portfolio Project Page](https://www.datascienceportfol.io/varshilgandhi308)
- [GitHub Repo](https://github.com/varshilgandhi/Target-SQL-Retail-Operations-Analysis) 

---

## 🤝 Let’s Connect

Feedback & collaborations welcome! [LinkedIn](https://www.linkedin.com/in/varshil-gandhi-08470b200/)
