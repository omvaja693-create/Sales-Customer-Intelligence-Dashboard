# 📊 Power BI Data Analytics & Dashboard Project

## 📝 Project Overview
This project involves the development of a comprehensive Power BI dashboard designed to provide actionable insights into sales performance, customer trends, and operational metrics. The report focuses on a user-friendly experience with advanced navigation, mobile optimization, and robust data modeling techniques.

## 🛠️ Key Features & Workflows

### 1. 🗂️ Data Modeling
* **Star Schema Architecture:** Established a clean and efficient Star Schema layout.
* **Relationships:** Created robust relationships between Fact and Dimension tables using Primary and Foreign Keys.
* **Optimization:** Hid unnecessary fields to maintain a clean report view and ensure consistent naming conventions.

### 2. 🧮 DAX Measures & Calculations
* **Advanced Measures:** Developed complex measures using DAX functions including `CALCULATE`, `FILTER`, `ALL`, `SUMX`, `COUNTX`, and `AVERAGEX`.
* **KPI Classification:** Implemented `SWITCH` logic to categorize Key Performance Indicators dynamicially.
* **Data Joins:** Used `RELATED` to fetch data across tables.
* **Calculated Columns:** * Profit Margin Classification.
    * Customer Full Names (First + Last concatenation).
    * Year-Month formatting for time series analysis.

### 3. 📅 Time Intelligence
* Implemented Time Intelligence functions to track performance over time:
    * **YOY (Year-Over-Year)**
    * **MOM (Month-Over-Month)**
    * **YTD (Year-To-Date)** for sales and returns.
* Identified and visualized seasonal trends.

### 4. 📈 Dashboard Layout & Visualization
* **Visual Mix:** Utilized a variety of visuals including Cards, KPI Cards, Line Charts, Bar Charts, and Donut Charts.
* **Forecasting:** Incorporated Trend lines and sales forecasts.
* **Matrix Visuals:** structured Matrix views for detailed tabular data analysis.
* **Top N Analysis:** Highlighted "Top N Products by Sales" and "Top N Customers by Profit".

### 5. 🖱️ Filtering & Interaction
* **Slicers:** Added slicers for Product, Customer Segment, Region, and Date to allow dynamic filtering.
* **Drill Capabilities:** Enabled Drill Up/Down and Drillthrough filters for deeper data exploration.
* **Parameters:** Implemented Numeric Range Parameters for custom user-driven filtering.

### 6. 🧭 Navigation & UX
* **Custom Navigation:** Built a page navigation system using Custom Buttons and Bookmarks.
* **Slicer Panel:** Designed a collapsible Slicer Panel to maximize canvas space.
* **Tooltips:** Enabled report tooltips to show mini visual summaries on hover.

### 7. 📱 Mobile Layout
* **Responsive Design:** Optimized key report pages for mobile viewing.
* **Mobile Priorities:** Prioritized KPI Cards and Top N visuals for quick insights on the go.

### 8. 🔒 Security
* **Row-Level Security (RLS):** Simulated RLS to restrict data views based on region.
* **Roles:** Created specific roles for Region Managers to ensure data governance.

## 🚀 How to Use
1.  Download the `.pbix` file.
2.  Open the file in **Power BI Desktop**.
3.  Use the **Slicer Panel** to filter data by region or date.
4.  Ctrl+Click the navigation buttons to switch between Main, Detail, and Drillthrough pages.

---
*Created by [Your Name]*
