# 📊 CRM Sales Opportunities Insights Using SQL  

This project explores **CRM sales data** using **PostgreSQL** to uncover valuable business insights — from sales performance to deal cycle analysis.  
The dataset is provided by **[Maven Analytics](https://www.mavenanalytics.io/)** and focuses on understanding how sales agents, products, and accounts contribute to overall company performance.  

---

## 🧠 Project Objective  
To analyze a CRM sales pipeline dataset using SQL and extract key insights such as:  
- Top-performing **products** and **accounts**  
- **Win rate** and **sales performance** by agent  
- **Average sales cycle duration**  
- **Sector-wise** and **regional** sales trends  
- **Monthly revenue** and deal trends  

---

## 🗂️ Dataset Overview  

The dataset consists of five related tables:  

| Table | Description |
|--------|--------------|
| **accounts** | Contains company details like sector, size, and revenue |
| **products** | Product information including series and price |
| **sales_teams** | Sales agents, their managers, and regional offices |
| **salespipeline** | Opportunities with dates, values, and deal stages |
| **data_dictionary** | Metadata describing the fields and tables |

---



## 🧮 SQL Analysis Performed

### 🔹 Beginner-Level Queries

* List open opportunities (`close_date IS NULL`)
* Display first 10 rows of sales pipeline
* Count opportunities by account

### 🔹 Intermediate-Level Queries

* Total deal value by sales agent
* Top 5 products by total deal value
* Opportunities that took more than 60 days to close
* Agents managed by *Dustin Brinkmann*

### 🔹 Advanced-Level Queries

* Average deal value per sector
* Top 3 accounts by total closed deal revenue
* Sales agent with the shortest average sales cycle
* Win rate per sales agent
* Monthly sales trend report

---

## 📈 Key Insights

* **GTX product series** achieved the highest average deal value.
* **Dustin Brinkmann’s team** consistently performed across regions.
* Average **sales cycle duration** varied by agent, helping identify process bottlenecks.
* Clear **monthly growth trends** and **seasonal fluctuations** in deal closures.

---

## 💡 Tools Used

* **PostgreSQL** — Database and query engine
* **Maven Analytics Dataset** — Source of CRM sales data
* **SQL Window Functions** — Ranking and trend analysis
* **Joins & Aggregations** — Relationship-based insights

---

## 🚀 How to Run

1. Clone the repository or download the SQL scripts.
2. Create the database and tables in **PostgreSQL** using the provided `CREATE TABLE` scripts.
3. Use the `\copy` command to import CSV files into each table.
4. Run the SQL queries in sequence to reproduce the analysis.

---

## 🙌 Acknowledgment

Special thanks to **Maven Analytics** for providing the dataset that made this project possible.


