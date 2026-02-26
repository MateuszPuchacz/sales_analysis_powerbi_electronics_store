# sales_analysis_powerbi_electronics_store
Power BI sales performance dashboard using custom data model, DAX measures (including variables), Date Table and interactive visual design for retail and online sales analytics.
## 🎯 Project Goal

The goal of this project was to design a business oriented sales dashboard that enables leadership to monitor KPIs, evaluate profitability, and identify performance drivers.
Rather than focusing purely on visuals, the report was structured to answer key commercial questions and simulate a real world decision support environment.

## 📊 Data Source

The dataset used in this project was simulated for educational and portfolio purposes.  
It does not represent real company data.

The dataset consists of two primary tables: a transactional sales table and a product dimension table. It was synthetically generated to simulate a retail electronics sales environment.

### Sales (Fact Table)

Contains transaction-level sales records.  
Each row represents a single order.

Key fields:
- Order Number – unique transaction identifier  
- Sales Date – transaction date  
- Sales Channel – distribution channel (Online, In-Store, Wholesale)  
- Productindex – product reference key  
- Order qty – quantity sold  
- Unit price – selling price per unit  
- Unit cost – cost per unit  
- Sales – total revenue per transaction  

This table serves as the analytical core for revenue, cost, and profitability calculations.

---

### Products (Dimension Table)

Contains descriptive information about products.

Key fields:
- Index – product identifier  
- Product Name – product description  
- Product Category – product classification  

This table enables categorical analysis and segmentation of sales performance.

## 🛠 Tools & Technologies

**Excel**  
Dataset preparation, data cleaning, structuring, and validation before import into the BI environment.

**Power BI**  
Data modeling (relationships, star schema structure), DAX measure development, KPI calculations, and interactive dashboard design to support business analysis.

**AI Assisted Design (ChatGPT)**  
Generated visual branding assets (logo) for portfolio presentation purposes.


### Data Preparation & Modeling

**1. Excel – Data Quality Checks

Before importing the dataset into Power BI, a preliminary data quality check was performed in Excel to ensure consistency and reliability.

The following validations were completed:

Missing values check in key columns (Sales Date, Sales, Cost, Order Quantity, Sales Channel).

Data type verification:

Dates formatted as Date

Numeric fields (Sales, Cost, Unit Price) as Decimal Number

Quantities as Whole Number

Identifiers (e.g., Order Number) as Text

Logical consistency validation (e.g., no negative quantities or unrealistic values).

The objective was to ensure clean, structured input data before building the analytical model in Power BI.
