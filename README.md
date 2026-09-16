# 📊 Sales & Business Performance Analysis

<img width="2017" height="1032" alt="Image" src="https://github.com/user-attachments/assets/37837c8f-f146-4ba6-a5db-52e6e88e016a" />

## 📌 Project Overview

This project analyzes a **1,000-record business sales dataset** to uncover insights into revenue, profit, sales performance, product categories, sales channels, customer satisfaction, marketing spend, and discount strategies.

The analysis was carried out using **Microsoft Excel**, with the goal of answering practical business questions and providing data-driven recommendations that can support business decision-making.

---

## 🎯 Business Objectives

The analysis was designed to answer five key business questions:

1. **Which region generates the highest total revenue and profit?**
2. **Which salesperson has the best overall performance based on revenue, profit, and units sold?**
3. **Which product category is the most profitable, and which category generates the highest revenue?**
4. **How does the sales channel affect revenue, profit, and customer satisfaction?**
5. **What is the relationship between discount percentage, marketing spend, and business performance such as revenue and profit?**

---

## 🗂️ Dataset

The dataset contains **1,000 business transactions** and 11 variables:

| Column                | Description                                   |
| --------------------- | --------------------------------------------- |
| Region                | Geographical region                           |
| Salesperson           | Sales representative responsible for the sale |
| Revenue               | Revenue generated from the transaction        |
| Profit                | Profit generated from the transaction         |
| Units_Sold            | Number of units sold                          |
| Customer_Satisfaction | Customer satisfaction rating                  |
| Marketing_Spend       | Marketing expenditure                         |
| Discount_Percentage   | Discount applied to the transaction           |
| Product_Category      | Category of the product sold                  |
| Sales_Channel         | Channel used for the sale                     |
| Order_Processing_Time | Time taken to process the order               |

---

## 🛠️ Tools & Techniques

### Tools

* **Microsoft Excel**
* Excel PivotTables
* Excel Charts
* Excel formulas
* Data Analysis ToolPak

### Analytical Techniques

* Descriptive statistics
* Data aggregation
* PivotTable analysis
* Correlation analysis
* Data visualization
* Business interpretation

---

# 📈 Key Findings

## 1. Overall Business Performance

The dataset generated approximately:

* 💰 **Total Revenue:** 107.3 million
* 📈 **Total Profit:** 24.0 million
* 📦 **Total Units Sold:** 498,594

This provides an overall view of the company's sales volume, revenue generation, and profitability.

---

## 2. Regional Performance

The analysis showed different strengths across regions.

| Region |    Revenue |        Profit |
| ------ | ---------: | ------------: |
| North  | 29,373,063 |     6,027,453 |
| West   | 28,628,148 | **7,084,145** |
| East   | 25,438,195 |     5,352,301 |
| South  | 23,876,202 |     5,509,219 |

### Insight

* **North** generated the highest total revenue.
* **West** generated the highest total profit.

This demonstrates that the region generating the most revenue is not necessarily the region generating the most profit.

---

## 3. Salesperson Performance

Revenue performance by salesperson was analyzed to identify differences in sales contribution.

| Salesperson |        Revenue |
| ----------- | -------------: |
| Alice       | **22,945,316** |
| Eve         |     22,490,262 |
| Bob         |     22,209,168 |
| Charlie     |     21,599,594 |
| David       |     18,071,268 |

### Insight

**Alice recorded the highest total revenue** among the salespeople in the dataset.

The results can help management identify high-performing sales practices and areas where additional support or training may be useful.

---

## 4. Product Category Performance

Product categories were analyzed from both revenue and profit perspectives.

* 🏆 **Electronics** generated the highest revenue: **23,172,817**
* 💰 **Furniture** generated the highest profit: **4,951,074**

### Insight

The category with the highest revenue was different from the category with the highest profit.

This highlights the importance of evaluating products using both **sales volume/revenue and profitability**, rather than revenue alone.

---

## 5. Sales Channel Performance

