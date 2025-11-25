# Pizza Sales Analysis - Data Analysis Project 

This project is a complete exploratory analysis of one year of pizza sales data.  
It demonstrates how raw transactional data can be transformed into business insights using Python.

Unlike a typical dashboard project, this analysis goes deeper into:
- identifying sales patterns,
- uncovering product performance,
- studying operational rhythms,
- and translating insights into strategic opportunities.
---

## 1. Project Objectives

This project answers three core questions:

### **Business**
- What drives revenue and demand?
- Which products contribute the most/least to performance?
- How should operations and inventory be optimized?

### **Analytics**
- What patterns appear across time (hour, day, month)?
- How do customer preferences vary by size, category, and ingredients?
- Which products dominate or fail across revenue, orders, and quantity?

### **Technical**
- How to transform raw CSV data into structured insights?
- How to design visualizations that tell a story?
- How to generate recommendations backed by data?

---

## 2. Tools & Technologies

**Python:** pandas, numpy, matplotlib, seaborn, plotly  
**Jupyter Notebook** for analysis  
**GitHub** for version control and project documentation  
**Markdown** for project storytelling  

---

## 3. Dataset Overview

The dataset includes **48,620 records** of pizza orders with fields like:
- order date and time  
- pizza name, size, category  
- ingredients  
- unit and total prices  
- quantity  

This enables analysis at the:
- product level,  
- time level (hour/day/month),  
- category and size level,  
- ingredient level.

---

## 4. Approach & Methodology

### **1. Data Cleaning**
- Converted date/time fields into datetime format  
- Standardized categorical ordering (days, months)  
- Extracted hours and additional analytical features  
- Exploded ingredient lists for frequency analysis  

### **2. KPI Development**
Calculated primary metrics:
- Total Revenue  
- Total Pizzas Sold  
- Total Orders  
- Average Order Value  
- Average Items per Order  

### **3. Exploratory Data Analysis**
Performed visual and statistical analysis across:
- daily, monthly, hourly patterns  
- category-level revenue performance  
- size-level sales contribution  
- ingredient usage frequency  
- top/bottom sellers  
- revenue vs. quantity behavior  

### **4. Visualization**
Used bar charts, line plots, pie charts, and heatmaps to create:
- demand trend charts  
- category and size breakdowns  
- top/bottom performers  
- ingredient usage mapping  

---

## 5. Key Deliverables in this Repository

- **pizza_sales_analysis.ipynb**  
  Full analysis with code, charts, insights, and explanations

- **README.md**  
  Project overview, methodology, and usage guide

---

## 6. How to Use This Project

### **To run the analysis locally:**
1. Clone the repo:
   ```bash
   git clone https://github.com/sakshidnaik/Pizza-Sales-Analysis.git
