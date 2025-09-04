# 📊 AI-Powered Supply Chain Data Automation & Analytics

## 🔹 Project Overview

This project automates the end-to-end process of extracting, storing, and analyzing supply chain data using **AI tools**. The system integrates **n8n** for workflow automation, **Supabase (PostgreSQL)** for cloud data storage, and **Quadratic** for AI-driven analytics and reporting.

The goal was to reduce manual data handling, improve reporting efficiency, and enable faster decision-making through real-time insights.

---

## 🔹 Tech Stack

* **n8n** → Workflow automation (email → database integration)
* **Supabase (PostgreSQL)** → Cloud database for structured storage
* **Quadratic** → AI-powered spreadsheet for analysis & visualization
* **CSV/Excel Files** → Raw input data (transactions, sales, inventory)

---

## 🔹 Workflow

1. **Data Ingestion**

   * Automated extraction of bank transactions & CSV files via **n8n**.
   * Transformation of data (date formatting, cleaning, mapping categories).
   * Storage into **Supabase PostgreSQL** tables (`fact_aggregate`, `fact_order_line`, etc.).

2. **Data Storage**

   * Database schema designed with **fact and dimension tables** (customers, products, orders).
   * Ensured primary keys and relationships for analytics-ready structure.

3. **Data Analysis**

   * Connected **Quadratic** to Supabase for real-time querying.
   * AI prompts used for:

     * Monthly revenue & expense trends
     * Inventory monitoring
     * Vendor performance
     * Order fulfillment insights

4. **Reporting & Insights**

   * Achieved **30% improvement in reporting efficiency**.
   * Reduced manual data handling time by **25%**.
   * Provided **business growth insights** for better decision-making.

---

## 🔹 Key Outcomes

* **Automated ETL** → No manual data entry required.
* **Real-time dashboards** → Faster access to KPIs.
* **Business impact** → Improved operational productivity & strategic planning.

---

## 🔹 Future Improvements

* Add **Slack/Email alerts** for anomalies (e.g., unexpected expenses).
* Extend to **forecasting models** (sales, expenses, demand).
* Integrate with **BI tools** (Power BI/Tableau) for richer dashboards.

---


👉 Would you like me to also **write a `README.md` file in proper GitHub markdown format** (with headings, emojis, and badges) so you can upload it directly to your GitHub repo?
