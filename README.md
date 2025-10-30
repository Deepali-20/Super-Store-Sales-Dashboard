# 📊 Super Store Sales Dashboard

An interactive **Power BI Dashboard** showcasing sales, profit, customer, and regional insights from the *Super Store Sales* dataset.
The project demonstrates advanced data visualization, DAX calculations, and business intelligence storytelling.

---

## 🧾 Dashboard Overview
 Power BI Dashboard

![Uploading Screenshot 2025-10-29 104930.png…]()


File: powerbi_dashboard/SuperStore_Sales_Dashboard.pbix
Preview:


✨ Dashboard Insights

### 🔹 **Key Metrics**

* **Total Sales:** ₹1.56M
* **Total Profit:** ₹192.89K
* **Total Quantity Sold:** 25K units
* **Average Discount:** 0.16

### 🔹 **Highlights**

* **Top Performing Categories:** Technology & Furniture
* **Most Profitable Sub-Categories:** Phones & Copiers
* **Highest Profit Region:** West (≈33% of total profit)
* **Peak Sales Month:** December — strong seasonal demand
* **Customer Insights:** Top customers like *Sean Miller* and *Tamara Chand* drive significant sales.

---

## 🧠 Key Insights

* 💰 **Technology and Furniture** dominate total sales.
* 🏆 **Phones & Copiers** yield the highest profit margins.
* 🌎 **West Region** leads in profitability.
* 📈 **December** marks peak sales — leverage for promotions.
* 🚚 Multiple shipping modes analyzed (*First Class, Second Class, Standard, Same Day*).
* 👥 Segmented by **Consumer**, **Corporate**, and **Home Office** customers.

---

## 🗂️ Dashboard Components

| Section                              | Description                                                  |
| ------------------------------------ | ------------------------------------------------------------ |
| **KPI Cards**                        | Displays Total Sales, Quantity, Profit, and Average Discount |
| **Profit by Sub-Category (Treemap)** | Visualizes profit contribution across sub-categories         |
| **Sales by Category (Bar Chart)**    | Compares Technology, Furniture, and Office Supplies          |
| **Sales by Month (Line Chart)**      | Shows seasonal sales trends                                  |
| **Profit by Region (Pie Chart)**     | Breakdown by East, West, Central, and South                  |
| **Customer Table**                   | Lists top customers and total sales                          |
| **Map Visualization**                | Displays city-wise regional sales                            |
| **Filters**                          | Dynamic filtering by Ship Mode, Segment, and Date Range      |

---

## ⚙️ Tools & Technologies

* **Power BI Desktop / Power BI Service**
* **Data Source:** Super Store Sales Dataset (CSV or Excel)
* **Techniques Used:**

  * Data Cleaning & Transformation using *Power Query*
  * Custom *DAX Measures* for KPIs
  * Interactive slicers and cross-filtered visuals
  * Dynamic time intelligence for monthly analysis

---

## 🧩 DAX Measures Used

```DAX
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Total Quantity = SUM(Sales[Quantity])
Average Discount = AVERAGE(Sales[Discount])
```

---

## 📈 Insights Summary

| Metric                    | Observation                              |
| ------------------------- | ---------------------------------------- |
| **Sales Trend**           | Rises sharply in Q4 (Nov–Dec)            |
| **Regional Profit**       | West contributes ≈33% of total profit    |
| **Category Comparison**   | Technology leads with ~₹0.56M sales      |
| **Customer Distribution** | Concentrated in key high-spending cities |
| **Discount Analysis**     | Lower discounts yield higher profits     |

---

## 📂 Repository Structure

```
📦 Super-Store-Sales-Dashboard
 ┣ 📊 SuperStore_Dashboard.pbix     # Power BI file
 ┣ 📄 Superstore_Sales_Data.xlsx     # Dataset
 ┣ 🖼️ Screenshot.png                 # Dashboard preview
 ┗ 📘 README.md                      # Documentation
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Load the dataset if not connected automatically.
4. Explore visuals, slicers, and regional filters interactively.

---

## 🧾 Author

**Created by:** [Deepali rai]
**Tool:** Power BI
**Purpose:** Data Analysis & Visualization Portfolio Project

---

⭐ If you find this project helpful, consider giving it a **star** and sharing feedback!
