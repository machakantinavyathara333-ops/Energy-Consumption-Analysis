# 🌍 Energy Consumption Analysis using MySQL

## 📌 Project Overview

This project analyzes global **Energy Production, Energy Consumption, Carbon Emissions, GDP, and Population** data using **MySQL**. The goal is to uncover meaningful insights into global energy trends, compare countries, and understand the relationship between economic growth, energy usage, and environmental sustainability.

This project demonstrates how SQL can be used to solve real-world analytical problems by transforming raw data into actionable business insights.

---

## 🎯 Business Problem

With increasing industrialization, economic growth, and population expansion, global energy demand has risen significantly, leading to higher carbon emissions and environmental concerns.

This project analyzes global energy data to identify trends, compare countries, evaluate energy efficiency, and support sustainable decision-making using SQL.

---

## 🎯 Objectives

- Analyze energy production and consumption across countries.
- Identify countries with the highest carbon emissions.
- Study the relationship between GDP and energy consumption.
- Analyze the impact of population growth on emissions.
- Measure energy efficiency using per-capita and ratio-based metrics.
- Generate insights for sustainable energy management.

---

## 🗂️ Dataset

The project uses six datasets:

| Table | Description |
|--------|-------------|
| Country | Master table containing country information |
| Consumption | Energy consumption data |
| Production | Energy production data |
| Emission | Carbon emission data |
| GDP | Gross Domestic Product data |
| Population | Population data |

---

## 🗃️ Database Schema

The **Country** table acts as the master table and is connected to all other tables through one-to-many relationships.

Country (1) → Production (Many)

Country (1) → Consumption (Many)

Country (1) → Emission (Many)

Country (1) → GDP (Many)

Country (1) → Population (Many)

---

## 🛠️ SQL Concepts Used

- Joins
- Aggregate Functions
- GROUP BY
- ORDER BY
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
  - LAG()
  - FIRST_VALUE()
  - LAST_VALUE()

---

## 📊 Analysis Performed

- Total emissions by country
- Top 5 countries by GDP
- Energy production vs consumption
- Countries with the highest carbon emissions
- Global emission trends over time
- Population vs emissions
- Energy consumption relative to GDP
- Energy consumption per capita
- Countries reducing per-capita emissions
- Global emission share

---

## 💡 Key Insights

- Major economies contribute the largest share of global carbon emissions.
- Countries with higher GDP generally consume more energy.
- Population growth influences emissions, but industrial activity has a greater impact.
- Energy production and consumption vary significantly across countries.
- Per-capita analysis provides a fair comparison of energy efficiency.
- Several countries have improved their per-capita emissions over the available years.

---

## 💻 Tools & Technologies

- MySQL Workbench
- SQL
- Microsoft PowerPoint
- GitHub

---

## 📁 Project Structure

```
Energy-Consumption-Analysis/
│
├── Dataset/
│   ├── Country.csv
│   ├── Consumption.csv
│   ├── Production.csv
│   ├── Emission.csv
│   ├── GDP.csv
│   └── Population.csv
│
├── SQL Queries/
│   └── Energy_Consumption_Analysis.sql
│
├── Presentation/
│   └── Energy_Consumption_Analysis.pptx
│
├── Images/
│   ├── ER_Diagram.png
│   ├── Query_Output_1.png
│   ├── Query_Output_2.png
│   └── ...
│
└── README.md
```



## 🚀 Conclusion

This project demonstrates how SQL can be used to analyze large datasets and extract meaningful insights related to energy consumption, economic growth, and environmental sustainability. 
The analysis supports data-driven decision-making by identifying trends, comparing countries, and evaluating energy efficiency.

---

## 👩‍💻 Author

**NavyaTara Machakanti**

- LinkedIn: https://www.linkedin.com/in/navyathara-machakanti-713580249/
- GitHub: *https://github.com/machakantinavyathara333-ops*
