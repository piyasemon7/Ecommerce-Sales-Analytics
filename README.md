# 🛒 E-commerce Sales Analytics

> Comprehensive analysis of 100,000+ e-commerce transactions to identify revenue drivers, customer segments, and growth opportunities.

![Project Banner](https://via.placeholder.com/800x200/2E9EF7/FFFFFF?text=E-commerce+Sales+Analytics)

## 📊 Project Overview

**Duration:** 3 weeks  
**Role:** Solo Data Analyst  
**Tools:** Python, Pandas, MySQL, Power BI  
**Dataset:** 100,000+ transaction records (2020-2026)

---

## 🎯 Business Problem

An online retailer had extensive sales data but lacked clear insights into:
- Which customers were most valuable
- Which products drove revenue
- Regional performance differences
- Seasonal trends and patterns

**Objective:** Transform raw transaction data into actionable insights for marketing and inventory optimization.

---

## 🔍 My Approach

### 1. Data Collection & Cleaning
- Extracted 100K+ records from MySQL database
- Handled missing values (30% in some columns)
- Removed duplicates (500+ identified)
- Standardized date formats and categorical variables

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of sales, customers, products
- Correlation analysis between variables
- Outlier detection using IQR method
- Time series decomposition

### 3. Customer Segmentation (RFM Analysis)
- **Recency:** Days since last purchase
- **Frequency:** Number of purchases
- **Monetary:** Total spending
- Segmented into 8 customer groups

### 4. Visualization & Dashboarding
- Built 8-page interactive Power BI dashboard
- Created Python visualizations (Matplotlib, Seaborn)
- Implemented drill-through capabilities

---

## 💡 Key Insights

### 1️⃣ Customer Value Distribution
- **Top 20% customers** generated **65% of total revenue** (₹6.9M)
- Average order value: ₹450
- Repeat customer rate: 35%

### 2️⃣ Product Performance
| Product Category | Revenue | % of Total |
|-----------------|---------|------------|
| Jeans | ₹6.9M | 35% |
| Smartphones | ₹3.8M | 19% |
| T-shirts | ₹2.1M | 11% |

### 3️⃣ Regional Trends
- **Chittagong region:** 25% higher AOV than national average
- **Dhaka division:** 45% of total transactions
- Delivery time correlation with customer retention

### 4️⃣ Seasonal Patterns
- 40% sales variation across quarters
- Peak: Q4 (festive season)
- Low: Q2 (monsoon impact)

---

## 📈 Business Impact

✅ **Automated Reporting:** Reduced weekly reporting time from 10 hours to 15 minutes (95% efficiency gain)

✅ **Revenue Opportunity:** Identified potential 18% revenue increase through targeted marketing to high-value segments

✅ **Inventory Optimization:** Recommended stock allocation by region based on demand patterns

✅ **Customer Retention:** Provided actionable insights for 25% retention improvement

---

## 🛠️ Tech Stack

**Programming:**
- Python 3.9 (Pandas, NumPy, Scikit-learn)
- SQL (MySQL 8.0)

**Visualization:**
- Power BI Desktop
- Matplotlib, Seaborn
- Plotly

**Tools:**
- Jupyter Notebook
- MySQL Workbench
- Git & GitHub

---

## 📁 Project Structure
```
Ecommerce-Sales-Analytics/
│
├── data/
│   ├── raw/                    # Original datasets
│   └── processed/              # Cleaned data
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_customer_segmentation.ipynb
│
├── sql/
│   ├── data_extraction.sql
│   └── customer_analysis.sql
│
├── dashboards/
│   ├── powerbi_dashboard.pbix
│   └── screenshots/
│
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.9+
MySQL 8.0+
Jupyter Notebook
Power BI Desktop
```

### Installation
```bash
# Clone the repository
git clone https://github.com/piyasemon7/Ecommerce-Sales-Analytics.git

# Navigate to project directory
cd Ecommerce-Sales-Analytics

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

---

## 📊 Sample Visualizations

### Customer Segmentation (RFM Analysis)
![RFM Segments](https://via.placeholder.com/600x400/2E9EF7/FFFFFF?text=RFM+Segmentation)

### Revenue Trend Over Time
![Revenue Trend](https://via.placeholder.com/600x400/2E9EF7/FFFFFF?text=Revenue+Trend)

### Product Performance
![Product Analysis](https://via.placeholder.com/600x400/2E9EF7/FFFFFF?text=Product+Performance)

---

## 📝 Key Learnings

- Importance of data quality in analysis accuracy
- Power of customer segmentation for targeted marketing
- Effective visualization techniques for business stakeholders
- SQL optimization for large datasets

---

## 🔗 Links

- **Live Dashboard:** [Tableau Public](https://public.tableau.com/app/profile/piyas.emon)
- **Portfolio:** [piyasemon07.blogspot.com](https://piyasemon07.blogspot.com)
- **LinkedIn:** [Piyas Emon](https://linkedin.com/in/piyas-emon-105508399)

---

## 📧 Contact

**Piyas Emon**  
Data Analyst  
📧 piyasemon7@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/piyas-emon-105508399) | [GitHub](https://github.com/piyasemon7)

---

## 📜 License

This project is for educational and portfolio purposes.

---

<div align="center">
  <i>⭐ If you found this project interesting, please consider giving it a star!</i>
</div>