The dataset contains three sales channels:

* Retail
* Online
* Wholesale

| Sales Channel |        Revenue |        Profit | Avg. Customer Satisfaction |
| ------------- | -------------: | ------------: | -------------------------: |
| Retail        | **36,379,664** | **8,250,872** |                   **3.02** |
| Online        |     35,655,573 |     8,189,119 |                       2.96 |
| Wholesale     |     35,280,371 |     7,533,127 |                       2.92 |

### Insight

Retail recorded the highest revenue, profit, and average customer satisfaction among the three channels in this dataset.

---

# 📊 Marketing Spend, Discounts & Business Performance

One of the main objectives of the project was to determine whether **discount percentage and marketing spend** were associated with revenue and profit.

Correlation analysis produced the following results:

| Variables                 | Correlation |
| ------------------------- | ----------: |
| Discount % & Revenue      |       0.014 |
| Discount % & Profit       |       0.005 |
| Marketing Spend & Revenue |      -0.015 |
| Marketing Spend & Profit  |      -0.035 |

### Insight

The correlations are all very close to zero, indicating **very weak linear relationships** between these variables and revenue or profit within this dataset.

Multiple regression was also identified as an appropriate technique for examining the combined relationship between:

**Revenue = Marketing Spend + Discount Percentage**

and

**Profit = Marketing Spend + Discount Percentage**

The analysis suggests that marketing spend and discount percentage, considered by themselves, do not strongly explain business performance in this dataset.

> **Important:** Correlation identify statistical relationships; they do not by themselves establish causation.

---

# 💡 Business Recommendations

Based on the analysis, the following recommendations were developed:

### 1. Focus on high-performing regions

Management should examine the strategies and practices contributing to the strong revenue performance of the **North** region and strong profit performance of the **West** region.

### 2. Learn from high-performing salespeople

The business can examine the practices of high-revenue salespeople, particularly **Alice**, and use these insights to support sales performance across the wider team.

### 3. Balance revenue with profitability

Since the highest-revenue product category was different from the highest-profit category, management should consider **both revenue and profit** when making product decisions.

### 4. Strengthen the Retail channel

Retail demonstrated strong performance across revenue, profit, and customer satisfaction. Management should continue monitoring and developing this channel while investigating opportunities to improve Online and Wholesale performance.

### 5. Review discount strategies

Because discount percentage showed almost no linear relationship with revenue or profit, the company should avoid assuming that larger discounts automatically produce better business results.

Discounts could instead be evaluated based on specific products, customers, or sales periods.

### 6. Evaluate marketing effectiveness

Marketing spend also showed a very weak relationship with revenue and profit.

The business should evaluate marketing activities based on measurable outcomes and determine which campaigns or activities provide meaningful returns.

### 7. Continue using data-driven decision-making

Other variables, including units sold, customer satisfaction, product category, region, salesperson, and sales channel, should also be investigated to better understand the factors influencing business performance.

---

# 📁 Project Structure

```text
Sales-Business-Performance-Analysis/
│
├── README.md
│
├── Dataset/
│   └── sales_dataset.xlsx
│
├── Analysis/
│   └── sales_analysis.xlsx
│
├── Dashboard/
│   └── sales_dashboard.xlsx
│
└── Documentation/
    └── project_report.pdf
```

*The folder structure can be adjusted to match the files included in the repository.*

---

# 📌 Project Outcome

This project demonstrates how Excel can be used to move from **raw business data → analysis → insights → recommendations**.

The analysis highlights the importance of looking beyond individual metrics. Revenue, profit, customer satisfaction, sales channels, product categories, and other business factors can provide different perspectives on performance.

The project also demonstrates the use of **correlation and regression** to investigate relationships between business variables.

---

## 👤 Author

**Olamide**

Aspiring Data Analyst | Excel | Power BI | Data Analytics

---

⭐ If you find this project useful, feel free to explore the repository and connect with me via email: Samson5olamide@gmail.com
