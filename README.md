# Credit Risk & Loan Performance Insights Dashboard

## 📊 Project Overview
This Power BI dashboard provides a comprehensive analysis of loan portfolio performance and credit risk indicators. It is designed to help financial institutions monitor loan disbursement trends, track default rates (NPA), and identify high-risk segments in real-time.

### Key Metrics Tracked:
* **Total Disbursement:** ₹436M (118.6% growth over the year)
* **Avg Interest Rate:** 12.05%
* **Total Applications:** 39K
* **NPA Ratio (Default Rate):** 13.82%

---

## 🛠️ Technical Features
* **Dynamic Risk Gauge:** Implemented a custom gauge with conditional formatting rules: **Green** (<8%), **Yellow** (8-12%), and **Red** (>12%) to immediately flag critical risk levels.
* **Advanced Filtering:** Developed a **Top 5 Loan Purposes** Treemap using visual-level filters and integrated a **Smart Reset** button using Power BI Bookmarks to clear slicers while maintaining core visual states.
* **Data Visualization:** Utilized Trend Lines for disbursement growth, Donut Charts for purpose distribution, and horizontal Bar Charts for NPA counts by Credit Grade to ensure high scannability.

---

## 💡 Business Insights
Based on the data analysis, the following critical findings were identified:
1.  **Risk Concentration:** Default rates are significantly higher among borrowers with lower employment experience and those with **unverified income sources**.
2.  **Product Risk:** **Small Business** and **Credit Card** loans contribute the highest share of defaults, indicating a need for stricter risk mitigation in these segments.
3.  **Growth vs. Risk:** While loan disbursement shows a steady upward trend, the increasing NPA trend over time (from 8.1% to 13.8%) requires immediate portfolio rebalancing and tighter credit policies.

---

## 📂 Repository Structure
* **/finannce_load.pbix**: Contains the `.pbix` Power BI file.
* **/cleaned_financial_loan.xlsx**: Sample dataset used for the analysis.
* **/dashboard_ss.png**: High-resolution images of the final dashboard.

---

## 🚀 How to Use
1. Download the `.pbix` file from the `/finannce_load.pbix` folder.
2. Open it using **Power BI Desktop**.
3. Use the slicers on the right to filter by **State**, **Month**, or **Loan Tenure** to see how risk factors change across different segments.
