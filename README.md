# AdventureWorks Sales Analytics Dashboard

 📊 Project Overview

This project analyzes the AdventureWorks sales dataset to understand sales performance, product performance, customer behavior, and regional sales trends.
The project follows a complete Data Analytics workflow using **Excel, SQL, Power BI, and Tableau** to clean, analyze, visualize, and derive meaningful business insights from the data.
AdventureWorks is a Microsoft sample database containing business data related to customers, products, sales orders, sales territories, and other business operations.



 🎯 Project Objectives

* Analyze overall sales performance
* Identify top-performing products and product categories
* Analyze sales by region and territory
* Understand customer purchasing patterns
* Analyze sales trends over time
* Identify high-performing sales territories
* Create interactive dashboards for business reporting
* Generate insights that can support data-driven decision-making

---

 🛠️ Tools & Technologies

| Tool                | Purpose                                            |
| ------------------- | -------------------------------------------------- |
| **Microsoft Excel** | Data exploration, cleaning and initial analysis    |
| **MySQL**           | Data querying and analysis                         |
| **Power BI**        | Interactive dashboard and visualization            |
| **Tableau**         | Sales analytics visualization                      |
| **SQL**             | Data extraction, aggregation and business analysis |

---

 🔄 Project Workflow

```text
Raw AdventureWorks Data
        ↓
Data Exploration
        ↓
Data Cleaning & Transformation
        ↓
SQL Analysis
        ↓
Data Modeling
        ↓
Power BI / Tableau
        ↓
Dashboard Creation
        ↓
Insights & Business Findings
```

---

## 🧹 Data Preparation

The dataset was explored and prepared before visualization.

Key activities included:

* Understanding tables and columns
* Checking data types
* Identifying missing or inconsistent values
* Removing unnecessary data
* Checking duplicate records
* Formatting date fields
* Creating calculated fields
* Joining related tables
* Preparing data for visualization

The AdventureWorks database contains sales-related tables such as customers, sales orders, sales order details, salespeople, products, and sales territories.

---

## 🗄️ SQL Analysis

SQL was used to perform business-oriented analysis such as:

* Total sales analysis
* Sales by product
* Sales by category
* Sales by territory
* Monthly and yearly sales trends
* Top-performing products
* Customer analysis
* Regional performance
* Salesperson performance

### Example SQL Analysis

```sql
SELECT 
    YEAR(OrderDate) AS Year,
    SUM(TotalDue) AS Total_Sales
FROM Sales.SalesOrderHeader
GROUP BY YEAR(OrderDate)
ORDER BY Year;
```

---

## 📈 Power BI Dashboard

The Power BI dashboard provides an interactive view of sales performance.

### Key KPIs

* **Total Sales**
* **Total Orders**
* **Total Customers**
* **Total Products**
* **Average Order Value**
* **Sales Growth**

### Dashboard Visualizations

* Sales trend by year/month
* Sales by product category
* Top products by sales
* Sales by territory
* Customer analysis
* Order analysis
* Category-wise performance
* Geographic/Regional sales performance

### Interactive Features

* Slicers
* Filters
* Drill-down
* Cross-filtering
* KPI cards
* Interactive charts

---

## 📊 Tableau Dashboard

A Tableau dashboard was also created to visualize the AdventureWorks sales data.

The dashboard focuses on:

* Sales trends
* Product performance
* Category performance
* Regional sales
* Customer analysis
* Top-performing products

Tableau was used to create an alternative visualization of the same business data and explore interactive analytical views.

---

## 💡 Key Insights

The analysis focuses on identifying:

* Products generating the highest sales
* Product categories contributing significantly to revenue
* Territories with strong sales performance
* Changes in sales over time
* Customer purchasing patterns
* Products or regions requiring further analysis
* Differences in performance across categories and territories

> **Note:** Specific numerical findings depend on the AdventureWorks dataset/version used for this project.

---

## 📂 Project Structure

```text
AdventureWorks-Sales-Analytics/
│
├── Excel/
│   └── AdventureWorks_Data.xlsx
│
├── SQL/
│   └── AdventureWorks_Analysis.sql
│
├── PowerBI/
│   └── AdventureWorks_Sales_Dashboard.pbix
│
├── Tableau/
│   └── AdventureWorks_Sales_Dashboard.twbx
│
├── Screenshots/
│   ├── PowerBI_Dashboard.png
│   └── Tableau_Dashboard.png
│
└── README.md
```

---

## 📸 Dashboard Preview

### Power BI Dashboard

Add your dashboard screenshot here:

```markdown
![Power BI Dashboard](Screenshots/PowerBI_Dashboard.png)
```

### Tableau Dashboard

Add your Tableau screenshot here:

```markdown
![Tableau Dashboard](Screenshots/Tableau_Dashboard.png)
```

---

## 🧠 Skills Demonstrated

* Data Cleaning
* Data Analysis
* SQL
* Excel
* Power BI
* Tableau
* Data Visualization
* KPI Development
* Data Modeling
* Dashboard Development
* Business Insights
* Analytical Thinking

---

## 📌 Project Outcome

This project demonstrates an end-to-end **Data Analyst workflow**, starting from raw business data and progressing through data preparation, SQL analysis, visualization, dashboard development, and insight generation.
It showcases practical experience in using multiple analytics tools to transform raw sales data into meaningful and interactive business reports.



## 👩‍💻 Author

**Vaishnavi Wandhekar**
**Data Analyst | SQL | Excel | Power BI | Tableau | Python**


