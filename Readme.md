# Customer & Sales Analytics Dashboard

An interactive **Power BI Business Intelligence dashboard** designed to analyze customer demographics, sales performance, transaction behavior, product performance, and profitability.

---

## 📌 Project Overview

This project transforms raw customer and transaction data into an interactive three-page Power BI dashboard.

The dashboard provides insights into:

* Customer demographics and segmentation
* Sales performance
* Product and brand performance
* Transaction behavior
* Geographic sales distribution
* Monthly sales and profit trends
* Profitability across different business dimensions

---

## 🎯 Aim

To develop an interactive dashboard that analyzes customer behavior, sales performance, transaction patterns, and profitability to provide meaningful business insights.

---

## 🎯 Objectives

* Analyze customer demographics based on gender, wealth segment, and job industry.
* Evaluate sales performance across states, brands, product lines, and product sizes.
* Compare transactions across different order approaches.
* Analyze monthly sales and profit trends.
* Identify profitability patterns across brands, states, products, and sales channels.
* Analyze new customer activity.
* Present business insights through interactive and easy-to-understand visualizations.

---

## 🗂️ Dataset

The project uses four related datasets:

| Dataset                  | Description                                                        |
| ------------------------ | ------------------------------------------------------------------ |
| **Customer Address**     | Customer location and property information                         |
| **New Customers**        | Newly acquired customer information and demographics               |
| **Customer Demographic** | Customer demographic, employment, wealth, and personal information |
| **Transaction**          | Transaction, product, pricing, cost, and order information         |

### Important Fields

* Customer ID
* Transaction ID
* State
* Gender
* Job Industry Category
* Wealth Segment
* Brand
* Product Line
* Product Size
* List Price
* Standard Cost
* Transaction Date
* Order Approach
* Online Order

---

# 📊 Dashboard

## Page 1 — Customer & Sales Overview

Provides an overall view of customer and sales performance.

### KPIs

* Total Sales
* Total Profit
* Total Customers
* New Customers

### Visualizations

* Sales by State
* Sales by Product Line
* Customers by Gender
* Customers by Wealth Segment

---

## Page 2 — Product & Transaction Analysis

Focuses on product performance and transaction behavior.

### KPIs & Visualizations

* Total Transactions
* Sales by Brand
* Sales by Product Size
* Transactions by Order Approach
* Sales by Month
* Customers by Job Industry
* Transactions by Product Line

---

## Page 3 — Profitability Analysis

Focuses on understanding business profitability.

### KPIs & Visualizations

* Total Profit
* Profit by Brand
* Profit by Order Approach
* Profit by State
* Profit by Product Line
* Profit by Product Class/Size
* Profit by Month

---

# 🧮 Key DAX Measures

### Total Sales

```DAX
Total Sales = SUM(transactions[list_price])
```

### Total Cost

```DAX
Total Cost = SUM(transactions[standard_cost])
```

### Total Profit

```DAX
Total Profit = [Total Sales] - [Total Cost]
```

### Total Customers

```DAX
Total Customers = DISTINCTCOUNT(transactions[customer_id])
```

---

# 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Excel / CSV**
* **Data Modeling**
* **Data Visualization**

---

# 🔄 Data Preparation & Modeling

The datasets were cleaned and prepared using **Power Query** before visualization.

The analysis uses relationships between customer and transaction information through **Customer ID**.

The data model enables analysis of transactions based on customer demographics, location, product information, and customer segments.

---

# 📸 Dashboard Preview

### Page 1 — Customer & Sales Overview
![Uploading Screenshot 2026-10-02 111450.png…]()


```text
![Customer & Sales Overview](images/page1.png)
```

### Page 2 — Product & Transaction Analysis
<img width="960" height="540" alt="Screenshot 2026-10-02 111459" src="https://github.com/user-attachments/assets/507d6eb0-65b2-4213-84b8-5a363f8b893d" />


```text
![Product & Transaction Analysis](images/page2.png)
```

### Page 3 — Profitability Analysis

<img width="960" height="540" alt="Screenshot 2026-10-02 111512" src="https://github.com/user-attachments/assets/dfb1296d-8bb6-4489-937e-adbaebd215a0" />


```text
![Profitability Analysis](images/page3.png)
```

---

# 📁 Project Structure

```text
Customer-Sales-Analytics/
│
├── Dataset/
│   ├── customer_address.csv
│   ├── new_customers.csv
│   ├── customer_demographic.csv
│   └── transaction.csv
│
├── Dashboard/
│   └── Customer_Sales_Analytics.pbix
│
├── Images/
│   ├── page1.png
│   ├── page2.png
│   └── page3.png
│
└── README.md
```

---

# 💡 Key Analysis Areas

The dashboard enables analysis of:

* Customer demographics
* Customer segmentation
* State-wise sales
* Brand performance
* Product performance
* Online vs. offline transactions
* Monthly sales trends
* Monthly profit trends
* New customer activity
* Profitability patterns

---

# 📌 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* Relationship Management
* DAX Measures
* KPI Development
* Business Intelligence
* Interactive Dashboard Design
* Data Visualization
* Business Data Analysis

---

# 👤 Project Information

**Project Type:** Data Analytics / Business Intelligence

**Tool:** Microsoft Power BI

**Focus:** Customer, Sales, Transaction & Profitability Analysis

