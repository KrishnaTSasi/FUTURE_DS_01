# FUTURE_DS_01



# 🛒 Sales Analysis (2009–2010 Online Retail Dataset)

## 📌 Task

The objective of this project is to **analyze retail transaction data** from 2009–2010 and uncover key business insights such as:

* **Sales trends** over time
* **Top-performing products** by revenue and demand
* **Customer purchasing patterns**
* **Geographic sales distribution**

The goal is to translate raw sales data into **actionable insights** that can support decision-making in inventory management, marketing and strategy.

---

## 🛠️ Steps Taken

1. **Data Understanding**

   * Explored dataset with 8 columns (`InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country`).
   * Handled missing values and cancellations (invoices starting with 'C').

2. **Data Cleaning**

   * Removed negative/invalid quantities and prices.
   * Handled missing `CustomerID` entries.
   * Converted `InvoiceDate` into proper `datetime` format.

3. **Feature Engineering**

   * Created a new column `Revenue = Quantity × UnitPrice`.
   * Extracted `Year, Month, Day, Hour` from `InvoiceDate` for trend analysis.

4. **Exploratory Data Analysis (EDA)**

   * 📈 Sales trends over months
   * 🌍 Revenue distribution by country
   * 🎁 Top products by sales and revenue
   * 👥 Customer purchase frequency

5. **Visualization** (using **Plotly**)

   * Time series plots for sales trends
   * Bar charts for top products/customers
   * Geographic insights with country-level sales

---

## 📊 Key Insights & Interpretation

### 🔹 Sales Trends

* Sales show **seasonal peaks**, especially during **November–December**, aligning with holiday shopping.
* This highlights the importance of **stocking popular items** and **targeted campaigns during peak months**.

### 🔹 Top Products by Revenue

* **🏆 PAPER CRAFT, LITTLE BIRDIE** generated the **highest revenue (£168K+)**, making it the star performer.
* **🥈 REGENCY CAKESTAND 3 TIER** (£142K) and **🎀 WHITE HANGING HEART T-LIGHT HOLDER** (£100K+) also stand out as **bestsellers in home décor & kitchen categories**.
* Everyday items like **Manuals** and **Postage** ranked among top 10, showing **consistent demand**.

👉 **Insight**: A **small set of products drives a large share of total revenue**, making them critical for growth.

### 🔹 Customer Behavior

* A few **loyal customers contribute disproportionately to total sales**.
* **Frequent buyers + high-value products = key drivers of profitability**.

👉 **Insight**: Retention strategies (discounts, loyalty programs) can help maximize CLV (Customer Lifetime Value).

### 🔹 Geographic Insights

* Majority of sales come from the **UK**, but there’s significant international demand from **Germany, France, and the Netherlands**.

👉 **Insight**: Potential for **expansion in strong international markets**.

---

## 🚀 Conclusion

This analysis demonstrates how **data-driven retail insights** can guide:

* 📦 **Inventory management** → Keep top sellers stocked.
* 🎯 **Marketing strategy** → Focus campaigns on high-demand items & seasonal peaks.
* 🌍 **Market expansion** → Target international regions with proven demand.

By combining **time-series analysis, product-level performance and customer segmentation**, businesses can make **smarter, evidence-based decisions**.


