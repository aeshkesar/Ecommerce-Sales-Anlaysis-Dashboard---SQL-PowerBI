# 🚴 Adventure Works Sales Analytics Dashboard | Power BI

## 📌 Project Overview

This project is a comprehensive Business Intelligence solution built using Power BI on the Adventure Works dataset.

The dashboard enables business stakeholders to monitor sales performance, customer behavior, product profitability, return rates, and geographical sales distribution through an interactive self-service reporting experience.

The solution leverages advanced Power BI development techniques including Snowflake Schema data modeling, DAX calculations, Row-Level Security (RLS), Drill Through, Drill Down, Custom Tooltips, Smart Narrative, Bookmarks, Dynamic Navigation, and Time Intelligence reporting.

---

# 🎯 Business Problem

Adventure Works generates sales across multiple product categories, customer segments, and geographical territories.

Business users needed answers to critical questions such as:

* Which products generate the highest revenue and profit?
* Which customers contribute most to overall sales?
* How are returns impacting profitability?
* Which regions are driving growth?
* Are revenue and profit targets being achieved?
* How do sales trends change over time?
* Which customer segments should be targeted for future campaigns?

Traditional reporting methods relied on static reports and manual analysis, making it difficult to obtain timely and actionable insights.

---

# 💡 Solution

Developed an interactive Power BI dashboard that provides:

* Executive-level KPI monitoring
* Customer analytics
* Product performance analysis
* Geographic sales intelligence
* Return analysis
* Trend analysis
* Self-service reporting capabilities

The dashboard allows users to move from high-level summaries to transaction-level insights using advanced navigation and drill-through functionality.

---

# 🏗 Data Model Architecture

## Snowflake Schema Design

The data model was designed using a Snowflake Schema architecture.

### Why Snowflake Schema?

The Snowflake Schema was selected to:

* Reduce data redundancy
* Improve data consistency
* Normalize hierarchical dimensions
* Support scalable warehouse-style modeling
* Demonstrate enterprise BI architecture concepts

Examples:

### Product Hierarchy

Product Category
→ Product Subcategory
→ Product

### Customer Geography

Region
→ Territory
→ Customer

This approach separates business entities into multiple related dimensions rather than storing all attributes in a single denormalized table.

Although Star Schema is generally preferred for reporting performance, Snowflake Schema was intentionally implemented to showcase advanced dimensional modeling concepts and real-world warehouse design practices.

---

# 📊 Dashboard Pages

## 1️⃣ Executive Dashboard

Provides a high-level overview of business performance.

### KPIs

* Total Revenue
* Total Profit
* Total Orders
* Return Rate

### Insights

* Weekly Revenue Trend
* Moving Average Analysis
* Orders by Category
* Top Products Performance
* Monthly Revenue Trends
* Monthly Orders Trends
* Monthly Returns Trends

---

## 2️⃣ Customer Analytics Dashboard

Customer-centric reporting and segmentation.

### Metrics

* Unique Customers
* Revenue Per Customer
* Top Customer Analysis

### Insights

* Customer Growth Trends
* Income-Level Segmentation
* Occupation-Based Analysis
* Top 100 Customer Ranking
* Customer Revenue Contribution

---

## 3️⃣ Product Analytics Dashboard

Product performance and profitability monitoring.

### Metrics

* Product Revenue
* Product Profit
* Product Returns

### Insights

* Orders vs Target
* Revenue vs Target
* Profit vs Target
* Product Trend Analysis
* Product Return Analysis

---

## 4️⃣ Geographic Sales Dashboard

Location-based performance tracking.

### Features

* Interactive Map Visualizations
* Territory Filtering
* Regional Sales Distribution
* Geographic Performance Analysis

---

# 🚀 Advanced Power BI Features Implemented

## Custom Tooltips

Created dedicated tooltip pages displaying:

* Revenue
* Profit
* Orders
* Return Rate
* Trend Visualizations

This provides additional context without requiring navigation away from the report page.

---

## Drill Down

Implemented hierarchical exploration including:

* Year → Quarter → Month → Week
* Category → Subcategory → Product

Users can investigate trends at multiple levels of granularity.

---

## Drill Through

Dedicated detail pages for:

* Customer Analysis
* Product Analysis

Allows users to investigate specific entities directly from summary reports.

---

## Bookmarks & Navigation

Implemented:

* Custom Navigation Menu
* Dynamic Page Switching
* Interactive Buttons
* Improved User Experience

---

## Smart Narrative

Automatically generates business summaries explaining:

* KPI Performance
* Revenue Trends
* Growth Patterns
* Business Insights

---

## Row-Level Security (RLS)

Implemented role-based security to ensure users can access only authorized data.

Example Roles:

* Executive Users
* Regional Managers
* Sales Representatives

---

## Dynamic Interactions

* Cross Filtering
* Cross Highlighting
* Sync Slicers
* Interactive Visual Behavior

---

# 📈 DAX Measures Created

## Sales Metrics

* Total Revenue
* Total Profit
* Total Orders
* Return Rate %

## Customer Metrics

* Revenue Per Customer
* Customer Count
* Customer Ranking

## Product Metrics

* Product Revenue
* Product Profit
* Product Return Rate

## Time Intelligence

* Year-to-Date Revenue
* Month-to-Date Revenue
* Previous Month Revenue
* Growth Percentage
* 4 Week Moving Average

## Ranking Measures

* Top N Customers
* Top N Products

---

# 🎨 Dashboard Design Highlights

* Custom Sidebar Navigation
* Modern KPI Cards
* Responsive Layout
* Interactive Visuals
* Consistent Color Palette
* Executive-Friendly Reporting Design
* Business-Oriented Storytelling

---

# 📊 Business Outcomes Achieved

### Improved Decision Making

Provided executives with a centralized platform for monitoring critical business KPIs.

### Reduced Reporting Effort

Eliminated manual spreadsheet-based reporting and consolidated analytics into a single dashboard.

### Faster Root Cause Analysis

Drill-through functionality allows stakeholders to quickly investigate performance anomalies.

### Better Customer Understanding

Identified high-value customer segments and revenue-driving customer groups.

### Product Optimization

Highlighted top-performing and high-return products for strategic decision-making.

### Enhanced Regional Visibility

Enabled geographic performance monitoring for territory-based planning and resource allocation.

### Secure Data Governance

Implemented Row-Level Security to ensure controlled data access.

---

# 🛠 Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* Snowflake Schema
* Power BI Service
* Row-Level Security (RLS)
* Bookmarks
* Smart Narrative
* Custom Tooltips

---

# 📂 Repository Structure

AdventureWorks-PowerBI-Dashboard/

├── Data/

├── PowerBI/

│ └── AdventureWorks_Dashboard.pbix

├── Screenshots/

│ ├── Executive_Dashboard.png

│ ├── Customer_Dashboard.png

│ ├── Product_Dashboard.png

│ └── Geography_Dashboard.png

├── Documentation/

└── README.md

---

# 👨‍💻 Skills Demonstrated

* Business Intelligence
* Advanced Power BI
* Data Modeling
* DAX Optimization
* KPI Design
* Data Storytelling
* Dashboard Development
* Dimensional Modeling
* Row-Level Security
* Drill Through Analytics
* Customer Analytics
* Product Analytics

---

## ⭐ Key Takeaway

This project demonstrates how advanced Power BI capabilities can transform raw sales data into actionable business insights through scalable data modeling, interactive analytics, and enterprise-grade reporting practices.
<img width="1332" height="742" alt="image" src="https://github.com/user-attachments/assets/3b55eef7-c699-4b7d-8db3-e9f9b03058bc" />
<img width="1327" height="747" alt="image" src="https://github.com/user-attachments/assets/23ea4f18-e948-43ee-8ac6-92742b8ae8d6" />

<img width="1327" height="740" alt="image" src="https://github.com/user-attachments/assets/7c9be6b8-9da4-4bae-aee0-b87c827c3dc3" />
<img width="1330" height="750" alt="image" src="https://github.com/user-attachments/assets/eee43099-b040-4d3a-9b8f-efac0d5ca5ff" />
<img width="1332" height="745" alt="image" src="https://github.com/user-attachments/assets/fe8893e6-d6e2-4a9f-9f74-ac98574842ed" />


