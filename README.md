# 📊 Financial Risk Dashboard | Power BI

An interactive **Financial Risk Dashboard** developed using **Power BI** to analyze customer demographics, loan portfolio performance, and financial risk. The dashboard provides valuable insights into loan distribution, customer creditworthiness, default trends, and high-risk customers through interactive visualizations and KPIs.

---

## 📌 Project Overview

This project focuses on analyzing financial and loan data to help financial institutions monitor customer profiles, evaluate loan performance, and identify potential financial risks.

The dashboard is divided into three interactive report pages:

- Customer Demographics
- Loan Portfolio & Performance
- Financial Risk Analysis

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft Excel

---

## 📂 Dataset

The project uses two Excel sheets:

### Customer Details
- Customer ID
- Name
- Age
- Gender
- Income
- Employment Status
- Education Level
- Credit Score

### Loan Details
- Loan ID
- Customer ID
- Loan Type
- Loan Amount
- Interest Rate
- Loan Term
- Issue Date
- Monthly Installment
- Loan Status

---

## 🔄 Data Preparation

The following preprocessing steps were performed:

- Imported Excel data into Power BI
- Renamed tables
- Removed duplicate records
- Removed missing values
- Corrected data types
- Created Date table using `CALENDARAUTO()`
- Built relationships between tables
- Merged customer and loan information
- Created calculated columns for categorization
- Built DAX measures for KPI reporting

---

## 📊 Data Categorization

### Age Groups
- Young (≤ 25)
- Middle-aged (26–45)
- Senior (46–58)
- Elder (≥ 59)

### Credit Score Buckets
- Poor
- Fair
- Good
- Very Good
- Excellent

### Income Groups
- Low
- Medium
- High

### Risk Categories
- High Risk
- Moderate Risk
- Low Risk
- Very Low Risk

---

## 📈 Dashboard Pages

### 1️⃣ Customer Demographics

#### KPIs
- Total Customers
- Average Age
- Average Income

#### Visualizations
- Gender Distribution
- Education Level Distribution
- Average Credit Score by Gender & Education Level

#### Filters
- Income Group
- Credit Score Bucket

---

### 2️⃣ Loan Portfolio & Performance

#### KPIs
- Total Loan Amount
- Average Monthly Installment

#### Visualizations
- Loan Type Distribution
- Loan Status by Loan Type
- Top 10 Active Loans
- Top 10 Defaulted Loans
- Interest Rate Gauge

#### Filters
- Income Group
- Credit Score Bucket

---

### 3️⃣ Financial Risk Analysis

#### KPIs
- Defaulted Loans
- Defaulted Loan Amount
- High Risk Loans
- High Risk Loan Amount

#### Visualizations
- Defaulted Loan Amount by Employment Status
- High Risk Loan Amount by Employment Status
- Income vs Education Risk Matrix
- Credit Score Bucket vs Employment Status

#### Filters
- Income Group
- Credit Score Bucket

---

## 📊 DAX Measures

The project includes several DAX measures, including:

- Total Loan Amount
- Average Interest Rate
- Average Monthly Installment
- Loan Status Count
- Total Customers
- Average Age
- Average Income
- Defaulted Loans
- Defaulted Loan Amount
- High Risk Loans
- High Risk Loan Amount

---

## 📌 Key Insights

- Identified high-risk customers based on credit scores.
- Analyzed defaulted loan trends.
- Compared loan performance across different loan types.
- Evaluated customer demographics and income distribution.
- Monitored financial KPIs for better decision-making.

---

## 🚀 Skills Demonstrated

- Power BI Dashboard Development
- Power Query (ETL)
- Data Cleaning
- Data Modeling
- DAX
- KPI Design
- Interactive Reports
- Financial Analytics
- Business Intelligence
- Data Visualization

---

## 👨‍💻 Author

**Souradeep Singha**

If you found this project helpful, feel free to ⭐ this repository.
