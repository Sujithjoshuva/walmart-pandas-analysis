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

### Lesson 3 — Department Analysis
- Analyzed total sales by department
- Analyzed average weekly sales by department
- Examined department sales variability
- Identified high-sales and relatively stable departments
- Calculated coefficient of variation (CV)
- Analyzed negative sales records
- Examined department sales by year
- Compared department performance across stores
- Identified the top department within each store
- Analyzed department dominance across stores
- Examined department sales changes between years

---

## Lesson 4 — Time-Based Sales Analysis

### Analysis Performed

- Compared total sales across years
- Examined year-over-year sales changes
- Analyzed monthly sales performance and average weekly sales by month
- Compared monthly sales patterns across years
- Identified the highest- and lowest-performing months by year
- Analyzed weekly sales patterns
- Identified the highest and lowest individual weekly sales records
- Compared holiday and non-holiday sales, using both total and average weekly sales
- Examined store sales trends across years and changes between 2010 and 2012
- Examined department sales trends across years
- Identified departments with the largest sales increases and decreases
- Identified departments with consistent year-over-year sales growth

### Key Insights

- **2011** recorded the highest total sales among the three years analyzed; total sales were lower in 2012 than in 2011.
- **July** had the highest combined monthly sales, while **January** had the lowest. December recorded the highest average weekly sales by month, and January the lowest.
- The dataset's weekly records fall on **Friday**, so a comparison across weekdays is not possible.
- The highest individual weekly sales record was **693,099.36** at Store 10, Department 72, on November 26, 2010, a holiday week. The lowest was **-4,988.94** at Store 28, Department 6, on October 8, 2010.
- Non-holiday weeks had higher total sales, while holiday weeks had higher average weekly sales in each year analyzed.
- Many stores recorded higher total sales in 2011 than in 2010, followed by lower sales in 2012. Store 38 had the largest increase between 2010 and 2012, while Store 14 had the largest decline.
- Department 92 recorded the highest total department sales in each of the three years shown.
- Department 87 had the largest sales increase between 2010 and 2012, while Department 72 had the largest decrease.
- Department 48 was the only department returned by the consistent-growth filter, with sales increasing in both 2010–2011 and 2011–2012.

### Notes

- Total sales and average weekly sales answer different questions; holiday comparisons should consider both measures.
- Negative weekly sales values and unusually small department totals may require further investigation.
- Lesson 4 is currently documented through Question 16. The next planned analysis is year-over-year sales change by department.

