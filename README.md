# ⚡ Hydropower & Data Centre Analytics Dashboard

![Hydropower Analytics Dashboard](Hydro.jpg)

## 1. Executive Summary
This Power BI dashboard provides a detailed operational analysis of data center sustainability, energy consumption, and environmental water usage metrics across globally distributed facilities (**3K Total Facilities**). Using **Power Query** for data transformation and **DAX** for custom calculation metrics (PUE, Total kWh, Total Water Gallons), the dashboard evaluates data center efficiency across operators, cooling technologies, and regional water risk tiers.

---

## 2. Key Performance Indicators (KPIs)
* **Average PUE (Power Usage Effectiveness):** `1.66`
* **Total Facilities Analyzed:** `3,000 (3K)`
* **Total Electricity Consumption:** `15.25K kWh`
* **Total Water Consumption:** `1.46 Billion Gallons`

---

## 3. Key Analytical Insights
1. **Top Operators by Energy Consumption:**
   * **Digital Realty Trust** leads total energy usage (>1,000 kWh), followed by **Equinix**, **CenturyLink**, **Cycxtera**, and **Zayo Group LLC**.
2. **Annual Water Consumption Trend (2019–2025):**
   * Water consumption shows a continuous upward trajectory, increasing from **~180M gallons in 2019** to nearly **240M gallons projected by 2025**.
3. **Cooling Technology Breakdown:**
   * **Air Cooled systems** consume the highest energy (~495.00K kWh), closely followed by **Evaporative Cooling** (~430.26K kWh), while **Liquid Cooled technology** accounts for a much smaller share (~43.87K kWh).
4. **Facility Risk Assessment:**
   * The majority of facilities are located in areas classified under **Medium** and **High Surrounding Water Stress Tiers**.

---

## 4. Technical Workflow (Power Query & DAX)
* **Data Transformation (Power Query):** Cleaned, standardized facility IDs, owner companies, cooling system types, and country geographic dimensions.
* **DAX Calculations:** Created dynamic measures for average PUE, total water usage in billions, aggregated annual energy metrics, and country-level filtering.
* **UI/UX Design:** Built a dark purple-themed layout utilizing KPI cards, stacked horizontal bar charts, line trends, and interactive multi-slicers (Country and Year).

---

## 5. Strategic Recommendations
* **Transition to Liquid Cooling:** Encourage adoption of liquid cooling technologies across high-consumption facilities to reduce overall PUE and energy footprint.
* **Water Risk Mitigation:** Implement localized water conservation measures for facilities situated in High Water Stress Tiers.
