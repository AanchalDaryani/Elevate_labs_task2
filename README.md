# Elevate_labs_task2

# Amazon Product Analytics Dashboard

## Project Overview
This Power BI dashboard analyzes Amazon product data to uncover **sales, discounts, customer behavior, and product performance**. The dashboard is designed to be **interactive, visually engaging, and easy to interpret**. It provides a **snapshot of revenue insights, discount impacts, and review analytics** for informed decision-making.

**Objective:**  
- Create a compelling story from the dataset.  
- Highlight key business insights using charts and visuals.  
- Make all visuals interactive with slicers for category and company.

---

## Dataset
The dataset contains the following columns:  
`product_id, product_name, category, discounted_price, actual_price, discount_percentage, rating, rating_count, about_product, user_id, user_name, review_id, review_title, review_content, Main category, sub category, company`

---

## Key Visualizations

### **Cards**
- **Total Revenue (Total_Actual)** – Gross revenue across products.  
- **Total Discounts (Total_Savings)** – Value saved by customers due to discounts.  
- **Net Revenue (Total_Discounted)** – Revenue after discounts.  
- **Total Reviews (Total_Reviews)** – Number of customer reviews.  

---

### **Page 1 Visuals**
- **Clustered Bar Chart:** Top 10 Companies by Avg Rating  
- **Treemap:** Top 20 Companies by Total Revenue  
- **Stacked Column Chart:** Top 15 Companies by Discount %  
- **Category & Company Slicer** (applies across all visuals)  

---

### **Page 2 Visuals**
- **Scatter Plot:** Actual & Discounted Revenue vs Rating Count  
- **Matrix Table:** Category, Actual Price, Avg Discount %, Avg Rating  
- **Column Chart:** Top Products by Review Count  
- **Scatter Plot:** Avg Discount vs Avg Rating by Rating Count  
- **Column Chart:** Sum of Actual Price by Company  
- **Line Chart:** Profit by Main Category  
- **Donut Chart:** Top 15 Sub Categories by Reviews  

---

## **Dashboard Highlights**
- Interactive and **user-friendly design**.  
- Consolidates **key revenue and performance metrics** in 2 pages.  
- Combines **quantitative insights (KPIs, bar charts, scatter plots)** with **qualitative insights (reviews, matrix, treemap)**.  
- Enables **dynamic exploration of products, categories, and companies** for decision-making.  


---

## Usage
- Select a **category or company** using the slicer to filter the dashboard.  
- Hover over charts to view **detailed tooltips**.  
- Explore KPI cards for **quick insights**.  
- Drill down into matrix or treemap for **product-level analysis**.
