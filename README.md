# UK Immigration Dashboards (2010–2024)

This project provides a comprehensive analysis of UK immigration trends between 2010 and 2024, combining multiple official data sources to create a set of interactive dashboards and exploratory data analysis (EDA). The goal is to understand long-term migration patterns, changes by nationality group, asylum trends, and irregular migration via small boat arrivals.

The project includes:
- A full Python-based data preparation and EDA workflow
- Three Tableau dashboards published on Tableau Public
- Clean and reproducible code in Jupyter notebooks
- Maps, comparative charts, and multi-year trend visualisations

---

## 📊 Tableau Dashboards

You can explore the full interactive dashboards here:

🔗 **Tableau Public:**  
https://public.tableau.com/app/profile/alec.woods/viz/UKImmigrationDashboards2010-2024/MigrationDashboard

Three dashboards are included in the published Tableau workbook:

### **Dashboard 1 — General Migration Trends**
This dashboard visualises patterns in long-term immigration, emigration, and net migration using ONS and GOV.UK data.

Includes:
- **Net migration per year (2012–2024)**  
- **Map of top 10 non-EU contributing countries**
- **Grouped column chart:** British, EU, and non-EU net migration  
- **Grouped column chart:** Reasons for immigration (study, work, family, etc.) over time

---

### **Dashboard 2 — Irregular Migration (Small Boats)**
Focused on small boat arrivals across the English Channel.

Includes:
- **Small boat arrivals (2018–2024)**  
- **Map of highest-contributing countries for small boat arrivals**

---

### **Dashboard 3 — Asylum Trends**
A detailed view of asylum claims and outcomes.

Includes:
- **Asylum claims (2010–2024)**  
- **Map of countries with the most asylum claims**
- **Bar + line chart:** Asylum claims vs. asylum waiting list by year  
- **Combined bar chart:** Asylum decisions vs. grant rates for the top 10 countries of origin  

---

## 📁 Repository

GitHub project link:  
🔗 https://github.com/esencela/uk-immigration-data-analysis

The repository includes:
- Jupyter notebooks for data cleaning and EDA
- Cleaned datasets
- Visualisation scripts
- Tableau workbook file (`.twbx`)

---

## 📚 Data Sources

This project uses official UK government and statistical datasets:

- **ONS (Office for National Statistics)**  
  - Long-term international migration (LTIM)
  - Migration statistics quarterly reports  
- **GOV.UK / Home Office**  
  - Asylum and resettlement statistics  
  - Irregular migration / small boats data  
  - Visa reason categories (study, work, family, other)

These sources were chosen for accuracy, transparency, and regular publication.

---

## 🛠 Tools Used

### **Data processing & EDA**
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

### **Visualisation**
- Tableau Desktop / Tableau Public  
- Matplotlib & seaborn (light EDA visuals)

---

## 🔍 Exploratory Data Analysis Summary

Key high-level observations:

- Net migration fluctuated significantly between 2010 and 2024, with notable peaks during the post-pandemic recovery period.
- **Non-EU migration increased sharply** after Brexit, becoming the primary driver of net migration.
- The **top contributing countries for immigration** varied over time, with a mixture of Commonwealth and international students’ countries.
- **Small boat arrivals rose steadily** from 2018 before showing signs of stabilisation or decline in the latest years.
- **Asylum claims increased significantly** post-2019, while decision backlogs also grew until recent stabilisation efforts.
- Grant rates varied substantially between nationalities, reflecting diverse geopolitical pressures.
- **Different timescales across datasets** required careful alignment (e.g., asylum data from 2010 vs small boats from 2018).

---

## ⚠️ Limitations

- Data from different sources cover **different time periods**, so direct comparison is limited in some cases.
- Asylum, irregular migration, and LTIM datasets use **different definitions and collection methodologies**.
- Some datasets only provide **country groups**, not full granular breakdowns.
- Annual vs quarterly updates create potential mismatches in trend alignment.
- Map visualisations depend on available country-level aggregation.

---

## 🚀 Possible Next Steps / Extensions

Here are some strong, realistic extensions that would elevate the project:

### **1. Time-Series Forecasting**
Predict future immigration, asylum claims, or small boat arrivals using:
- ARIMA / SARIMA
- Prophet
- Gradient boosting regressors

### **2. Deeper Country-Level Analysis**
Drill down into:
- Regional origins of migrants  
- Push/pull factors tied to economic or conflict indicators  

### **3. Labour Market Integration**
Link immigration trends with:
- Job vacancy data  
- Wage levels  
- Shortage occupation lists
