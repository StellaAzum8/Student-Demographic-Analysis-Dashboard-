# Student-Demographic-Analysis-Dashboard-

# Student Data Analysis Dashboard: Demographics, Finances, and Campus Life Trends

![Student Data Analysis Dashboard](assets/dashboard-page2-overview.jpg)

This Student Data Analysis Dashboard provides a comprehensive overview of a university's student population, focusing on key metrics such as academic level, nationality, community involvement, financial allowances, and living arrangements. Here's a breakdown of the components and insights from the dashboard:

## 1. Header and Key Metrics

- **Total Number of Students (4,696):** The dashboard summarizes the full student population captured in the dataset, indicating the overall scale of the analysis.
- **Number of Courses Offered (14):** Highlights the academic breadth of the institution across departments.
- **Students with Both Parents (2,372):** Roughly half the student body reports having both parents, offering a lens into family background.
- **Minimum Age of Students (15):** Flags the youngest recorded student, useful for identifying data entry outliers or early-admission cases.
- **Average Monthly Allowance (₦69.35K):** A baseline figure for comparing financial support across levels, courses, and family occupations.

## 2. Charts and Visualizations

**Count of is_nigerian, is_member_of_src, and is_chapel_worker by Level (Donut & Pie Charts):**
These three visuals share a strikingly similar distribution across levels — 400-level students make up the largest share (39.18%), followed by 300-level (20.91%), 200-level (20.51%), and Masters (19.4%). The consistency across nationality, SRC membership, and chapel worker status by level suggests these categories track closely with overall enrollment size rather than varying independently by group.

**Count of resumed_with_provision_bag by Level (100% Stacked Bar):**
This chart mirrors the same level-based distribution, with 400-level leading at 1,840 students, reinforcing that 400-level is consistently the largest cohort across nearly every metric on the dashboard.

**Total Number of Students by Course of Study (Pie Chart):**
Enrollment is evenly spread across the six courses tracked — Industrial Chemistry, Mass Communication, Business Administration, Cyber Security, and others — each accounting for roughly 16–17% of the student body, showing no single course dominates.

**Average Monthly Allowance by Level (100% Stacked Bar):**
300-level students report the highest average allowance (₦69.97K), followed closely by 400-level (₦69.4K), Masters (₦69.18K), and 200-level (₦68.79K). The narrow spread suggests allowance is fairly consistent regardless of academic level.

## 3. Family and Financial Breakdown

**Average Monthly Allowance by Breadwinner Occupation (Ranked List):**
Students whose breadwinner works as a Doctor (₦70,323.68) or Businesswoman (₦70,317.19) report the highest average allowances, while those with an Engineer as breadwinner report the lowest (₦68,314.69). Architects, Bankers, and Lecturers fall in between, showing a modest but noticeable link between parental occupation and student allowance.

**Count of Breadwinner Parent Occupation (Treemap):**
This visualization maps the relative frequency of each occupation among students' breadwinners — Doctor, Businesswoman, Lecturer, Engineer, Banker, Trader, and Architect — giving a quick sense of the professional makeup of students' families.

**Average Monthly Allowance vs. Average Monthly Spent by Level:**
Comparing allowance received against amount spent by level shows spending tracks closely with allowance at every level, with 400-level students handling by far the largest totals, consistent with their larger cohort size.

## 4. Neighborhood and Housing Distribution

**Count of matric_num by Address/Neighborhood (Treemap):**
Students are mapped across five Lagos neighborhoods — Surulere, Ajah, Ikeja, Marina, and Yaba — with Surulere and Ajah representing the largest concentrations of student residences.

**Count of Level by Hall of Residence (Clustered Bar):**
2-bedded, 4-bedded, and 6-bedded halls house comparably large numbers of students, while 8-bedded halls are used far less frequently, suggesting a preference (or availability constraint) toward smaller room configurations.

## 5. Filters

The dashboard includes four cross-page slicers — **Level**, **Chapel Worker**, **Is Nigerian**, and **Member of SRC** — allowing users to filter every visual by these attributes and explore how demographics shift across subgroups.

## Key Insights

- **400-Level Dominance:** Nearly every categorical metric — nationality, SRC membership, chapel worker status, provision bag resumption — is led by the 400-level cohort, reflecting its larger overall enrollment share.
- **Even Course Distribution:** No single course of study dominates enrollment; all six courses sit within a tight 16–17% band.
- **Allowance Tracks Family Occupation:** Students with Doctor or Businesswoman breadwinners report modestly higher allowances than those with Engineer breadwinners, hinting at a link between household profession and financial support.
- **Housing Preference for Smaller Halls:** Students are concentrated in 2-, 4-, and 6-bedded halls, with minimal representation in 8-bedded accommodation.

## Conclusion

This dashboard provides a powerful tool for visualizing and analyzing a university student population across academic levels, courses, family background, and living arrangements. It offers a clear picture of how demographics, finances, and housing patterns intersect — helping identify which levels, courses, and neighborhoods are most represented, and how financial support varies with family occupation.

---

### Dashboard Pages

**Page 1 — Student Demographics & Welfare**
![Student Demographics Dashboard](assets/dashboard-page1-demographics.jpg)

**Page 2 — Academic & Financial Overview**
![Academic Overview Dashboard](assets/dashboard-page2-overview.jpg)

### Tools Used
Power BI Desktop · Power Query · DAX

### How to Use
1. Clone or download this repository
2. Open the `.pbix` file in Power BI Desktop
3. Refresh the data source if connected to a live dataset
4. Use the slicers at the top of each page to filter by level, nationality, chapel worker status, or SRC membership

### Author
**Stella Azum** — Data Analyst | Accounting Graduate
[GitHub](https://github.com/StellaAzum8)
