# Service and Operational Optimization of AMRIT Pharmacy at KGMU

## Business Data Management – Capstone Project (Final Report)

**Author:** Neeraj Kumar  
**Program:** IIT Madras – Online BS Degree Program  
**Email:** 23F2002096@ds.study.iitm.ac.in  
**Submission Date:** 03 October 2025  

---

## Project Overview
Amrit Pharmacy operates within King George’s Medical University (KGMU), Lucknow, and plays a critical role in providing affordable and accessible medicines by sourcing directly from manufacturers. With a growing customer base and high transaction volume, the pharmacy faces operational challenges such as stock shortages, demand fluctuations, and billing inefficiencies.

This capstone project applies data-driven analysis to study sales patterns, inventory behavior, and revenue distribution, and proposes actionable recommendations to improve service efficiency and operational performance.

---

## Objectives
- Analyze daily, weekly, and monthly sales trends  
- Identify high-demand and slow-moving medicines  
- Perform ABC inventory segmentation  
- Study revenue contribution, discounts, and profitability  
- Recommend operational and inventory optimization strategies  

---

## Dataset Description
- **Time Period:** 01 March 2025 – 31 May 2025  
- **Total Records:** 56,281 transactions  
- **Attributes:** 21 cleaned and processed fields  
- **Data Source:** System-generated sales data from Amrit Pharmacy, KGMU  

### Key Attributes
- Date  
- Item Name  
- Item Category  
- Pack Size  
- Quantity Sold  
- MRP  
- Selling Price  
- GST  
- Discount  
- Sale Value  
- Payment Type  

---

## Data Processing & Preparation
- Removal of null values and duplicate records  
- Aggregation of daily sales for each item  
- Creation of derived fields such as **Total Quantity Sold**  
- Separation of numerical and categorical features  
- Descriptive statistical summarization using Pandas  

---

## Analysis Techniques
- **Descriptive Statistics:** Mean, median, standard deviation, skewness  
- **Trend Analysis:** Daily, weekly, and monthly sales patterns  
- **ABC Segmentation:** Product classification based on revenue contribution  
- **Visualization:** Line and bar charts using Matplotlib  

---

## Key Findings
- Sales peak on **Mondays and Tuesdays**; lowest sales occur on **Sundays**  
- Several medicines show stable daily demand, while others exhibit high variability  
- **Category A products (237 items)** contribute nearly **70–80% of total revenue**  
- **Category C products (790 items)** show low turnover and high overstocking risk  
- General Medicine is the highest revenue-generating category  
- High sales volume does not always translate into high profit margins  

---

## Recommendations
- Prioritize **Category A** products for strict monitoring and replenishment  
- Minimize overstocking of **Category C** items to reduce expiry-related losses  
- Implement **data-driven demand forecasting** models  
- Optimize discount strategies to balance sales growth and profitability  
- Promote digital payments to improve billing efficiency  
- Align staff scheduling with high-demand weekdays  

---

## Tools & Technologies
- **Language:** Python  
- **Libraries:** Pandas, Matplotlib  
- **Data Format:** Excel (.xlsx)  

---

## Repository Structure
