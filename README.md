#  HR Employee Flow Analytics Dashboard | Excel & Slicers

This project delivers a fully interactive HR analytics dashboard built in Excel, designed to provide dynamic insights into workforce health, turnover risk, and organizational growth trends. The goal was to transform static HR data into actionable business intelligence using Pivot Tables and advanced Excel functionality.

##  Problem Statement

The organization faced challenges due to a lack of consolidated, real-time metrics on employee flow. This resulted in reactive staffing decisions and an inability to proactively address emerging retention risks. Key questions that needed answers included:

1.  Which **departments** and **age groups** pose the highest attrition risk relative to their size?
2.  What is the company's true **attrition rate**, and how does it correlate with employee demographics?
3.  Are current **hiring trends** supporting the organization’s long-term growth needs?

This dashboard was developed to centralize these metrics and provide HR Business Partners and management with a dynamic, filterable tool for strategic workforce planning.

 ## 🔍 Key Actionable Insights

Based on the visual analysis provided by the charts (Attrition by Department, Attrition by Age, etc.), the following critical insights were identified:

### **A. Targeted Retention Risk**

* **Highest Attrition Rate:** The **HR Department** shows the highest relative attrition rate (the highest orange line peak), indicating a significant internal retention problem that undermines recruitment efforts.
* **Highest Volume Risk:** While HR has the highest *rate*, **Finance** and **Sales** have the highest *volume* of leavers (tallest blue bars), representing the largest immediate staffing gaps to fill.
* **Mid-Career Flight:** The **40-49 Age Group** exhibits the highest volume of attrition, suggesting a failure to retain experienced, mid-career talent. This points to potential issues with career progression paths, compensation stagnation, or leadership opportunities for this cohort.

### **B. Workforce Flow Dynamics**

* **Hiring Volatility:** The Hiring Trend chart reveals significant volatility, with hiring peaks followed by sharp, immediate drops. This suggests inconsistent long-term workforce planning and potential resource constraints during high-growth periods.
* **KPI Benchmark:** The overall **Total Attrition Rate** provides the necessary organizational benchmark for measuring the success of future retention initiatives.

* ## 🛠️ Tools & Technical Skills

* **Platform:** Microsoft Excel
* **Data Modeling:** Pivot Tables (as data sources for all visuals)
* **Interactivity:** Slicers (Gender, Department, Age Group, etc.) connected to all charts and KPIs.
* **Advanced Formulas:** Implementation of `GETPIVOTDATA` for creating **Dynamic KPI Cards** that update instantly when Slicers are applied.
* **Calculated Metrics:** Custom fields for Tenure, Age Groups, and Attrition Rate calculation.

### Static View (High-Resolution Screenshot)
![HR Analytics Dashboard Final View](./Dashboard Screenshot.jpg)
