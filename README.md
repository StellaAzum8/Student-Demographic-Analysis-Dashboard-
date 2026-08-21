# Student-Demographic-Analysis-Dashboard-


# Student Data Analysis Dashboard

**Power BI · DAX · Power Query**


![Image](https://drive.google.com/uc?export=view&id=1IsYiLxB_d34-Uqd8FhZzCdNPU8gTK9X6)
![Image](https://drive.google.com/uc?export=view&id=13H5V8GK7iuWccr2xpreiu0uncE7SqBem)


This Student Data Analysis Dashboard provides a comprehensive overview of a university's student population, focusing on key metrics such as academic level, financial allowances, community involvement, family background, and living arrangements. Here's a breakdown of the components and insights from the dashboard:

## Table of Contents
- [1. Header and Key Metrics](#1-header-and-key-metrics)
- [2. Demographics and Community Involvement by Level](#2-demographics-and-community-involvement-by-level)
- [3. Academic and Financial Overview](#3-academic-and-financial-overview)
- [4. Financial and Family Background Breakdown](#4-financial-and-family-background-breakdown)
- [5. Geographic and Housing Distribution](#5-geographic-and-housing-distribution)
- [6. Filters](#6-filters)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Skills Demonstrated](#skills-demonstrated)
- [Tools & Tech Stack](#tools--tech-stack)
- [How to Use](#how-to-use)
- [Contact](#contact)

---

## 1. Header and Key Metrics

- **Total Number of Students (4,696):** The dashboard summarizes the full student population captured in the dataset, giving a baseline scale for every other metric in the report.
- **Number of Courses Offered (14):** Reflects the academic breadth of the institution and provides context for how enrollment is distributed across departments.
- **Students with Both Parents (2,372):** Just over half the student body reports having both parents present, a figure worth cross-referencing against allowance and breadwinner-occupation data later in the report.
- **Minimum Age of Students (15):** Flags the youngest recorded student in the dataset — useful both as a demographic data point and as a quick check for data-entry outliers.
- **Average Monthly Allowance (₦69.35K):** Serves as the benchmark figure against which allowance by level, course, and breadwinner occupation can be compared throughout the dashboard.

## 2. Demographics and Community Involvement by Level

**Count of is_nigerian by Level (Donut Chart):**
This chart breaks the student population down by nationality across the four academic levels. 400-level students make up the largest share (39.18%, 1,840 students), followed by 300-level (20.91%), 200-level (20.51%), and Masters (19.4%). Because this split closely tracks overall level-wise enrollment, it suggests nationality is proportionally distributed rather than concentrated in any one level.

**Count of is_member_of_src by Level (Donut Chart):**
SRC (Student Representative Council) membership follows the exact same proportional pattern as nationality — 400-level leads, followed by 300, 200, and Masters. This consistency indicates that participation in student governance scales with cohort size rather than reflecting a particular level being more civically engaged than another.

**Count of is_chapel_worker by Level (Pie Chart):**
Religious/chapel worker involvement mirrors the same level-based distribution once again. Seeing this pattern repeat across three independent categorical variables (nationality, SRC membership, chapel worker status) is itself an insight — it confirms these attributes are evenly distributed across the population rather than skewed toward any specific level.

**Count of resumed_with_provision_bag by Level (100% Stacked Bar):**
This visual tracks how many students in each level resumed campus life with a provision bag. 400-level again leads at 1,840 students, reinforcing that this cohort is consistently the largest and most represented group across nearly every metric in the dashboard.

## 3. Academic and Financial Overview

**Total Number of Students by Course of Study (Pie Chart):**
Enrollment is split almost evenly across the six courses tracked — Industrial Chemistry, Mass Communication, Business Administration, Cyber Security, and two others — each landing within a tight 16.4%–17.1% band. This even spread suggests the institution enforces balanced admission quotas rather than allowing enrollment to concentrate around a small number of popular courses.

**Average Monthly Allowance by Level (100% Stacked Bar):**
300-level students report the highest average allowance (₦69.97K), narrowly ahead of 400-level (₦69.4K), Masters (₦69.18K), and 200-level (₦68.79K). The spread between the highest and lowest level is under ₦1.2K, indicating that financial support from home stays fairly consistent as students progress through their studies, rather than increasing sharply with seniority.

## 4. Financial and Family Background Breakdown

**Average Monthly Allowance by Breadwinner Occupation (Ranked List):**
Students whose breadwinner works as a **Doctor** (₦70,323.68) or **Businesswoman** (₦70,317.19) report the highest average allowances, while those with an **Engineer** as breadwinner report the lowest (₦68,314.69). Architects, Bankers, and Lecturers fall in between. The roughly ₦2K spread is modest but consistent, hinting that professional and business-owning households may provide marginally more discretionary support than salaried technical roles.

**Count of Breadwinner Parent Occupation (Treemap):**
This treemap maps the relative frequency of each occupation among students' breadwinners — Doctor, Businesswoman, Lecturer, Engineer, Banker, Trader, and Architect. The mix skews toward professional and white-collar occupations, painting a picture of the socioeconomic background typical of this student population.

**Average Monthly Allowance vs. Average Monthly Spent by Level:**
Comparing allowance received against amount spent shows spending tracks closely with allowance at every level, with little to no surplus visible in the aggregate totals. 400-level shows the largest raw totals on both sides, which is expected given it's also the largest cohort — the relationship between allowance and spend, not the raw total, is the more meaningful comparison here.

## 5. Geographic and Housing Distribution

**Count of matric_num by Address/Neighborhood (Treemap):**
Students are mapped across five Lagos neighborhoods — Surulere, Ajah, Ikeja, Marina, and Yaba — with **Surulere** and **Ajah** representing the largest concentrations of student residences. This geographic spread could reflect affordability, proximity to campus, or simply where student housing is most available in each area.

**Count of Level by Hall of Residence (Clustered Bar):**
2-bedded, 4-bedded, and 6-bedded halls house comparably large numbers of students, while 8-bedded halls are used far less frequently. This likely reflects either limited capacity in larger-occupancy halls or a general student preference for more private living arrangements.

## 6. Filters

The dashboard includes four cross-page slicers — **Level**, **Chapel Worker**, **Is Nigerian**, and **Member of SRC** — allowing users to filter every visual by these attributes and explore how demographics, financials, and housing patterns shift across specific subgroups.

## Key Insights

- **400-Level Dominance:** Nearly every categorical metric — nationality, SRC membership, chapel worker status, provision bag resumption — is led by the 400-level cohort, reflecting its larger overall enrollment share rather than any behavioral difference between levels.
- **Balanced Course Enrollment:** No single course of study dominates; all six courses sit within a tight 16–17% band, suggesting controlled admission quotas.
- **Allowance Tied to Family Occupation:** Students with Doctor or Businesswoman breadwinners report modestly higher allowances than those with Engineer breadwinners, pointing to a mild but consistent link between household profession and financial support.
- **Housing Preference for Smaller Halls:** Students are heavily concentrated in 2-, 4-, and 6-bedded halls, with minimal use of 8-bedded accommodation, likely driven by capacity or privacy preferences.
- **Spending Mirrors Allowance:** Across every level, amount spent tracks closely with amount received, leaving little visible surplus in the aggregate data.

## Conclusion

This dashboard provides a powerful tool for visualizing and analyzing a university's student population across academic levels, courses, family background, and living arrangements. It offers a clear picture of how demographics, financial support, and housing patterns intersect — helping identify which levels, courses, and neighborhoods are most represented, and how allowance varies with family occupation. The consistency of the 400-level cohort across nearly every metric, paired with the even spread of course enrollment and allowance levels, suggests a well-balanced but sizeable student population worth monitoring for capacity planning and welfare support.

---

## Dashboard Preview

**Page 1 — Student Demographics & Welfare**
![Student Demographics Dashboard](assets/dashboard-page1-demographics.jpg)

**Page 2 — Academic & Financial Overview**
![Academic Overview Dashboard](assets/dashboard-page2-overview.jpg)

## Skills Demonstrated

- **Data modeling** — structuring relationships between student, course, and residence data for accurate cross-filtering
- **DAX** — writing calculated measures for averages, counts, and KPI cards
- **Power Query** — cleaning and transforming raw student records into analysis-ready tables
- **Data visualization** — selecting the right chart type (donut, treemap, 100% stacked bar, clustered bar) for each question
- **Dashboard design** — building a cohesive, filterable, multi-page report with a consistent visual theme
- **Analytical storytelling** — translating chart output into clear, actionable insights

## Tools & Tech Stack

`Power BI Desktop` `Power Query` `DAX` `Data Visualization`

## How to Use

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Refresh the data source if connected to a live dataset
4. Use the slicers at the top of each page to filter by level, nationality, chapel worker status, or SRC membership

## Contact

**Stella Azum**
Data Analyst | Accounting Graduate
[GitHub](https://github.com/StellaAzum8)
