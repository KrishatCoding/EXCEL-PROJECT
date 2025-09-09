# 📊 Excel Project – Sales Performance Analysis  

## 📝 Overview  
This project is a **Sales Performance Analysis** built entirely in **Microsoft Excel**.  
It simulates a business scenario with interconnected datasets covering **customers, products, sales transactions, and sales representatives**.  

The project demonstrates:  
- Data cleaning & structuring in Excel  
- Analysis using **Pivot Tables, Charts, and Slicers**  
- Building an interactive **Dashboard** for decision-making  
- Applying **formulas, calculated fields, and conditional formatting**  

⚡ The data used in this project is **synthetic** and created solely for learning and practice purposes.  

---

## 📂 Files Included  
- **Excel Project.xlsx** → Main workbook containing all datasets, analysis, and dashboard  
- Sheets inside the workbook:  
  - `customer` – Customer details  
  - `products` – Product catalog with costs, prices, and profit margins  
  - `sales` – Sales transactions (orders, dates, reps, discounts, payments)  
  - `salesREP` – Sales representative details and performance metrics  
  - `Sales Analysis` – Pivot-based sales summaries (region, category, payment)  
  - `Customer Details` – Customer segmentation (gender, loyalty, city)  
  - `Stock Details` – Stock availability & low stock products  
  - `Supplier Details` – Seller targets, achievements, and ratings  
  - `Dashboard` – Interactive sales dashboard  

---

## 🗂️ Dataset Structure  

### 1️⃣ Customers (`customer`)  
- Customer_ID → Unique identifier for each customer  
- Customer_Name → Name of customer  
- Gender → Male / Female  
- Age → Customer age  
- City → City of residence  
- Loyalty_Level → Bronze, Silver, Gold  

---

### 2️⃣ Products (`products`)  
- Product_ID → Unique identifier for each product  
- Product_Name → Name of product  
- Category → Product category (Mobile, Tablet, Laptop, etc.)  
- Supplier → Supplier company  
- Unit_Cost → Cost price per unit  
- Unit_Price → Selling price per unit  
- Stock → Current stock availability  
- Profit_Margin → Margin per unit  

---

### 3️⃣ Sales Transactions (`sales`)  
- Sales_ID → Unique sales order ID  
- Customer_ID → Customer who placed the order  
- Product_ID → Product purchased  
- Order_Date → Date of order  
- Order_Status → Success / Cancelled  
- Quantity → Units sold  
- Rep_ID → Sales representative handling order  
- Product_Cost → Cost price  
- Selling_Price → Selling price  
- Discount% → Discount applied  
- After_Discount_Price → Final price after discount  
- Payment_Method → Card, Cash, Wallet, UPI, etc.  
- Region → Region of order  
- Profit_Margin → Profit per transaction  
- Order_Date (Year/Month/Quarter) → Extracted fields for time-series analysis  

---

### 4️⃣ Sales Representatives (`salesREP`)  
- Rep_ID → Unique sales rep ID  
- Rep_Name → Sales representative name  
- Region → Assigned sales region  
- Hire_Date → Date of joining  
- Performance_Rating → Rating (1–5)  
- Orders_Handled → Total orders managed  
- Target_Orders → Assigned sales targets  
- Target_Achievement_% → Achievement percentage  

---

## 🔍 Analysis & Dashboard  

The Excel workbook includes multiple analysis sheets with **Pivot Tables, Charts, and KPIs**:  

- **Sales Analysis** → Sales by region, payment method, and product category  
- **Customer Details** → Customer distribution by gender, loyalty, and city  
- **Stock Details** → Current stock levels & low stock alerts  
- **Supplier Details** → Seller targets, achievements, and ratings  
- **Dashboard** → Interactive dashboard with slicers for region, category, and time  

---

## 🚀 Getting Started  

1. Open **Excel Project.xlsx** in **Microsoft Excel (2016 or later)**  
2. Navigate through sheets:  
   - Use `customer`, `products`, `sales`, `salesREP` as raw data  
   - Explore analysis in `Sales Analysis`, `Customer Details`, `Stock Details`, `Supplier Details`  
   - Open `Dashboard` for an interactive experience  
3. Use slicers and filters to analyze different segments  

---

## 🎯 Learning Outcomes  

From this project, you will learn how to:  
- Connect and analyze multiple datasets in Excel  
- Create pivot tables & pivot charts for analysis  
- Apply formulas and calculated fields for business insights  
- Design an **interactive dashboard** in Excel  
- Perform **end-to-end business analysis** using only Excel  

---

## 📜 License  
This project is created for **educational purposes** and is free to use for practice, learning, and portfolio building.  
