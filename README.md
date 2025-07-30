# Finance-Dashboard-Power-BI

#### **Objective**

The Finance Dashboard project was developed to provide a centralized and visual representation of an individual's or organization's financial performance over time. The key goal of this project was to enable better **financial planning, budgeting, and savings optimization** through the use of data analytics and visualization. The dashboard focuses on key financial indicators such as **Income %, Expenses %, Savings %, and Expense vs Savings %**, and breaks down the monthly performance using interactive charts and filters.

---

#### **Key Features**

The Power BI dashboard created in this project provides deep insights into financial health using the following features:

* **KPIs Overview:**
  Display of core KPIs such as:

  * **Income (Monthly/Total)**
  * **Expenses (Monthly/Total)**
  * **Savings (Monthly/Total)**
  * **Savings %** – percentage of income saved
  * **Expense vs Savings %** – comparative insight for strategic budgeting

* **Trends Over Time:**

  * Line graph showing **monthly trends** in income, expenses, and savings.
  * Easy identification of financial dips or spikes for better financial retrospection.

* **Category-wise Expense & Savings Distribution:**

  * **Donut Charts** show percentage distribution across expense categories (e.g., EMIs, Rent, Food, Health, Leisure) and savings components (e.g., Liquid Cash, Mutual Funds, Fixed Deposits).
  * Helps pinpoint overspending or underutilized savings instruments.

* **Detailed Expense Table by Year:**

  * Year-wise breakdown of all major expenses from 2021 to 2024.
  * Shows total values and specific amounts for each component like shopping, travel, EMIs, rent, and more.

* **Time & Year Filters:**

  * Users can **filter data by month and year** (2021 to 2024) using intuitive slicers.
  * Enables users to isolate trends and metrics for specific periods.

* **Visual KPIs with Conditional Formatting:**

  * Highlights monthly change trends in income, expenses, and savings using color-coded percentages (e.g., +7%, -2%) for quick understanding.

---

#### **Process**

* **Data Collection:**

  * Sourced from a structured **Excel file** containing raw financial records over multiple years (2021–2024).

* **Data Cleaning & Transformation:**

  * Unnecessary columns were removed.
  * Missing or null values were handled.
  * Aggregated and categorized data (e.g., by month, year, expense category).
  * Used **Power BI Query Editor** for transformation.

* **Metric Derivation using DAX:**

  * Custom metrics such as:

    * `Total Savings = Income - Expenses`
    * `Savings % = (Savings / Income) * 100`
    * `Expense vs Savings %` comparison
    * Calculated values for month-on-month changes

* **Dashboard Development:**

  * Built using **Power BI visual tools** (line graphs, donut charts, cards, and tables).
  * Used interactive slicers for user-controlled analysis.
  * Implemented **card visuals for key KPIs** with conditional indicators.

---

#### **Technologies Used**

* **Power BI:** For creating the interactive dashboard and data visualizations
* **Excel:** Source of historical financial data
* **Power BI Query Editor:** For cleaning and shaping the data
* **DAX (Data Analysis Expressions):** To calculate key metrics and KPIs

---

#### **Files and Structure**

* **Excel File: <a href="Finance Dataset.xlsx">Dateset</a>
  Contains:

  * Monthly and yearly income and expense data
  * Categorized breakdowns for both expenses and savings

* **Power BI File:**

  * Contains the complete interactive Finance Dashboard with all visuals, filters, and logic implemented

---

#### **How to Use**

1. Open the **Power BI dashboard file** using Power BI Desktop.
2. Make sure the Excel data source is in the same directory, or update the path inside Power BI.
3. Use filters to switch between months and years or analyze specific KPIs.
4. Hover over visuals to gain insights into specific data points.

---

#### **Future Improvements**

* **Real-Time Integration:**

  * Integrate with APIs like bank statements or budgeting apps for live updates.

* **Financial Goal Tracking:**

  * Add modules to track progress toward goals (e.g., retirement, emergency fund, travel fund).

* **Alert Triggers & Budget Warnings:**

  * Set automated alerts if monthly expenses exceed a limit or savings drop below a threshold.

* **Mobile-Optimized Dashboard:**

  * Develop a responsive version for mobile users to track finances on the go.

---

#### **Conclusion**

This **Finance Dashboard** project empowers individuals or small teams to understand and manage their financial health through **data-driven insights and interactive visuals**. By tracking trends in income, expenses, and savings, users can make informed decisions, optimize spending, and stay on track with financial goals. The project is a strong foundation for deeper integration with budgeting tools or financial forecasting models in the future.

