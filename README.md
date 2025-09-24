# 🛒 Blinkit Sales Dashboard  

An interactive data visualization dashboard analyzing Blinkit's sales performance, outlet metrics, and customer behavior.  
This project provides **key business insights** into sales by outlet type, item category, fat content, location, and establishment year — enabling data-driven decision-making.  

---

## 📖 Short Description / Purpose  
The Blinkit Sales Dashboard was created to help business managers and analysts quickly identify **top-selling items, outlet performance, and revenue patterns**.  
It enables better **inventory planning, marketing strategy optimization, and performance tracking** across outlet locations and categories.  

---

## 🛠 Tech Stack  
This dashboard was built using the following tools and technologies:  
• 📊 **Power BI** – Primary data visualization platform for building reports and dashboards.  
• 📂 **Power Query** – For cleaning, transforming, and preparing the dataset.  
• 🧠 **DAX** – Used to calculate KPIs like Total Sales, Average Sales, and Average Rating.  
• 🗄️ **SQL** – Used for extracting, filtering, and aggregating data before visualization.  
• 📝 **Data Modeling** – Relationships were created between tables (sales, outlets, items) to allow interactive filtering and drill-down analysis.  
• 📁 **File Format** – `.pbix` (Power BI report) and `.png` (dashboard preview).  

---

## 📊 Data Source  
Dataset: **Blinkit Sales Dataset**  
Contains information about:  
- Outlet details (type, size, location, establishment year)  
- Items (category, fat content, visibility)  
- Sales data and ratings  

The data was cleaned and processed using **SQL** and Power Query before visualization.  

---

## 🌟 Features / Highlights  

### • Business Problem  
Retail businesses like Blinkit face challenges in understanding:  
- Which **outlets generate the most revenue**  
- Which **item categories drive the highest sales**  
- How **location type** and **outlet size** affect performance  
- Trends in sales over time  

### • Goal of the Dashboard  
To provide an **interactive, visual analytics tool** that:  
- Tracks **total sales, number of items, and ratings**  
- Identifies **top-performing outlets and categories**  
- Analyzes **sales contribution by fat content, outlet size, and type**  
- Helps make **strategic decisions for growth and marketing**  

### • Walkthrough of Key Visuals  
- **KPIs (Top Section)**  
  - **Total Sales:** `$1.20M`  
  - **Average Sales:** `$141`  
  - **Number of Items:** `8523`  
  - **Average Rating:** `3.9`  

- **Sales by Fat Content (Donut Chart)**  
  Shows revenue split between **Low Fat** and **Regular** items.  

- **Sales by Item Type (Bar Chart)**  
  Highlights top-selling categories like Fruits, Snacks, and Household items.  

- **Sales Over Time (Area Chart)**  
  Displays revenue trends based on outlet establishment year.  

- **Sales by Outlet Size (Donut Chart)**  
  Compares sales contributions of **Small, Medium, and Large** outlets.  

- **Sales by Outlet Location (Bar Chart)**  
  Shows Tier-wise revenue distribution (Tier 3 contributing the highest).  

- **Outlet Type Performance Table**  
  Compares Grocery Stores, Supermarkets (Type 1, 2, 3) on:  
  - Total Sales  
  - Number of Items  
  - Average Sales  
  - Average Rating  
  - Item Visibility  

---

## 💡 Business Impact & Insights  
- **Outlet Optimization:** Focus marketing efforts on Tier 3 outlets, as they generate the most revenue.  
- **Category-Level Strategy:** Invest more in top-selling categories like Fruits, Snacks, and Household items.  
- **Inventory Planning:** Maintain better stock levels for Regular Fat items, as they contribute the highest share.  
- **Performance Tracking:** Use establishment year trends to monitor outlet maturity and growth opportunities.  

---

## 🖼 Screenshots / Demo  
![Blinkit Dashboard Preview](https://github.com/RaushanPatel/Blinkit-Sales-Dashboard/blob/main/Blinkit%20Dashboard%20Screenshot.png)

---

## 🚀 How to Use  
1. Download or clone this repository:  
   ```bash
   git clone https://github.com/RaushanPatel/blinkit-sales-dashboard.git
