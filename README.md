# 👥 HR Analytics Dashboard
---

## 📎 Dashboard Preview

📄 **[Click here to view the full dashboard — HR Analytics Dashboard.png](https://github.com/mohamed1710-1998/Hr-analytics-dashboard/blob/main/hr-analytics-dashboard.png)**

---

## 🧩 Project Overview

An interactive Power BI dashboard designed to give HR teams and management a comprehensive view of **workforce composition, salary distribution, hiring trends, and departmental headcount** across multiple cities and employee groups.

The dashboard supports dynamic filtering by **Gender, City, Marital Status, and Time Period** — enabling data-driven HR decisions at both strategic and operational levels.

---

## 🎯 Business Questions Answered

- What is the total headcount and salary distribution across the organization?
- How does salary compare between Full Time and Part Time employees across groups?
- What are the hiring trends year over year?
- How is the workforce distributed by education level?
- Which departments have the highest headcount per city?
- How does gender and marital status break down across the workforce?

---

## 📌 Key KPIs

| Metric | Value |
|---|---|
| 👥 Total Employees | **1,766** |
| 💰 Total Salary | **$168M** |
| 👩 Female Employees | **862** |
| 👨 Male Employees | **904** |

---

## 📄 Dashboard Components

### 🔢 KPI Cards (Top Left)
- Total Employees: **1,766**
- Sum of Salary: **$168M** (shown across multiple KPI tiles)
- Marital Status breakdown: **Divorced \| Married \| Single**

### 📊 Salary By Group
Grouped bar chart comparing **Full Time vs Part Time** salary across 4 groups:
- Group D | Group A | Group C | Group B
- All groups hover around **$40M** range with consistent Full Time dominance

### 📈 Hires By Year
Line chart showing annual hiring volume (2013–2018):

| Year | Hires |
|---|---|
| 2013 | 301 |
| 2014 | 287 |
| 2015 | 319 |
| 2016 | 253 |
| 2017 | 293 |
| 2018 | 313 |

> 📉 2016 was the lowest hiring year — 2015 and 2018 were peak years

### 🍩 Headcount by Education
Donut chart showing education level distribution:

| Education | Count | % |
|---|---|---|
| Bachelor | 461 | 26.10% |
| Masters | 460 | 26.05% |
| College | 432 | 24.46% |
| Doctor | 413 | 23.39% |

> Workforce is evenly distributed across all education levels

### 🏢 Headcount by Department & City
Multi-city bar chart across 16 departments broken down by:
**Houston \| Los Angeles \| New York City \| Seattle**

Top departments by total headcount:
- Quality Assurance, Tech Support, Sales & Marketing, Human Resources

### 🎛️ Slicers & Filters
- **Time filter**: Last N periods
- **Gender**: Female / Male
- **City**: Houston / Los Angeles / New York City / Seattle
- **Page**: Overview tab navigation

---

## 🔍 Key Insights

- 👨 **Male employees (904)** slightly outnumber females (862) — nearly balanced workforce
- 📅 **2016 saw the lowest hiring** (253) — possible budget cut or restructuring
- 🎓 Education is **evenly spread** across all 4 levels — no dominant qualification tier
- 💼 **Full Time employees** consistently drive higher salary totals across all groups
- 🏙️ Headcount is distributed across **4 major US cities** with no single dominant location

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Microsoft Excel** | Data source & preparation |
| **Power BI Desktop** | Data modeling, DAX measures, visualization |
| **DAX** | Headcount, salary aggregations, time-based filtering |
| **Power Query** | Data transformation & loading |

---

## 📂 Repository Structure

```
hr-analytics-dashboard/
│
├── hr-analytics-dashboard.pbix           # Power BI report file
├── hr-analytics-dashboard.png            # Full dashboard preview (png)
├── Human Resources.CSV                   # Source dataset
└── README.md                             # Project documentation
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open with **Power BI Desktop** (free — download from Microsoft)
3. Use the filters at the top to slice by **Gender** or **City**
4. Adjust the time period slicer to explore hiring trends
5. To preview without Power BI — open the PDF file

---

## 👤 Author

**Mohamed Samir**
- 💼 [LinkedIn](https://www.linkedin.com/in/mohamed-samir-gaber/)
- 📧 mohamed171019988@gmail.com

---

*Dataset: HR Analytics dataset used for workforce analysis and BI demonstration*
