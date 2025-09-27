# Data Professionals Survey – Power BI Portfolio Project

A full end-to-end analytics project built in **Power BI Desktop** using a **real survey dataset** (≈700 responses; 630 usable after cleaning). The report explores demographics, roles, compensation, tooling preferences, and satisfaction across the data profession and presents insights via interactive visuals and KPIs. :contentReference[oaicite:0]{index=0}

---

## 📌 Highlights

- **630** total valid survey takers analyzed. :contentReference[oaicite:1]{index=1}  
- Average **work/life balance happiness ~5.7 / 10**; **salary happiness ~4.3 / 10**. :contentReference[oaicite:2]{index=2}  
- **Python** ranks as the top favorite programming language across roles. :contentReference[oaicite:3]{index=3}  
- Salary comparisons by **job title** (Data Scientist, Data Engineer, Data Architect, Data Analyst, etc.). :contentReference[oaicite:4]{index=4}  
- **Entry difficulty**: plurality report it’s **difficult** to break into data (vs. easy/very easy). :contentReference[oaicite:5]{index=5}

## 🧭 Project Objectives

1. **Profile the data profession**: geography, age, roles, and experience. :contentReference[oaicite:6]{index=6}  
2. **Benchmark compensation** across job titles and locations. :contentReference[oaicite:7]{index=7}  
3. **Map tool preferences** (languages, databases, viz tools). :contentReference[oaicite:8]{index=8}  
4. **Assess satisfaction** (work/life balance, salary) and career entry difficulty. :contentReference[oaicite:9]{index=9}

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
   - **Average Salary by Job Title** bar chart with tooltips & role filter :contentReference[oaicite:10]{index=10}  
   - Distribution plots (optional): box/violin alternatives via custom visuals

3. **Tools & Languages**  
   - **Favorite Programming Languages** by role (stacked/clustered bars) :contentReference[oaicite:11]{index=11}  
   - Database & BI tool preferences (optional)

4. **Satisfaction & Career Path**  
   - **Happiness with Work/Life** & **Salary** (0–10 scale) KPIs :contentReference[oaicite:12]{index=12}  
   - **Difficulty to Break Into Data** (Very Easy → Very Difficult) :contentReference[oaicite:13]{index=13}

---

## 📐 Data Model (High Level)

- **Fact**: `SurveyResponses` (one row per respondent)  
- **Dimensions** (derived via Power Query):  
  - `DimRole` (normalized job titles)  
  - `DimCountry` (standardized country names/regions)  
  - `DimTools` (language/tool preferences exploded/one-hot or bridge)  




