# 🛒 Shiva E‑Commerce Sales Dashboard (Power BI)

A fully interactive and professional Power BI dashboard built using a real-world **CSV dataset**, showcasing end‑to‑end data analysis, cleaning, modeling, and visualization. This project demonstrates practical data analytics skills used in business environments — including KPI tracking, customer insights, sales performance monitoring, and drill‑down reporting.

---

## 🚀 Project Overview

This E‑Commerce Sales Dashboard provides a complete analytical view of sales performance across:

* Revenue & Profit Trends
* Customer Purchase Behavior
* State‑wise & Category‑wise Sales Distribution
* Payment Mode Usage
* Monthly Profit Analysis
* Sub‑Category Profit Breakdown

The dashboard is designed to support **data‑driven decision making**, revealing key patterns, growth opportunities, and operational gaps.

---

## 📊 Key Features & Insights

### **1. Executive KPIs**

* **Sum of Profit**: 37K
* **Sum of Sales Amount**: 438K
* **Total Quantity Sold**: 5615
* **Average Order Value (AOV)**: 121K

### **2. Sales by State**

A horizontal bar chart comparing sales contribution from:

* Maharashtra (Highest)
* Madhya Pradesh
* Uttar Pradesh
* Delhi

### **3. Category‑wise Quantity Distribution**

A donut chart showing:

* **Clothing** – 63%
* **Electronics** – 21%
* **Furniture** – 17%

### **4. Monthly Profit Trend**

Includes positive and negative months, helping identify seasonal patterns.

### **5. Customer‑wise Sales**

Top performing customers (Harivansh, Madan Mohan, etc.) visualized using bar charts.

### **6. Payment Mode Insights**

Breakdown of payment modes:

* **COD** – 44%
* **UPI** – 21%
* **Debit/Credit Card** – 25%
* **EMI** – 10%

### **7. Sub‑Category Profit Analysis**

Printers, Bookcases, Saree, Accessories, and Tables analyzed for profitability.

---

## 🧰 Tools & Technologies Used

* **Power BI** – Data Modeling, DAX Measures, Visualizations
* **CSV Dataset** – Raw data source
* **Power Query** – ETL (Cleaning, Transformation)
* **DAX** – KPI Formulas & Calculations

---

## 🗂️ Project Structure

```
📁 PowerBI-Ecommerce-Sales-Dashboard
│
├── 📄 Sales_Dataset.csv
├── 📄 Ecommerce_Dashboard.pbix
├── 🖼️ Dashboard_Screenshot.png
└── 📄 README.md
```

---

## 🧮 DAX Measures Used

Some of the core DAX measures created in this project:

```DAX
Total Sales = SUM(Sales[Amount])

Total Profit = SUM(Sales[Profit])

Total Quantity = SUM(Sales[Quantity])

AOV = [Total Sales] / DISTINCTCOUNT(Sales[Order ID])
```

---

## 📝 How to Use This Dashboard

1. Download the `.pbix` file.
2. Open it using **Power BI Desktop**.
3. Explore filters like:

   * Quarter Selection (Q1–Q4)
   * Category Filters
4. Interact with charts to reveal insights through cross‑filtering.

---

## 📥 Dataset

The dataset is included as a CSV file and can be replaced with your own e‑commerce dataset.
Just ensure column names remain consistent.

---

## 📈 Key Learning Outcomes

By building this dashboard, I gained hands‑on experience in:

* Data transformation using Power Query
* Designing professional dashboards
* Creating business KPIs using DAX
* Visual storytelling with charts
* Understanding sales and customer behavior patterns

---

## 👨‍💻 Developed By

**Shiva – Data Analyst**
Passionate about Data Analytics, Power BI, SQL, and turning raw data into meaningful insights.

If you like this project, feel free to ⭐ star the repo!

---

## 📬 Contact

📧 Email: *[your-email@example.com](mailto:shivakumar110045@gmail.com)*

🐙 GitHub: *https://github.com/shiva-singh01*

---

## 📌 Screenshot
<img width="1304" height="780" alt="Screenshot 2025-12-12 053811" src="https://github.com/user-attachments/assets/12d5272e-a73f-49e1-9d2b-1f87bbe397fe" />


---

### 🙌 Thank You for Visiting!

If you're a recruiter or hiring manager, I’d love to connect and discuss data opportunities.
