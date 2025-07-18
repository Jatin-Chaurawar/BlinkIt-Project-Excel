# 📊 BlinkIT Data Analysis Project

This repository contains an end-to-end **Power BI project** based on BlinkIT's operations dataset. The project demonstrates data modeling, KPI development, and interactive report building to uncover insights that can support business decision-making.

---

## 📁 Dataset Overview

The data was sourced from internal BlinkIT systems and provided in an Excel format. It contains the following key information:

- **Orders**: Order ID, timestamps, values  
- **Products**: Product details and categories  
- **Customers**: Demographics and customer IDs  
- **Stores**: Store locations and performance  
- **Employees**: Sales rep and manager details  
- **Sales**: Sales metrics, profit, discounts, revenue  
- **Others**: Delivery times, ratings, feedback  

---

## 🏗️ Power BI Features

### 🧱 Data Model

- Star Schema with multiple **Dimension Tables**:
  - `dim_Date`
  - `dim_Product`
  - `dim_Customer`
  - `dim_Store`
  - `dim_Employee`
  - `dim_Salary`
- Central **Fact Table** for `Sales`, `Orders`, or `Transactions`

---

### 📌 KPIs Developed

- Total Revenue  
- Total Orders  
- Average Order Value (AOV)  
- Gross Margin %  
- Sales by Category/Region  
- Top 10 Products by Sales  
- Customer Retention Rate  
- Delivery Time Average  
- Order Return Rate  
- Employee Performance  

---

## 📈 Visuals & Dashboards

The project includes **10+ dynamic charts** such as:

- 💹 Revenue Trend (Line Chart)  
- 🛒 Top Selling Products (Bar Chart)  
- 🌐 Sales by Region (Map)  
- 🧮 Orders by Time Period (Area Chart)  
- 📦 Product Category Distribution (Pie Chart)  
- ⏰ Delivery Times (Box Plot)  
- 💰 Profit vs Discount (Scatter Plot)  
- 📆 Monthly Customer Growth (Line/Area)  
- 📊 Employee-wise Sales (Bar Chart)  
- 🧭 Interactive Slicers (Date, Category, Store)  

---


---

## 🎯 Project Goals

- Learn and apply dimensional modeling in Power BI  
- Create meaningful KPIs for a business context  
- Build clean, user-friendly interactive dashboards  
- Simulate real-world analytics scenario for BlinkIT  

---

## 🧠 Learnings

- Power BI modeling using relationships and DAX  
- Data cleaning and transformation with Power Query  
- Designing dashboards for storytelling  
- Creating reusable measures and calculated columns  

---

## 🚀 How to Use

1. Download the `.pbix` file from this repo (or clone and build it yourself)  
2. Open in Power BI Desktop  
3. Connect the provided Excel file as source if needed  
4. Explore dashboards and play with slicers!  

---

## 📎 File Structure

