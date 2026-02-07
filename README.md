# Python + SQL E-Commerce Data Analysis Project

## Project Overview
This project analyzes an E-commerce dataset using **PostgreSQL** and **Python**. The main objective is to extract business insights by performing SQL-based data analysis and visualizing results using Python.

The project demonstrates real-world data analytics workflow including database querying, business analysis, and visualization.

---

## Dataset
The dataset contains multiple CSV files related to E-commerce operations.
🔗 Dataset Link: [Click Here](https://drive.google.com/drive/folders/13Atlc06Od_Dd76xhJnO5IRZp0kzfQprN)

### Tables Used
- Customers  
- Orders  
- Sellers  
- Products  
- Order Items  
- Payments  
- Geolocation  

---

## Tools & Technologies

### 🔹 Database
- PostgreSQL
- SQL (Joins, Aggregation, Date Functions, Correlation)

### 🔹 Programming
- Python
- Pandas
- NumPy
- Psycopg2

### 🔹 Visualization
- Matplotlib
- Seaborn

---

## Project Workflow

### 1️⃣ Data Import & Database Setup
- Connected Python with PostgreSQL
- Imported CSV files into relational tables
- Maintained relationships between tables

---

### 2️⃣ Data Cleaning & Transformation
- Handled missing values
- Converted data types
- Prepared date columns
- Aggregated data for analysis

---

### 3️⃣ SQL Business Analysis
Performed several business analysis queries such as:

✔ Monthly Order Trend  
✔ Category-wise Order Performance  
✔ Customer Purchase Behavior  
✔ Revenue Analysis  
✔ Product Demand Analysis  
✔ Price vs Purchase Correlation  

---

### 4️⃣ Data Visualization
Used Python visualization libraries to generate:

- Bar Charts
- Trend Analysis Graphs
- Correlation Scatter Plots
- Monthly Performance Charts

---

## Key Business Insights

### 🔹 Order Trend Analysis
Identified seasonal order patterns and monthly distribution of orders.

### 🔹 Category Performance
Analyzed which product categories receive higher customer demand.

### 🔹 Price Impact
Evaluated correlation between product price and purchase frequency.

### 🔹 Customer Behavior
Analyzed repeat purchase trends and customer engagement.

---

## 🔗 Database Connection Example

```python
import psycopg2

conn = psycopg2.connect(
    host="localhost",
    user="your_username",
    password="your_password",
    database="ecommerce_db"
)
```
## Author - Md Rifat sarker

For more information about me, please connect with following link:

- **FaceBook**: [Profile Link](https://www.facebook.com/md.rifat.sarker.268451/)
- **Instagram**: [Profile Link](https://www.instagram.com/md_rifat_sarker/)
- **LinkedIn**: [Profile Link](https://www.linkedin.com/in/mdrifatsarker/)

Thank you for your support, and I look forward to connecting with you!
---
