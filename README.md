# 📊 Business Sales Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Domain](https://img.shields.io/badge/Domain-Data%20Science%20%26%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Internship](https://img.shields.io/badge/Internship-Future%20Interns-purple)

---

## 🚀 Project Overview

This project was developed as part of my **Data Science & Analytics Internship at Future Interns**.  
The objective was to analyze business sales data and design a **professional, interactive Power BI dashboard** that enables stakeholders to understand performance, identify trends, and make **data-driven decisions**.

The dashboard focuses on **business storytelling**, transforming raw data into actionable insights rather than just numbers.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard design & visualization  
- **Python (Pandas)** – Data cleaning & preprocessing  
- **DAX (Data Analysis Expressions)** – KPI calculations  
- **CSV / Excel** – Dataset format  

---

## 🎯 Business Objectives

This dashboard answers key business questions such as:

- What is the overall **revenue, profit, and order volume**?  
- How do **sales and profits trend over time**?  
- Which **categories and sub-categories** drive the most revenue?  
- Which **regions and states** perform best?  
- How does **sales compare with profit** across categories?  
- Which **customer segments** contribute the most revenue?  

---

## 🖼️ Dashboard Pages Overview

### 🔹 Page 1: Sales Performance Overview

![Sales Performance Overview](Screenshots/PAGE1.png)

**Purpose:**  
Provides top-level management with a quick snapshot of overall business performance.

**Key KPIs & Visuals:**
- Total Revenue  
- Total Orders  
- Net Profit  
- Units Sold  
- Average Order Value (AOV)  
- Monthly Revenue & Profit Trends (Year-wise)  
- Category-wise Revenue Share  
- Regional Revenue Distribution  
- Year slicer for dynamic filtering  

---

### 🔹 Page 2: Detailed Sales & Profit Analysis

![Detailed Sales Analysis](Screenshots/PAGE2.png)

**Purpose:**  
Designed for analysts and operations teams to explore deeper insights.

**Key Visuals:**
- Top States by Revenue  
- Revenue by Customer Segment  
- Geographic Revenue Distribution (U.S. Map)  
- Daily Revenue Trend Analysis  

---


## 📐 Key DAX Measures Used

```DAX
Total Revenue = SUM(Sales[Sales])

Total Orders = DISTINCTCOUNT(Sales[Order_ID])

Net Profit = SUM(Sales[Profit])

Units Sold = SUM(Sales[Quantity])

AOV = DIVIDE([Total Revenue], [Total Orders])
```

---

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop** – Dashboard creation & visualization  
- **Python (Pandas)** – Data cleaning & preprocessing  
- **CSV / Excel Dataset**  
- **DAX (Data Analysis Expressions)** – KPI calculations  

---

## 🔍 Key Insights & Findings

- The **South region** emerged as the top-performing region, contributing the highest share of total revenue.
- **Technology** was the leading product category, generating the maximum sales and profit.
- A clear **seasonal sales pattern** was observed, with **Q3 showing peak performance** across multiple years.
- **Corporate and Consumer segments** contributed the majority of revenue, highlighting their importance for business growth.
- Several states consistently outperformed others, indicating strong regional market demand.
- Despite high sales in some categories, **profit margins varied**, emphasizing the need to focus on profitability along with revenue.

---

## 🙏 Acknowledgements

I would like to express my sincere gratitude to **Future Interns** for providing the opportunity to work on this project.  
Their guidance, mentorship, and structured internship program played a vital role in enhancing my analytical and visualization skills.

---

## ✍️ Author

**Ajay Ugale**  
Data Science & Analytics Intern – Future Interns
