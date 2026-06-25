# 📊 Precision Farming Intelligence Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-orange)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-blue)
![Agriculture](https://img.shields.io/badge/Domain-Precision%20Farming-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Tool:** Microsoft Power BI &nbsp;|&nbsp; **Domain:** Agriculture / Precision Farming Analytics  
> **Project Type:** Multi-page Interactive Dashboard  
> **Focus:** Crop Health, Yield, Irrigation, Fertilizer, Soil, Weather, and Regional Farm Performance

---

## 📌 About This Project

The **Precision Farming Intelligence Dashboard** is an end-to-end **Power BI analytics project** built to transform smart farming data into actionable agricultural insights. It helps analyze **farm productivity, crop health, disease severity, irrigation performance, fertilizer usage, soil conditions, weather impact, and regional yield trends** — enabling farm managers, analysts, and agricultural stakeholders to make better data-driven decisions.

This dashboard was designed as a **6-page interactive reporting solution**, where each page focuses on a specific area of agricultural analysis such as crop health, geo-regional performance, irrigation efficiency, and smart farming recommendations.

---

## 🎯 Project Objective

The goal of this project is to use farming sensor and operational data to answer questions like:

- Which **crop types** are producing higher yield?
- Which regions have **higher severe disease concentration**?
- How do **soil moisture, rainfall, humidity, pH, and NDVI** affect crop performance?
- Which **irrigation methods** and **fertilizer types** are associated with better yield?
- How can farmers use these insights to improve **crop health monitoring, disease control, and resource planning**?

---

## 📂 Repository Structure

```bash
Precision_Farming_Intelligence_Dashboard/
│
├── Images/
│   ├── Crop Health & Disease Analytics.png
│   ├── Geo & Regional Performance Analytics.png
│   ├── Irrigation & Fertilizer Analytics.png
│   ├── Precision Farming Intelligence Dashboard.png
│   ├── Smart Farming Insights & Recommendations.png
│   └── Soil & Weather Analytics.png
│
├── Raw Data/
│   └── Smart_Farming_Crop_Yield_2024.csv
│
└── README.md
```

### 🔗 Quick Navigation
- 📸 [Dashboard Screenshots](./Images)
- 📂 [Raw Dataset](./Raw%20Data)
- 📄 [Smart Farming Dataset CSV](./Raw%20Data/Smart_Farming_Crop_Yield_2024.csv)

---

# 🖥️ Dashboard Pages Overview

This project contains **6 interactive dashboard pages**, each designed to answer a different business question in the precision farming workflow.

---

# 1️⃣ Precision Farming Intelligence Dashboard

![Precision Farming Intelligence Dashboard](./Images/Precision%20Farming%20Intelligence%20Dashboard.png)

## 📍 Purpose
This is the **main overview dashboard** that gives a high-level snapshot of overall farming performance, crop health, rainfall, NDVI, and disease case distribution.

## 📊 KPIs Displayed
- **Total Farms** → 500
- **Total Yield** → 2M
- **Average Soil Moisture** → 26.75%
- **Average Rainfall** → 181.69 mm
- **Average NDVI** → 0.60
- **Healthy Crops** → 130
- **Mild Disease Cases** → 125
- **Moderate Disease Cases** → 112
- **Severe Disease Cases** → 133

## 📈 Visuals Included
- **Map Visual** → Region-wise yield distribution across farming locations
- **Monthly Yield Trend** → Tracks yield performance over time
- **Fertilizer Type Distribution** → Donut chart showing fertilizer usage split
- **Crop Health Score (NDVI) Gauge** → Indicates overall crop health condition
- **Slicers** → Crop Type, Region, Disease Severity

## 🔍 Key Insight
This page acts as the **executive summary** of the dashboard by combining productivity metrics, crop health indicators, rainfall, and disease severity into one consolidated view.

---

# 2️⃣ Soil & Weather Analytics

![Soil & Weather Analytics](./Images/Soil%20%26%20Weather%20Analytics.png)

## 📍 Purpose
This page focuses on understanding how **soil and weather conditions vary across crop types**, helping users assess environmental impact on crop growth and yield.

## 📊 KPIs Displayed
- **Average Soil Moisture** → 26.75%
- **Average Temperature** → 24.68 °C
- **Average Rainfall** → 181.69 mm
- **Average Humidity** → 65.19%

## 📈 Visuals Included
- **Soil Moisture by Crop Type** → Column chart
- **Rainfall Distribution by Crop Type** → Column chart
- **Soil pH Analysis by Crop Type** → Column chart
- **Humidity Analysis by Crop Type** → Horizontal bar chart
- **Slicers** → Crop Type, Region, Disease Severity

## 🔍 Key Insight
This page helps compare **environmental conditions across crops** and shows how rainfall, humidity, pH, and soil moisture differ from one crop to another — useful for identifying crop-specific farming needs.

---

# 3️⃣ Irrigation & Fertilizer Analytics

![Irrigation & Fertilizer Analytics](./Images/Irrigation%20%26%20Fertilizer%20Analytics.png)

## 📍 Purpose
This page analyzes the relationship between **irrigation methods, fertilizer types, soil moisture, and crop yield**.

## 📊 KPIs Displayed
- **Average Yield** → 4.03K
- **Average Soil Moisture** → 26.75%
- **Total Farms** → 500
- **Average NDVI** → 0.60

## 📈 Visuals Included
- **Yield by Irrigation Type** → Column chart
- **Yield by Fertilizer Type** → Column chart
- **Soil Moisture by Irrigation** → Treemap
- **Fertilizer Distribution** → Donut chart
- **Fertilizer Performance by Crop** → Crop-wise fertilizer performance comparison
- **Slicers** → Crop Type, Region, Disease Severity

## 🔍 Key Insight
This page helps determine:
- which irrigation method is associated with better yield,
- how fertilizer usage is distributed,
- and whether crop performance varies depending on fertilizer strategy.

This is useful for **resource optimization and farm planning**.

---

# 4️⃣ Crop Health & Disease Analytics

![Crop Health & Disease Analytics](./Images/Crop%20Health%20%26%20Disease%20Analytics.png)

## 📍 Purpose
This page focuses on **crop disease severity and crop health performance**, helping identify which crops are more affected and how disease severity impacts yield and NDVI.

## 📊 KPIs Displayed
- **Healthy Crops** → 130
- **Mild Disease Cases** → 125
- **Moderate Disease Cases** → 112
- **Severe Disease Cases** → 133

## 📈 Visuals Included
- **Disease Distribution by Crop** → Stacked bar chart
- **Yield by Disease Severity** → Column chart
- **NDVI by Disease Severity** → Column chart
- **Severe Cases by Crop** → Horizontal bar chart
- **Slicers** → Crop Type, Region, Disease Severity

## 🔍 Key Insight
This page helps answer:
- which crop types have the highest severe disease concentration,
- how disease severity affects yield,
- and whether NDVI scores differ significantly across disease levels.

It is especially useful for **crop health monitoring and disease management planning**.

---

# 5️⃣ Geo & Regional Performance Analytics

![Geo & Regional Performance Analytics](./Images/Geo%20%26%20Regional%20Performance%20Analytics.png)

## 📍 Purpose
This page provides a **regional and geographical view of farm performance**, allowing users to compare yield, NDVI, and disease severity across different regions.

## 📊 KPIs Displayed
- **Total Regions** → 5
- **Average Yield** → 4.03K
- **Average NDVI** → 0.60
- **Severe Diseases** → 133

## 📈 Visuals Included
- **Geographical Map** → Region-wise farm distribution
- **Average Yield by Region** → Horizontal bar chart
- **Severe Cases by Region** → Horizontal bar chart
- **Average NDVI by Region** → Treemap
- **Slicers** → Crop Type, Region, Disease Severity

## 🔍 Key Insight
This page helps identify:
- which regions are producing higher average yield,
- which regions are facing more severe disease cases,
- and how crop health differs region-wise.

This supports **regional agricultural planning and targeted intervention**.

---

# 6️⃣ Smart Farming Insights & Recommendations

![Smart Farming Insights & Recommendations](./Images/Smart%20Farming%20Insights%20%26%20Recommendations.png)

## 📍 Purpose
This page summarizes the overall findings from the dashboard and converts them into **practical farming recommendations**.

## 📊 KPIs Displayed
- **Average Yield** → 4.03K
- **Average NDVI** → 0.60
- **Severe Disease %** → 26.60%
- **Average Soil Moisture** → 26.75%

## 📈 Visuals Included
- **Yield by Crop Type** → Column chart
- **Yield Trend by Disease Severity** → Line chart
- **Recommended Actions Panel** → Text-based actionable insights

## 🧠 Recommendations Highlighted
- Prioritize monitoring in regions with **higher severe disease counts**
- Improve disease management for crops with **higher severe case concentration**
- Use **NDVI + soil moisture together** as early indicators of crop stress
- Review fertilizer usage crop-wise to improve productivity
- Maintain optimal irrigation practices where soil moisture influences performance
- Focus preventive actions in areas with **lower crop health scores**

## 🔍 Key Insight
This page acts as the **decision-making layer** of the project by converting dashboard findings into clear actions for agricultural stakeholders.

---

## 📊 Dataset Used

The project uses the smart farming dataset available in this repository:

- 📄 [Smart_Farming_Crop_Yield_2024.csv](./Raw%20Data/Smart_Farming_Crop_Yield_2024.csv)

### Main fields available in the dataset
- `farm_id`
- `region`
- `crop_type`
- `soil_moisture`
- `pH`
- `temperature`
- `rainfall`
- `humidity`
- `irrigation_type`
- `fertilizer_type`
- `pesticide_usage_kg`
- `yield_kg_per_hectare`
- `NDVI_index`
- `crop_disease_status`
- `latitude`
- `longitude`

---

## 📐 Core Metrics / KPIs Used

| KPI | Meaning |
|------|---------|
| **Total Farms** | Total number of farms in dataset |
| **Total Yield** | Total crop yield produced |
| **Avg Yield** | Average yield across farms / crops / regions |
| **Avg Soil Moisture** | Average soil moisture percentage |
| **Avg Rainfall** | Average rainfall recorded |
| **Avg Temperature** | Average temperature |
| **Avg Humidity** | Average humidity |
| **Avg NDVI** | Average crop health score (Normalized Difference Vegetation Index) |
| **Healthy Crops** | Count of healthy crop records |
| **Mild / Moderate / Severe Disease Cases** | Count of disease cases by severity |

---

## 📊 Dashboard Features & Interactivity

### Interactive Features Used
- **Slicers**
  - Crop Type
  - Region
  - Disease Severity

- **Cross-filtering**
  - Selecting one visual updates related visuals dynamically

- **Multi-page storytelling**
  - Each dashboard page focuses on a specific analytical theme

- **KPI Cards**
  - Quick snapshot of major agricultural indicators

- **Maps**
  - Geographic analysis of yield and regional distribution

- **Gauge / Donut / Treemap / Bar / Line Charts**
  - Used for performance comparison, trend tracking, and composition analysis

---

## ⚙️ Technical Highlights

| Category | Details |
|----------|---------|
| **Tool Used** | Microsoft Power BI |
| **Data Preparation** | Power Query |
| **Calculations / KPIs** | DAX Measures |
| **Data Modeling** | Relationships between farming attributes, crop health, weather, fertilizer, irrigation, and regional metrics |
| **Visuals Used** | KPI Cards, Column Charts, Bar Charts, Donut Chart, Treemap, Gauge, Map, Line Chart, Stacked Bar Chart, Slicers |
| **Dashboard Design** | Agriculture-focused theme with green tones and disease severity color coding |
| **Use Case** | Precision farming, crop monitoring, yield analysis, disease analytics, and resource optimization |

---

## 💡 Business Value Delivered

This dashboard can help **farm managers, agri-analysts, researchers, and agricultural stakeholders** to:

- Monitor **crop health and disease severity** across farms
- Compare **yield performance across crops and regions**
- Analyze the impact of **soil moisture, rainfall, humidity, pH, and NDVI**
- Evaluate **irrigation and fertilizer effectiveness**
- Identify regions with **high severe disease concentration**
- Support better **fertilizer planning, irrigation strategy, and crop management**
- Make **data-driven farming decisions** for improving productivity

---

## 🔍 Key Project Insights

### 1. Crop Health Monitoring is Critical
Disease severity is spread across crops, and some crop types show higher severe case concentration. Monitoring crop health using NDVI and disease indicators can help reduce productivity loss.

### 2. Regional Comparison Adds Strong Business Value
Yield and severe disease cases vary across regions, so regional-level monitoring is important for targeted action.

### 3. Soil + Weather + NDVI Together Give Better Understanding
Soil moisture, rainfall, humidity, and NDVI together provide a better view of crop stress and health than looking at only one variable.

### 4. Irrigation and Fertilizer Decisions Affect Yield
The dashboard shows that irrigation type and fertilizer usage can be compared directly against yield, helping identify more efficient farming strategies.

### 5. Dashboard Supports Preventive Farming Decisions
Instead of only reporting farm performance, the final recommendations page helps convert insights into **preventive and optimization actions**.

---

## 🚀 Conclusion

The **Precision Farming Intelligence Dashboard** demonstrates how Power BI can be used in the agriculture domain to turn raw farm data into meaningful insights. By combining **crop health monitoring, disease analysis, weather conditions, irrigation performance, fertilizer analysis, and regional comparisons**, this project provides a strong example of **data-driven decision-making in smart farming**.

This project is especially valuable as a **portfolio project** because it showcases:
- domain understanding
- KPI-based dashboard design
- data storytelling
- multi-page dashboard architecture
- business-oriented insight generation

---

## 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Het%20Ladani-blue?logo=linkedin)](https://linkedin.com/in/het-ladani-5001bb29a/)
[![GitHub](https://img.shields.io/badge/GitHub-ladanihet2410-black?logo=github)](https://github.com/ladanihet2410)