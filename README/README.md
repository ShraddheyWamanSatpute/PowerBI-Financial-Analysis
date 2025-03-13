# USA Financial Data Analysis

## 📌 Overview
This project provides insightful analysis of customer financial data across the USA to support informed decision-making, targeted marketing campaigns, and strategic planning. Our analysis dives deep into income trends, credit usage, loan preferences, and demographic insights.

## 🎯 Project Goals
- Automate daily data collection and merging (via Power Automate and Google Drive API).
- Efficiently clean and prepare data for detailed analysis using Python, Power Query, and Power BI.
- Analyze financial behaviors, such as payment delays and credit utilization.
- Examine how age influences credit limit adjustments.
- Segment customers based on credit scores and Loan-to-Value (LTV) ratios.
- Deliver actionable insights for targeted promotions and strategic marketing.

## 📊 Key Metrics
- Average Annual Income
- Average Monthly Account Balance
- Average Days in Payment Delay
- Average Credit Utilization
- Age vs. Credit Limit Adjustments
- Age-based LTV Scores
- Popular Loan Types Distribution

## 📁 Data Source
- Automated daily retrieval of financial data files via email, streamlined using Power Automate, and securely stored on Google Drive using GCP APIs.

## 🛠️ Tech Stack
- **Google Drive & Google Cloud Platform (GCP) API**
- **Microsoft Power Automate**
- **Python (Pandas)**
- **Power BI & Power Query**
- **DAX & Measures**

## 🔗 Power BI Dashboard

You can access the interactive Power BI dashboard using the link below:

[View Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=5fcee971-5ee4-47e0-a5a2-a327ca34e7e8&autoAuth=true&ctid=2efd699a-1922-4e69-b601-108008d28a2e)
 
- Ensure you have the necessary access permissions to view the report.

## 🔄 Project Workflow

```plaintext
Email Attachments (25 files daily)
                 │
                 ▼
┌──────────────────────────────────────────────┐
│ 📥 Automated Extraction (Power Automate ⚙️)   │
└──────────────────────────────────────────────┘
                 │
                 ▼
┌──────────────────────────────────────────────────┐
│ 📂 Upload to Google Drive via GCP Drive API ☁️    │
└──────────────────────────────────────────────────┘
                 │
                 ▼
┌───────────────────────────────────────────────────────────┐
│ 🐍 Data Merging & Cleaning (Python_Script, BI Power Query) │
└───────────────────────────────────────────────────────────┘
                 │
                 ▼
┌──────────────────────────────────────────────┐
│ 📊 Data Visualization & Analysis (Power BI)   │
└──────────────────────────────────────────────┘
                 │
                 ▼
┌────────────────────────────────────────────────┐
│ 📑 Dashboard & Insights (Strategic Decisions)   │
└────────────────────────────────────────────────┘
                 │
                 ▼
         ✅ Final Report Delivery
```



### 📥 Data Collection
- Automatic daily extraction (~25 files) via 📧 **Power Automate**.
- Instant upload to 📂 **Google Drive** through integrated **GCP Drive API**.

### 🧹 Data Cleaning & Preparation
- Python automation scripts merge and prepare data.
- Transformations including custom columns, conditional columns, and removal of empty/unwanted columns.
- Cleaning includes data formatting, managing missing values, and standardizing data fields.

### 📈 Analysis & Visualization
- Development of interactive dashboards in 📊 **Power BI** highlighting critical insights.
- **DAX & Measures** used for deeper analysis.
- Created a dedicated **Measures Table** for calculations.
- Three key measures:
  1. **AvgCreditEnquiries** 📊
  2. **LTV Score** 💳
  3. **Potential Customers** 🎯
- Visualization of loan distribution and customer demographics.

## 🎨 Dashboard Highlights
- **💰 Income & Credit Metrics**: Visualization of average income, monthly balances, delayed payments, and credit utilization.
- **📉 Age vs. Credit Limit**: Scatter plots showing age-related credit limit variations.
- **📊 Age Demographics**: Bar charts detailing customer distribution across age groups and credit scores.
- **🏦 Loan Analysis**: Visualization of loan popularity among customers.

## 💡 Insights & Recommendations
- Target potential customers based on age and financial behavior for customized promotions.
- Leverage LTV and credit analytics for strategic marketing and retention.
- Optimize resources based on identified loan trends and demographics.

## 📂 Project Resources
- `Dataset`: Raw datasets
- `python_script_for_BI.txt`: Python automation script
- `Power BI Finance Project.pbix`: Dashboard report
- `DAX Measures & Power Query`: Used for calculations, analysis and transformations

## ✨ Tech Summary
| Tech              | Usage                           |
|-------------------|---------------------------------|
| Power BI       | Data visualization & reporting  |
| DAX & Measures | Data calculations & analysis    |
| Power Query    | Data transformation & cleaning |
| Python         | Data merging & automation      |
| Google Drive   | Data storage & retrieval        |
| Power Automate | Workflow automation             |
| GCP(Drive API) | Establish connection between Drive and Power BI|

