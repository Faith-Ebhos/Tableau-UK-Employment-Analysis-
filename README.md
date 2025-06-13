# Job Change UK Dashboard Project

This project explores job change trends across the UK using data from the **EMSI Job Change dataset**. An interactive **Tableau dashboard** was created to analyze labor market transitions, occupational growth and decline, regional variations, and skills demand.

The goal was to deliver clear and compelling visual insights for policymakers, workforce planners, and education providers.

---

## 📊 Dashboard Overview

The Tableau dashboard visualizes and compares:

- Occupational inflows and outflows across the UK  
- Top growing and declining jobs over time  
- Job change volume by region and industry  
- Skills demand associated with career transitions  
- Gender and age distribution among job changers  

The dashboard uses dynamic filters to segment the data by region, occupation, industry, and demographic group.

---

## 🔍 Large Events and Key Insights

- 📈 **Surge in Healthcare and Tech Occupations**: NHS-related roles and IT support jobs saw a notable increase in job inflow, especially during and after the COVID-19 pandemic.
- 🧯 **Decline in Retail and Hospitality Roles**: These sectors experienced the highest outflow, particularly in urban centers like London and Manchester.
- 🧠 **Reskilling Shift**: Workers moving into high-demand roles (e.g., software development, data analysis) often transitioned from unrelated sectors, signaling a growing emphasis on **transferable skills** and **reskilling**.
- 🌍 **Regional Polarization**: The South East and Greater London gained the highest number of new job entrants, while some regions in the North and Midlands saw a net job loss.
- 👩‍💻 **STEM Careers Dominated Female Entry Gains**: Compared to previous years, more women entered data-driven and healthcare occupations, especially in junior and mid-level roles.
- 📉 **Job Volatility in Young Workers (16–24)**: Youth job changers were most affected by seasonal industries and automation risks.

---

## 🧠 Tableau Skills Demonstrated

### 📈 Advanced Visual Design
- Created a multi-page **Tableau dashboard** with:
  - Heatmaps, bar charts, line graphs, scatter plots, and tree maps  
  - Tooltips with embedded trend data and definitions  
  - Dynamic parameters and filters for role, region, and time period
- Used color encoding to signal growth/decline patterns and job change direction

### 🧹 Data Preparation in Tableau
- Connected EMSI data directly to Tableau with custom extract
- Cleaned and transformed raw data using:
  - Tableau Prep Builder and in-workbook calculated fields  
  - Grouping, binning, and hierarchical dimension creation (Occupation → SOC → Sector)
  - Pivoted columns and created unions for multi-year trend comparisons

### 📊 Calculations and KPIs
- Developed custom measures such as:
  - Net Job Flow = Inflow – Outflow
  - Job Change Rate % = (Inflow / Total Employment) × 100
  - Occupation Volatility Index based on year-on-year changes
- Applied LOD (Level of Detail) expressions to handle regional aggregates

### 🧱 Dashboard Structuring & Storytelling
- Designed an intuitive layout with consistent navigation and legends
- Used **dashboard actions** (filter, highlight, URL) for interactivity
- Emphasized readability with dynamic titles and descriptive captions

---

## 📂 Files Included

- `EMSI_Job_Change_UK.twbx` – Packaged Tableau workbook with full dashboard  
- `README.md` – Project documentation (this file)  
- `EMSI_UK_Job_Data.csv` – Cleaned dataset used in the dashboard (optional)

---

## 📌 Summary

This project showcases strong capabilities in **Tableau dashboard development**, **data storytelling**, and **labor market analytics**. By leveraging EMSI UK data, the dashboard highlights critical workforce transitions and skills shifts in the modern economy. The end result enables stakeholders to spot trends, plan interventions, and understand where jobs are coming from — and going to.

![Dashboard 1](https://github.com/user-attachments/assets/232265f9-3324-448f-b7ae-f802f1857368)


