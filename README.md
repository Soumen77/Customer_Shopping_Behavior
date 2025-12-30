# 📊 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900+ purchases** across diverse product categories.  
The objective is to uncover actionable insights related to **customer segmentation, spending patterns, subscription behavior, discount impact, and product performance** to support data-driven business decisions.

The project follows an **end-to-end data analytics workflow** using **Python, SQL, and Power BI**.

---

## 🗂️ Dataset Summary
- **Total Records:** 3,900  
- **Total Features:** 18  

### Customer Information
- Age  
- Gender  
- Location  
- Subscription Status  

### Purchase Details
- Item Purchased  
- Category  
- Purchase Amount  
- Season  
- Size  
- Color  

### Behavioral Attributes
- Discount Applied  
- Previous Purchases  
- Purchase Frequency  
- Review Rating  
- Shipping Type  

### Data Quality
- Identified **37 missing values** in the `review_rating` column
- Missing values handled using **median imputation by product category**

---

## 🐍 Exploratory Data Analysis (Python)
Tools & Libraries:
- Python
- Pandas
- NumPy

### Key Steps:
- Data loading, inspection, and statistical analysis (`df.info()`, `df.describe()`)
- Standardized column names using **snake_case**
- Handled missing review ratings using **median imputation**
- Feature engineering:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns after validation
- Exported cleaned dataset to **PostgreSQL** for SQL analysis

---

## 🧮 Data Analysis (SQL)
Performed advanced SQL queries to answer key business questions:

- Revenue comparison by **gender**
- Spending analysis for **subscribers vs non-subscribers**
- Identification of **high-spending customers**
- Products are highly dependent on **discounts**
- Top 5 products by **average review rating**
- Purchase amount comparison across **shipping types**
- Customer segmentation:
  - New
  - Returning
  - Loyal
- Top 3 most purchased products per category
- Revenue contribution by **age group**
- Relationship between **repeat purchases and subscription status**

---

## 📊 Dashboard Development (Power BI)
Built an **interactive Power BI dashboard** to visualize key insights:
- Revenue trends by customer segment
- Product performance and purchase behavior
- Subscription vs non-subscription analysis
- Impact of discounts and shipping types

The dashboard enables both **technical and non-technical stakeholders** to explore insights easily.

---

## 💡 Key Business Insights & Recommendations
- Enhance **subscription models** with exclusive benefits
- Introduce **loyalty programs** to convert returning customers into loyal customers
- Optimize discount strategies to balance growth and profitability
- Promote **high-performing and highly-rated products**
- Focus marketing efforts on **high-revenue age groups** and **express shipping customers**

---

## 🛠️ Tools & Technologies Used
- **Python** (Pandas, NumPy)
- **SQL**
- **Power BI**
- **Excel (for validation & exploration)**

---
