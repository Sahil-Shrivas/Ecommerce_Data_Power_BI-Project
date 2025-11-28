# Sahil Store — E-commerce Sales Dashboard (Power BI) 📊

**One-line summary:**  
Interactive Power BI sales dashboard built from ecommerce order and product details datasets — includes ready-to-open `.pbix` file, raw CSV data, and visual assets for quick analysis and presentation.

---

## 🔎 Project overview
This repository contains a complete Power BI dashboard project for an e-commerce storefront named *Sahil Store*. It’s intended as a demo and learning resource for analysts and BI enthusiasts who want to explore typical ecommerce KPIs (sales, orders, product performance, customer metrics) using Power BI Desktop. The project includes source CSV data, the published Power BI Desktop file (`.pbix`), and visuals/screenshots of the final dashboard. :contentReference[oaicite:1]{index=1}

---

## 📁 Repository structure
    Sahil-Store-Ecommerce-Data-Power-BI/
    ├── Sahil Ecommerce Sale Dashboard.pbix # Power BI Desktop file (dashboard + data model)
    ├── Orders.csv # Orders-level transactional data
    ├── Details.csv # Product / order line details
    ├── Dashboard Screenshot.png # Screenshot of the dashboard visuals
    ├── background image.jpg # Background/branding asset used in the report
    └── README.md # This file

---

## ✅ What you can do with this repo
- Open and explore a ready-made Power BI report (.pbix) showing common ecommerce KPIs:
  - Total sales, orders, average order value, units sold
  - Time-series sales trends (daily / monthly)
  - Product performance and top-sellers
  - Order-level and product-level drilldowns
  - Visual cards, charts, and filters for interactive exploration
- Reuse or adapt the provided dataset (CSV) for your own Power BI learning and demos.
- Inspect the data model, DAX measures, and visual design choices inside the `.pbix` file to learn report-building best practices.

---

## 📦 Data description
- **Orders.csv** — transactional header-level data (one row per order). Typical fields: order id, order date, customer or region fields, total order value, etc.
- **Details.csv** — order-line / product-level data (one row per product in an order). Typical fields: order id, product id/name, quantity, unit price, line total, category, etc.

> Note: Column names and exact fields may vary — open the CSV files to confirm schema before importing.

---

## 🛠 Prerequisites
- **Power BI Desktop** (Windows) — required to open and edit the `.pbix` file.  
  Download from the Microsoft Store or Microsoft Power BI website.
- A modern web browser to view screenshots or host any exported report pages.
- (Optional) Excel or a text editor to inspect / edit the CSV files.

---

## ▶️ How to open and explore
1. Install **Power BI Desktop** if you don't have it.  
2. Clone or download this repository:
   ```bash
   git clone https://github.com/Sahil-Shrivas/Sahil-Store-Ecommerce-Data-Power-BI.git
   cd Sahil-Store-Ecommerce-Data-Power-BI
3. Launch Power BI Desktop and open Sahil Ecommerce Sale Dashboard.pbix.
4. In Power BI:
   . Use the Data view to inspect loaded tables and columns.

   . Use the Model view to examine relationships and calculated measures (DAX).

   . Use the Report view to interact with visuals, slicers and drill-through pages.
5. If you prefer to build the report from scratch, import Orders.csv and Details.csv into Power BI and recreate visuals.
