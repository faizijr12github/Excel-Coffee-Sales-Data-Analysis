# ☕ Coffee Sales Data Analysis (Excel Project)

This project demonstrates **Sales Data Analysis in Excel** using advanced formulas, formatting, pivot tables, and dashboards. The dataset contains customer, product, and order details, and the goal was to clean, transform, and analyze the data to extract meaningful business insights.

---

## 📂 Project Overview
The analysis focuses on customer orders, product details, and sales performance. Key steps included data cleaning, formula application, and creating an interactive dashboard for visualization.

---

## 🛠️ Data Preparation & Cleaning
1. **XLOOKUP Functions**
   - Retrieved **Customer Name** from the *Customers Table* into the *Orders Table*.
   - Retrieved **Email** from the *Customers Table* into the *Orders Table*.
   - Retrieved **Country** from the *Customers Table* into the *Orders Table*.

2. **INDEX + MATCH**
   - Fetched **Coffee Type** from the *Products Table* into the *Orders Table*.

3. **Data Standardization**
   - Applied **Multiple IF** statements to correct naming conventions:
     - `R → Robusta`
     - `M → Medium`
   - Formatted **Date** as `dd-mmm-yyyy` (e.g., `06-Sep-2024`) using `CTRL + 1`.
   - Converted **Coffee Size** to kilograms (e.g., `1 → 1.0 kg`) with custom format `0.0 "kg"`.
   - Converted **Unit Price** and **Sales** values to currency (e.g., `1200 → $1200`).
   - Checked and **removed duplicate records**.
   - Converted the entire **Orders Data** into an Excel Table (`CTRL + T`).

---

## 📊 Data Analysis (Pivot Tables)
- **Total Sales Over Time** – Analyzed monthly/annual sales growth.
- **Sales by Country** – Compared sales performance across countries.
- **Top 5 Customers** – Identified most valuable customers.

---

## 📈 Data Visualization
- Created **Pivot Charts** for visual insights.
- Built an **Interactive Dashboard** with slicers to filter by:
  - Coffee Size in kg
  - Roast Type
  - Loyalty Card

---

## 🖼️ Dashboard Preview
Here’s a snapshot of the interactive dashboard created in Excel:

<p align="center">
  <img width="1290" height="651" alt="image" src="https://github.com/user-attachments/assets/49adf406-824e-4bcd-b0c1-2a501c097557" />
</p>

---

## 🚀 Key Outcomes
- Improved understanding of global coffee sales trends.
- Identified top-performing countries and customers.
- Delivered a professional and interactive Excel dashboard for decision-making.

---

## 🧑‍💻 Tools & Skills Used
- **Microsoft Excel**
- **XLOOKUP, INDEX + MATCH, IF**
- **Data Cleaning & Formatting**
- **Pivot Tables & Pivot Charts**
- **Interactive Dashboards**

---

### ⭐ If you found this project insightful, consider giving it a star on GitHub!
