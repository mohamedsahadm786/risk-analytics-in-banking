# Banking Risk Analytics Project

## Repository Overview

This repository presents a comprehensive project for **risk analytics in banking and financial services** using data analysis and visualization. The workflow spans Python-based EDA, advanced Power BI dashboarding, and supporting documentation.

---

## Business Problem & Objective

Banks need to minimize the risk when lending to clients, using data-driven insights to reduce defaults and enhance profitability.

- **Key Objective:**  
  Deploy analytics to evaluate applicant profiles, guiding lending decisions.
- **Expected Impact:**  
  - Reduce loss from defaults.
  - Enable smarter approvals/rejections.
  - Identify high-value and high-risk segments.

---

## Project Structure

Here’s an overview of the files included:

- **Dashboard.pbix**: Power BI presentation containing multi-tab dashboards, KPI views, and drill-through explorations.
- **EDA.ipynb**: Jupyter notebook documenting all Python-based data cleaning, feature engineering, and exploratory analysis.
- **README.md**: This file—project guide covering goals, structure, and methodology.
- **Report.pdf**: Detailed business problem statement, summary of workflow, and key findings/results based on the analysis.
- **banking-clients.csv**: Tabular data for individual bank clients.
- **banking-relatlonships.csv**: Banking relationship mapping and attributes.
- **gender.csv**: Gender lookup table for clients.
- **investment-advisors.csv**: Mapping clients to investment advisors.

---

## Data Sources & Preparation

- **Sources:**  
  Multiple CSV tables containing information about clients, banking relationships, gender, and investment advisors.
- **Preparation Steps:**  
  - Cleaned all tables and handled missing values.
  - Merged tables via primary/foreign keys for analytical depth.
  - Engineered new features:
    - **Engagement Timeframe**: Shows how long a client has been with the bank.
    - **Processing Fees**: Derived from the Fee Structure column.
    - **Income Bands**: Client income categorized (Low/Mid/High).
    - **Engagement Days**: Exact client tenure in days.

---

## Exploratory Data Analysis (EDA)

Python-based exploration (see `EDA.ipynb`):

- Provided descriptive stats for all features.
- Analyzed distribution of client demographics, banking products, and financial KPIs.
- Explored correlations between deposits, savings, loans, and credit card usage.
- Generated feature bands and segmentation overview.

---

## Power BI Dashboard

- Interactive dashboard (see `Dashboard.pbix`) with:
  - Multiple tabs: KPI Overview, Loan Analysis, Deposit Analysis, Client Profiles, Risk Analysis.
  - Drill-through functionality for segment deep-dives.
  - Filters by demographic and product attributes.
  - Visual cues for high-risk and priority segments.

---

## Report & Key Results

- **Report.pdf** summarizes:
  - Business problem, methodology, and analytical approach.
  - Major findings from EDA and dashboard.
  - Sample recommendations and business impact.

---

## How to Use This Repository

1. Clone/download the repository and place all files in a working directory.
2. Use `EDA.ipynb` (Jupyter) to review Python EDA pipeline and summary stats.
3. Open `Dashboard.pbix` in Power BI Desktop to interact with the analytical dashboards.
4. Review `Report.pdf` for the formal writeup and business discussion.

**Requirements:**
- Python 3.x (with pandas, numpy, matplotlib, seaborn)
- Power BI Desktop

---

## Future Enhancements

- Extend analytics with predictive ML models for risk scoring.
- Integrate real-time dashboards using cloud data pipelines.
- Add client churn and cross-sell models for expanded business intelligence.

---

## Conclusion

This project demonstrates analytics best practices and business value for banking risk mitigation, using real-world feature engineering, Python data science, and Power BI dashboarding.
