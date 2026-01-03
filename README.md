#  SQL-Based Sustainability Analytics (SDG 7 & SDG 13)

##  Project Overview
This project is an end-to-end **SQL-based analytics project** focused on analyzing
**clean energy adoption, carbon emissions, and energy access** in alignment with the
**United Nations Sustainable Development Goals (SDGs)**:

- **SDG 7** – Affordable & Clean Energy  
- **SDG 13** – Climate Action  

The project simulates a **real-world government or policy analytics use case**, where
decision-makers rely on SQL-driven insights to monitor sustainability progress across
countries and over time.

---

##  Business Context
Governments and sustainability-focused organizations need to answer questions such as:
- Which countries are increasing renewable energy adoption?
- How does renewable investment impact carbon emissions?
- Which regions still lack access to electricity and clean cooking fuels?
- Are emissions reducing as clean energy usage increases?

This project uses **relational SQL analytics** to answer these questions and support
**data-driven sustainability decisions**.

---

##  Dataset Description
The dataset is a **synthetic but production-style relational dataset**, intentionally
designed to mimic real-world sustainability data.

### Key Characteristics
- Time period: **2018–2022**
- Multiple countries across different regions and income levels
- Multiple related tables (not a flat dataset)
- Includes **intentional data quality issues** to replicate production environments

### Tables Included
| Table Name | Description |
|----------|------------|
| countries | Country, region, and income-level information |
| years | Time dimension for trend analysis |
| energy_types | Renewable vs non-renewable energy sources |
| energy_production | Energy generation and investment data |
| emissions | CO₂ emissions by country and year |
| energy_access | Electricity and clean cooking access metrics |

---

##  Real-World Data Quality Issues Included
To simulate real production data, the dataset intentionally includes:
- Missing values in energy access data for some low-income countries
- Inconsistent country name formatting (case differences, duplicates)
- Outliers in emissions data for selected years
- Uneven data distribution across countries and years

These issues were handled using **SQL-based data cleaning and validation queries**.

---

##  SQL Skills Demonstrated
- Relational data modeling with primary & foreign keys  
- INNER JOIN and LEFT JOIN operations  
- GROUP BY and HAVING clauses  
- Subqueries and Common Table Expressions (CTEs)  
- NULL handling and data standardization  
- Trend and comparison analysis  

---

##  Key Analysis Performed
- Renewable vs fossil fuel energy trends
- Carbon emissions trend analysis
- Energy access gaps across countries
- Investment efficiency in renewable energy
- Identification of emission outliers and anomalies

---

##  Tools Used
- **SQL** (MySQL / PostgreSQL / SQLite compatible)
- **GitHub** for version control and documentation

---

## 📂 Repository Structure
