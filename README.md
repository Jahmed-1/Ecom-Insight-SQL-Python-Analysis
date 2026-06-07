**Ecom-Insight: E-Commerce Data Analysis with SQL and Python**

**Project Overview**

An end-to-end data analysis project on a large-scale Brazilian e-commerce 
dataset, utilizing MySQL for data extraction and Python for analysis and 
visualization. The goal was to derive actionable business insights across 
sales performance, customer behavior, seller efficiency, and payment trends.

**Author:** Junaid Ahmed  
**MSc Artificial Intelligence**
**Tools:** Python, MySQL, Pandas, Seaborn, Matplotlib, Jupyter Notebook

---

 **Project Structure**

**1. Dataset**
- **Source:** Large-scale Ecommerce platform dataset (Olist/Target)
- **Format:** CSV files ingested into MySQL for structured querying
- **Dataset Link:** https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv

**2. Tools and Technologies**
- **MySQL:** Database management and querying
- **Python (Jupyter Notebook):** Analysis, metrics, and visualizations
- **Libraries:**
  - `pandas` — data manipulation and cleaning
  - `matplotlib` & `seaborn` — visualizations
  - `mysql-connector-python` — MySQL interaction
  - `numpy` — numerical computations

---

**Key Analysis (18 Queries)**

**Basic:**
- Unique customer cities and state-wise distribution
- Orders placed in 2017
- Total sales per product category
- Installment payment percentage

**Intermediate:**
- Monthly order trends in 2018
- Average products per order by city
- Revenue percentage by product category
- Price vs purchase frequency correlation

**Advanced:**
- Moving average of order values per customer
- Cumulative monthly sales per year
- Year-over-year revenue growth rate
- Customer retention rate (6-month window)
- Top 3 highest-spending customers per year
- Top 10 sellers by fastest average delivery time *(Q.16)*
- Payment method popularity by year *(Q.17)*
- Top product categories: 2017 vs 2018 comparison *(Q.18)*

---

**Visual Insights**
- Customer distribution by state
- Monthly order patterns (2018)
- Top seller revenue ranking
- Delivery time performance by seller
- Payment method trends across years
- Category performance: year-over-year comparison

---

**Next Steps**
- Machine learning models for customer lifetime value (CLV) prediction
- Churn prediction using classification models
- Real-time data pipeline integration

---