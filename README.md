# Veda-Technology-Task-18
#  Region Performance Analysis — Superstore Dataset

**> Task 18 · Data Analytics Track · VEDA Technology Internship**

A data analysis project comparing **sales and profit performance across regions** using the Sample Superstore dataset, built with Excel (PivotTables & PivotCharts).

---
##  Overview

| | |
|---|---|
| **Task** | Region Performance |
| **Objective** | Compare sales across regions |
| **Skill practiced** | Grouping & comparison |
| **Tools** | Microsoft Excel (PivotTable, PivotChart) |
| **Dataset** | [Sample Superstore](https://www.tableau.com/) — 9,994 orders, 21 columns |
| **Author** | Akshat Srivastava |

---
##  Objective

Compare total **Sales** and **Profit** across the four regions in the dataset — **West, East, Central, and South** — to identify top and bottom performing regions, and rank them accordingly.

---

##  Repository Structure

```
├── data/
│   └── Sample - Superstore.csv        # Raw dataset (9,994 rows)
├── Sample - Superstore.xlsx           # Excel workbook with PivotTable + PivotChart
├── Region Performance Report.pdf      # Final formatted report
└── README.md
```
---

##  Approach

1. Loaded the Superstore dataset into Excel.
2. Built a **PivotTable** grouping `Region` in Rows, with `Sum of Sales` and `Sum of Profit` in Values.
3. Sorted regions by total sales (highest → lowest) to rank performance.
4. Created a **Clustered Column PivotChart** to visually compare Sales vs Profit per region.
5. Summarized findings in a written report.

---

##  Results

| Rank | Region  | Total Sales (₹) | Total Profit (₹) |
|:----:|---------|-----------------:|-------------------:|
| 1 | **West**    | 7,25,458 | 1,08,418 |
| 2 | East        | 6,78,781 | 91,523   |
| 3 | Central     | 5,01,240 | 39,706   |
| 4 | South       | 3,91,722 | 46,749   |

**Grand Total:** ₹22,97,201 Sales · ₹2,86,397 Profit
---
##  Key Insights
- **West** is the top-performing region in both sales and profit.
- **East** is a close second across both metrics.
- **Central** has the third-highest sales but the **lowest profit** of all regions.
- **South**, despite having the lowest sales, earns more profit than Central — suggesting better cost efficiency relative to revenue.
---
##  Tools Used
- Microsoft Excel — PivotTable, PivotChart, SUMIF formulas
- Sample Superstore public dataset
---
##  Deliverables
-  Region Summary (PivotTable)
- Bar Chart (Sales vs Profit by Region)
-  PDF Report with insights and conclusion
---

*Part of a 45-day Data Analytics internship program — Day 18/45.*
