# 🛍️ Customer Shopping Behavior Analysis

## 📌 Overview

Customer Shopping Behavior Analysis is an end-to-end Data Analytics project that explores customer purchasing patterns using transactional retail data. The project combines Python, SQL Server, and Power BI to clean, analyze, and visualize customer behavior, helping businesses make data-driven decisions.

The analysis focuses on identifying customer segments, purchasing trends, product performance, subscription behavior, and revenue insights through interactive dashboards and SQL-based business analysis.

---

## 📊 Dataset

- **Total Records:** 3,900
- **Total Columns:** 18

### Key Features

- Customer Demographics
  - Age
  - Gender
  - Location
  - Subscription Status

- Purchase Information
  - Item Purchased
  - Category
  - Purchase Amount
  - Season
  - Size
  - Color

- Shopping Behavior
  - Review Rating
  - Shipping Type
  - Discount Applied
  - Previous Purchases
  - Purchase Frequency

### Data Quality

- Missing values in **Review Rating**
- Standardized column names using **snake_case**
- Feature engineering performed for customer segmentation

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- SQL Server
- SQL
- Power BI
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Cleaning (Python)

- Loaded dataset using Pandas
- Explored data using `.info()` and `.describe()`
- Handled missing values using median imputation
- Converted column names to snake_case
- Removed redundant columns
- Created new features:
  - `age_group`
  - `purchase_frequency_days`

---

### 2. SQL Analysis

Performed business-focused SQL analysis including:

- Revenue by Gender
- High-Spending Discount Users
- Top 5 Products by Average Rating
- Shipping Type Comparison
- Subscribers vs Non-Subscribers Analysis
- Products with Highest Discount Usage
- Customer Segmentation
- Top 3 Products within Each Category
- Repeat Buyer Subscription Analysis
- Revenue Contribution by Age Group

---

### 3. Dashboard Development (Power BI)

Created an interactive Power BI dashboard featuring:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Distribution

### Dashboard Filters

- Gender
- Category
- Subscription Status
- Shipping Type

---

## 📈 Key Insights

- Male customers generated higher revenue than female customers.
- Clothing category contributed the highest sales.
- Express shipping customers had a slightly higher average purchase amount.
- Some products consistently received higher customer ratings.
- Loyal customers represented the largest customer segment.
- Young Adult customers contributed the highest revenue.
- Subscription status influenced customer purchasing behavior.

---

## 💡 Business Recommendations

- Promote subscription plans with exclusive offers.
- Reward loyal customers through loyalty programs.
- Highlight top-rated and best-selling products in marketing campaigns.
- Optimize discount strategies to maintain profitability.
- Target high-value customer segments with personalized promotions.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

### 2. Install Dependencies

```bash
pip install pandas numpy sqlalchemy pyodbc matplotlib
```

### 3. Open the Jupyter Notebook

Run the data preprocessing notebook to clean and prepare the dataset.

### 4. SQL Analysis

Import the cleaned dataset into SQL Server and execute the SQL queries to perform business analysis.

### 5. Open Power BI

- Open the `.pbix` file.
- Connect to the SQL Server database.
- Refresh the data.
- Explore the interactive dashboard.

---

## 📂 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_data.csv
│
├── Python/
│   └── data_cleaning.ipynb
│
├── SQL/
│   └── business_queries.sql
│
├── PowerBI/
│   └── Customer_Behavior_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

## 📷 Dashboard Preview

> Add a screenshot of your Power BI dashboard here.

---

## 📌 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Aggregations
- Window Functions
- Business Analysis
- Data Visualization
- Dashboard Design
- Power BI
- SQL Server
- Python (Pandas)

---

## 👤 Author

**Shree Rangam**

MCA Graduate | Aspiring Data Analyst

- LinkedIn: www.linkedin.com/in/rangam05

