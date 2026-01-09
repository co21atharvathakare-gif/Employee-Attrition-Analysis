# HR Analytics: Employee Attrition Deep Dive 📊

## 📌 Project Overview
Why do high-performing, satisfied employees leave an organization? This project explores the "hidden" drivers of employee attrition using the **IBM HR Attrition Dataset**. 

Unlike standard reports that focus on surface-level dissatisfaction, this analysis performs a **Root Cause Analysis** to identify specific "Flight Risk" personas and provide data-driven recommendations for HR retention strategies.

## 🛠️ Tech Stack & Methodology
* **Tool:** Microsoft Excel
* **Data Cleaning:** Used **Power Query** to standardize data types and create Age Buckets (e.g., 26–35, 36–45).
* **Data Modeling:** Engineered a binary `Attrition_Count` helper column to enable precise rate calculations within Pivot Tables.
* **Analysis:** Leveraged **Pivot Tables** to cross-reference multiple variables (Marital Status, Stocks, Overtime).
* **Visualization:** * Interactive Dashboard with dynamic **Slicers**.
    * **Satisfaction vs. Work-Life Balance Heat Map** using Conditional Formatting.
    * Professional UI design using the **Linked Picture (Camera Tool)** for layout flexibility.

## 🔍 The "Perfect Storm" – Key Insights
The data revealed a surprising **"Satisfaction Paradox"**: 
Over 50% of leavers reported **High Job Satisfaction** and **Good Work-Life Balance**. The analysis identifies the true drivers as a combination of three factors:

1.  **The Target Demographic:** 67% of leavers are aged **26–35** and 51% are **Single**.
2.  **The Financial Anchor:** 156 leavers (66% of all exits) had **0 Stock Options**, providing no long-term financial incentive to stay.
3.  **The Trigger:** High **Overtime** acts as the final push for this mobile and unanchored segment.



## 💡 Strategic Recommendations
* **Early Stock Vesting:** Implement a "Year 1" Stock Option program for high-performing junior/single talent to create a "financial anchor."
* **Targeted Role Monitoring:** Review overtime limits specifically for **Sales Representatives** and **Laboratory Technicians**, who show the highest correlation between extra hours and exit.
* **Retention Personas:** Move away from "one-size-fits-all" HR policies. The 26–35 age bracket requires **career-track visibility** rather than just increased work-life balance perks.

## 🚀 How to Use
1.  Download the `HR_Analytics_Dashboard.xlsx` file.
2.  Use the **Slicers** (Department, Marital Status, Job Role) to explore how attrition drivers shift across different employee segments.
3.  Refer to the **Calculations** sheet to see the underlying Pivot Table logic.
