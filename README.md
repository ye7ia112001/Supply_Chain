# 📈 Supply Chain Performance Dashboard (Power BI)

## 📊 Overview 

This project features a comprehensive Power BI dashboard designed to monitor and analyze key performance indicators (KPIs) across a product supply chain. It integrates financial, logistical, and operational data to provide actionable insights for executive decision-making.

The dashboard structure follows best practices for data visualization, utilizing a dark theme for high contrast and readability.

---

## 🛠️ Project Goals & Technical Highlights 

### Project Goals:

* **Diagnose Bottlenecks:** Identify areas of inefficiency, such as long shipping times for specific product types (e.g., Skincare).
* **Assess Profitability:** Clearly show the most and least lucrative product categories (Skincare leads revenue).
* **Measure Performance vs. Target:** Compare the actual overall satisfaction rate (2.28) against the target (3.00).

### Technical Highlights:

* **Data Modeling:** Employed a robust Star Schema architecture to ensure data integrity and efficient filtering.
* **Complex DAX Measures:** Developed advanced DAX logic to calculate core KPIs, including:
    * `Total Revenue Generated`: The sum of generated revenue, filtered by location and product type.
    * `Total Product Sold`: Aggregation of units sold, used for distribution analysis.
    * `Average Lead Time`: Calculated average delivery lead time (14.77 days).
    * `Average Satisfaction Score`: Calculated based on underlying quality/inspection results to derive the overall satisfaction rate of 2.28.

---

## 🔍 Key Insights & Analytical Report 

The analysis derived from this dashboard is crucial for strategic planning (Refer to the attached `Supply Chain Report.jpg` for detailed notes):

1.  **Financial Drivers:** **Skincare** is the undisputed most lucrative category, significantly contributing to the total revenue.
2.  **Operational Performance:**
    * **Satisfaction Gap:** The overall customer satisfaction rate (2.28) is short of the target (3.00).
    * **Logistics:** **Route A** is the preferred transport route (facilitating over 43% of products), with **Roadways** being the primary transportation mode.
    * **Geographic Focus:** **Mumbai** is the top revenue generator, while **Kolkata** leads in the volume of products sold.

---

## 💻 Visualizations 
The dashboard includes key visuals for diagnostics:

* **Product Price vs. Revenue:** (Line and Column Chart) Analyzing price impact on revenue across product types.
* **Products & Revenue by Location:** (Clustered Column Chart) Comparing financial output against sales volume across different cities (e.g., Mumbai vs. Kolkata).
* **Products by Routes/Transportation:** (Donut Charts) Showing the distribution of products across different routes and transportation modes.
* **Overall Satisfaction Gauge:** Direct performance measure against the set target.

---

## 📁 File Structure 

* `Supply Chain Dashboard.pbix`: The Power BI Report file.
* `RawData.xlsx`: The original data source files (simulated).
* `Supply Chain Report.jpg`: A visual summary of the key findings.
* `33.png`: Detailed chart snapshot.

---
