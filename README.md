# Walmart Weekly Sales Analysis — Python & Pandas

## Project Overview

This project analyzes Walmart weekly sales data using Python and Pandas to identify sales performance, store-level trends, variability, and business insights.

The project is being developed step by step while learning Pandas and applying each concept to a real-world sales dataset.

---

## Dataset

- **Dataset:** Walmart Weekly Sales
- **Records:** 421,570
- **Tools:** Python, Pandas, Google Colab

### Key Fields

- Store
- Date
- Weekly_Sales
- IsHoliday
- Dept
- Year
- Month

---

# Lessons

## Lesson 1 — Data Understanding

Covered foundational Pandas techniques for understanding and inspecting the dataset.

### Concepts Practiced

- Loading data
- Inspecting DataFrame structure
- Understanding columns and data types
- Viewing sample records
- Basic dataset exploration
- Data preparation for analysis

---

## Lesson 2 — Store Sales Analysis

Focused on evaluating store-level sales performance and consistency.

### Analysis Performed

- Total sales by store
- Average weekly sales by store
- Maximum weekly sales
- Top and bottom performing stores
- Store-year sales performance
- Sales variability using standard deviation
- Sales gap analysis
- Coefficient of Variation (CV)
- Negative-sales record analysis
- High-sales and relatively stable stores

### Key Findings

- **Store 20** recorded the highest average weekly sales at **29,508.30**.
- **Store 5** recorded the lowest average weekly sales at **5,053.42**.
- **Store 14** had the highest weekly sales variability with a standard deviation of **36,911.12**.
- **Store 5** had the lowest weekly sales variability with a standard deviation of **8,068.22**.
- **Store 6** had the lowest CV among the high-sales stores analyzed, at **1.08**.
- **Store 35** had the highest number of negative-sales records, with **124** records.

---

## Business Questions

The project explores questions such as:

- Which stores generate the highest total sales?
- Which stores have the highest average weekly sales?
- Which stores have the lowest average weekly sales?
- Which stores have the highest sales variability?
- Which stores have the most consistent sales?
- Which stores combine strong sales with lower variability?
- Which stores have the highest frequency of negative-sales records?
- How does store performance change across years?

---

## Project Structure

```text
walmart-pandas-analysis/
│
├── Walmart_Sales_Analysis_Lesson_1_Data_Understanding.ipynb
├── Walmart_Sales_Analysis_Lesson_2_Store_Analysis.ipynb
└── README.md
