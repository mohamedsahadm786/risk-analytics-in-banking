# 🏦 Banking Risk Analytics – End-to-End Data Analytics & Power BI Project

---

## 📌 Project Overview

This project focuses on **banking risk analytics** using **Python-based exploratory data analysis (EDA)** and **Power BI dashboards** to understand how financial institutions can reduce lending risk through data-driven insights.

The analysis helps evaluate **client profiles, loan exposure, deposits, engagement duration, and demographic segmentation**, enabling better-informed lending and business decisions.

This repository is structured to reflect a **practical analytics workflow**, similar to how analytics projects are documented and shared by **professional data analysts and BI teams**.

---

## 🎯 Business Problem Statement

Banks face financial risk when lending without sufficient analytical understanding of:

- Client engagement duration with the bank  
- Income-based loan exposure  
- Distribution of loans across demographic segments  
- Deposit behavior and account balances  
- Concentration risk across banking relationships and nationalities  

Without analytics-backed insights, lending decisions may lead to **higher default risk and revenue loss**.

---

## 🎯 Project Objectives

- Perform **Exploratory Data Analysis (EDA)** on banking datasets  
- Clean and prepare data for analysis  
- Create **business-relevant features** for risk assessment  
- Build **interactive Power BI dashboards** for analysis and reporting  
- Enable filtering and segmentation for better decision-making  
- Present insights in a **clear, business-oriented format**

---

## 🛠️ Tools & Technologies Used

### **Programming & Analysis**
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

### **Visualization & Reporting**
- Power BI Desktop  

### **Documentation & Version Control**
- Git  
- GitHub  
- Markdown  

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & Cleaning (Python)

- Imported multiple banking-related datasets  
- Handled missing values and data inconsistencies  
- Merged datasets using common keys  
- Created new analytical features such as:
  - **Engagement Timeframe**
  - **Engagement Days**
  - **Income Band (Low / Mid / High)**
  - **Processing Fees (derived from fee structure)**

---

### 2️⃣ Exploratory Data Analysis (EDA)

- Generated descriptive statistics  
- Analyzed distributions of:
  - Loans  
  - Deposits  
  - Credit card balances  
- Segmented analysis by:
  - Income band  
  - Gender  
  - Banking relationship  
  - Nationality  
- Identified early patterns related to **risk and engagement**

---

### 3️⃣ Power BI Dashboard Development

- Imported cleaned datasets into Power BI  
- Created calculated measures for:
  - Total Loan  
  - Bank Loan  
  - Business Lending  
  - Credit Card Balance  
  - Total Deposits  
  - Total Fees  
- Designed **interactive dashboards** using slicers and filters  
- Focused on clarity, usability, and business interpretation  

---

## 📊 Power BI Dashboard Pages

Below are the main Power BI dashboard pages included in this project.  

---

### 🏠 Home – Executive Overview

**Purpose:**  
Provides a high-level summary of key banking metrics.

**Highlights:**
- Total Loans  
- Total Deposits  
- Total Fees  
- Overall client engagement indicators  

📷 **Dashboard Preview:**  
![Home Dashboard](https://github.com/mohamedsahadm786/risk-analytics-in-banking/blob/main/power%20BI/1.png)

---

### 💳 Loan Analysis

**Purpose:**  
Analyze loan exposure and lending distribution.

**Highlights:**
- Bank Loan vs Business Lending vs Credit Cards  
- Loan distribution by:
  - Income Band  
  - Banking Relationship  
  - Nationality  

📷 **Dashboard Preview:**  
![Loan Analysis](https://github.com/mohamedsahadm786/risk-analytics-in-banking/blob/main/power%20BI/2.png)

---

### 💰 Deposit Analysis

**Purpose:**  
Understand how clients hold and distribute their assets.

**Highlights:**
- Bank Deposits  
- Savings Accounts  
- Checking Accounts  
- Foreign Currency Accounts  

📷 **Dashboard Preview:**  
![Deposit Analysis](https://github.com/mohamedsahadm786/risk-analytics-in-banking/blob/main/power%20BI/3.png)

---

### 📈 Summary Dashboard

**Purpose:**  
Consolidated analytical view for quick decision-making.

**Highlights:**
- Combined view of loans, deposits, and engagement  
- High-level segmentation comparison  

📷 **Dashboard Preview:**  
![Summary Dashboard](https://github.com/mohamedsahadm786/risk-analytics-in-banking/blob/main/power%20BI/4.png)

---

### 🔍 Drill-Through / Detailed View

**Purpose:**  
Enable deeper analysis of specific segments.

**Highlights:**
- Segment-level insights  
- Filter-based deep dives  
- Support for exploratory decision analysis  

📷 **Dashboard Preview:**  
![Drill Through](https://github.com/mohamedsahadm786/risk-analytics-in-banking/blob/main/power%20BI/Screenshot%202026-01-29%20195351.png)

---

## 📈 Key Insights Observed

- Private banking relationships show higher loan concentration  
- Mid-income clients contribute significantly to total loan value  
- Longer engagement duration often aligns with higher deposits  
- Certain demographic segments show higher credit exposure  

---

## 📌 Business Use Cases

- Identify high-risk lending segments  
- Support loan approval and rejection decisions  
- Understand deposit behavior across clients  
- Assist banks in segment-based strategy formulation  

---

## ▶️ How to Use This Repository

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/banking-risk-analytics.git
cd banking-risk-analytics
```

### Step 2: Python EDA
- Open `EDA using python/EDA.ipynb`
- Review data cleaning, feature creation, and EDA

### Step 3: Power BI Dashboard
- Open `power BI/Dashboard.pbix` using Power BI Desktop  
- Refresh data if required  
- Use filters and slicers to explore insights  

---

## 📂 Project Folder Structure

```text
banking-risk-analytics/
│
├── Data sets/
│   ├── Real_data.xlsx
│   ├── banking-clients.csv
│   ├── banking-relationships.csv
│   ├── gender.csv
│   └── investment-advisors.csv
│
├── EDA using python/
│   ├── EDA.ipynb
│   └── EDA_1.ipynb
│
├── power BI/
│   └── Dashboard.pbix
│
├── screenshots/
│   ├── home.png
│   ├── loan_analysis.png
│   ├── deposit_analysis.png
│   ├── summary.png
│   └── drill_through.png
│
├── Banking Report.docx
├── Report.pdf
├── index.html
└── README.md
```

---

## 🏁 Conclusion

This project demonstrates a **practical banking risk analytics workflow**, combining:

- Python-based exploratory analysis  
- Business-oriented feature engineering  
- Interactive Power BI dashboards  

It reflects how **data analytics is applied in banking environments** to support risk assessment and decision-making.

---

## 👤 Author

**Mohamed Sahad M**  
Master’s in Statistics  
Data Analytics | Power BI | Python  

