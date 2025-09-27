# Data Professionals Survey – Power BI Portfolio Project

A full end-to-end analytics project built in **Power BI Desktop** using a **real survey dataset** (≈700 responses; 630 usable after cleaning). The report explores demographics, roles, compensation, tooling preferences, and satisfaction across the data profession and presents insights via interactive visuals and KPIs.

---

## 📌 Highlights

- **630** total valid survey takers analyzed. 
- Average **work/life balance happiness ~5.7 / 10**; **salary happiness ~4.3 / 10**.
- **Python** ranks as the top favorite programming language across roles.
- Salary comparisons by **job title** (Data Scientist, Data Engineer, Data Architect, Data Analyst, etc.). 
- **Entry difficulty**: plurality report it’s **difficult** to break into data (vs. easy/very easy). 

## 🧭 Project Objectives

1. **Profile the data profession**: geography, age, roles, and experience. 
2. **Benchmark compensation** across job titles and locations. 
3. **Map tool preferences** (languages, databases, viz tools).
4. **Assess satisfaction** (work/life balance, salary) and career entry difficulty.

---

## 🛠️ Tech & Skills

- **Power BI Desktop** (data model, DAX, visuals)
- **Power Query** (ETL: cleaning, type casting, standardizing categories)
- **DAX** (KPIs, role-level aggregations, time-independent measures)
- **Data Storytelling** (interactive slicers, drill-downs, and layout)

---

## 📈 Report Pages & Visuals

1. **Overview Dashboard**  
   - KPIs: Count of Survey Takers, Avg Age, Happiness (Work/Life & Salary)  
   - Role composition & country distribution  
   - Slicers: Job Title, Country, Experience, Education

2. **Compensation Explorer**  
   - **Average Salary by Job Title** bar chart with tooltips & role filter 
   - Distribution plots (optional): box/violin alternatives via custom visuals

3. **Tools & Languages**  
   - **Favorite Programming Languages** by role (stacked/clustered bars) 
   - Database & BI tool preferences (optional)

4. **Satisfaction & Career Path**  
   - **Happiness with Work/Life** & **Salary** (0–10 scale) KPIs 
   - **Difficulty to Break Into Data** (Very Easy → Very Difficult)

---

## 📐 Data Model (High Level)

- **Fact**: `SurveyResponses`   
- **Dimensions** (derived via Power Query):  
  - `DimRole` (normalized job titles)  
  - `DimCountry` (standardized country names/regions)  
  - `DimTools` (language/tool preferences exploded/one-hot or bridge)  




