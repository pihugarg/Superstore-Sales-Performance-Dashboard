# 📊 Superstore Sales Performance Dashboard

An interactive **multi-page Power BI dashboard** built using the **Sample Superstore dataset** to analyze sales, profit, customer orders, product performance, discount impact, and regional trends. The dashboard provides actionable business insights through KPIs, interactive visualizations, slicers, custom tooltips, conditional formatting, and page navigation to support data-driven decision-making.

---

## 📌 Project Overview

The Superstore Sales Performance Dashboard is designed to help business users monitor overall performance, identify sales trends, evaluate product profitability, analyze the impact of discounts, and compare regional performance. The dashboard is organized into multiple interactive report pages, allowing users to explore business insights from executive, product, and regional perspectives.

---

## 🎯 Objectives

- Monitor key business KPIs.
- Analyze monthly and yearly sales performance.
- Compare sales and profit across product categories.
- Analyze product performance and discount impact.
- Identify high-performing and low-performing sub-categories.
- Evaluate regional and state-wise sales performance.
- Enable interactive analysis using slicers, page navigation, and custom tooltips.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- **Conditional Formatting**
- **Custom Report Tooltips**
- **Page Navigation**
- **Interactive Slicers**

---

## 📂 Dataset

**Dataset Used:** Sample Superstore Dataset

The dataset contains information about:

- Orders
- Sales
- Profit
- Quantity
- Discount
- Categories & Sub-Categories
- Customer Orders
- Product Details
- State & Region

---

# 📄 Dashboard Pages

## 🏠 Page 1 – Executive Dashboard

This page provides a high-level overview of business performance.

### KPI Cards

- 💰 Total Sales
- 📈 Total Profit
- 📊 Profit Margin
- 📦 Total Orders
- 🛒 Total Quantity
- 🏷️ Average Discount
- 💳 Average Order Value

### Interactive Visualizations

- 📈 Monthly Sales Trend
- 📊 Sales vs Profit Analysis
- 📅 Yearly Sales & Profit Overview
- 🛍️ Sales by Category
- 🌍 State-wise Sales & Profit
- 💹 Profit by Sub-Category
- 📦 Product Details
- 💰 Profit by Category

### Interactive Filters

- Region
- Year

---

## 📦 Page 2 – Product & Discount Analysis

This page focuses on product performance and profitability while evaluating the impact of discounts on business performance.

### KPI Cards

- 💰 Total Sales
- 📈 Total Profit
- 📅 Previous Year Sales
- 📊 YoY Sales Growth %
- 📈 Profit Margin
- 🏷️ Average Discount

### Interactive Visualizations

- 📉 Average Discount by Category
- 🎯 Discount vs Profit Analysis
- 💹 Profit by Sub-Category
- 🏆 Top 10 Products by Sales
- 📋 Business Insights

### Interactive Filters

- Category
- Sub-Category
- Discount

---

## 🌍 Page 3 – Regional Analysis

This page provides detailed insights into geographical business performance across different regions and states.

### Interactive Visualizations

- 🗺️ State-wise Sales Map
- 📈 Sales by Region
- 📉 Profit by Region
- 📊 Sales by State
- 💰 Profit by State
- 📋 Business Recommendations

### Interactive Filters

- Region
- State
- Year

---

## 💬 Custom Report Tooltip

A dedicated report tooltip provides quick state-level information when users hover over the map.

### Tooltip Includes

- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Orders
- 🛒 Total Quantity
- 📊 Profit Margin
- 🛍️ Sales by Category

---

## ✨ Key Features

- Multi-page Interactive Dashboard
- Interactive KPI Cards
- Dynamic Page Navigation
- Dynamic Slicers
- Monthly & Yearly Sales Analysis
- Product Performance Analysis
- Discount vs Profit Analysis
- Geographic Sales Analysis
- State-wise Performance Analysis
- YoY Sales Growth KPI
- Business Insights & Recommendations
- Custom Report Tooltips
- Conditional Formatting
- Clean and User-Friendly Dashboard Design

---

## 🎨 Conditional Formatting

Conditional formatting has been applied to the **Profit by Sub-Category** chart to improve readability and highlight business performance.

- 🟢 **Green Bars** → Positive Profit
- 🔴 **Red Bars** → Negative Profit (Loss)

This enables users to instantly identify profitable and loss-making product sub-categories.

---

## 📈 Key Business Insights

- Generated **$2.3M** in Total Sales.
- Achieved **$286.4K** Total Profit.
- Maintained a **12.47% Profit Margin**.
- Processed over **5,000 Orders**.
- Sold approximately **38K Products**.
- Technology is the highest-performing category.
- Higher discounts are associated with lower profitability across several product groups.
- Furniture contains multiple low-profit or loss-making sub-categories.
- California and New York are among the highest-performing states.
- Sales showed consistent growth from **2014–2017**, supported by the **YoY Sales Growth KPI**.

---

## 💡 Business Recommendations

- Review high-discount products to improve profitability.
- Increase focus on Technology products due to their higher profitability.
- Optimize pricing strategies in low-profit regions.
- Monitor regional performance regularly for better business decisions.
- Focus marketing efforts on high-performing states to maximize revenue.

---

# 📷 Dashboard Preview

## 🏠 Executive Dashboard

<<img width="1331" height="746" alt="Dashboard" src="https://github.com/user-attachments/assets/031de1b4-1199-4488-ba21-7541841d5280" />
>

---

## 📦 Product & Discount Analysis

<<img width="1342" height="745" alt="Product and Discount Analysis" src="https://github.com/user-attachments/assets/e1fb1b18-971e-4292-a4a2-35b026daa5f5" />


---

## 🌍 Regional Analysis

<<img width="1325" height="795" alt="Regional Analysis" src="https://github.com/user-attachments/assets/37760f12-1963-4734-b92b-a90c14c7f965" />
>

---
## Tooltip

<img width="465" height="397" alt="Tooltip" src="https://github.com/user-attachments/assets/e6bf3a7f-4137-4077-a1c6-9bd6b4ea6008" />



---

## 📁 Project Structure

```text
Superstore-Sales-Performance-Dashboard/
│
├── analysis/
│   └── Superstore Sales Performance Dashboard.pbix
│
├── assets/
│   ├── Executive_Dashboard.png
│   ├── Product_Discount_Analysis.png
│   ├── Regional_Analysis.png
│   └── State_Tooltip.png
│
├── data/
│   └── Orders.csv
│
├── docs/
│   └── Superstore_Sales_Performance_Report.pdf
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🚀 How to Use

1. Clone this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Navigate between the dashboard pages using the built-in page navigation buttons.
4. Apply filters using the Region, State, Category, and Year slicers.
5. Hover over the state map to view custom report tooltips.
6. Interact with the visuals to gain business insights.

---

## 📄 Project Report

A detailed project report explaining the Executive Dashboard, Product & Discount Analysis, Regional Analysis, KPIs, DAX measures, visualizations, and business insights is available in the **docs** folder.

---

## 👩‍💻 Author

**Pihu Gupta**

Passionate about **Data Analytics, Power BI, SQL, Python, and Business Intelligence**

**GitHub:** https://github.com/pihugarg

---

⭐ **If you found this project helpful, consider giving it a Star!**
