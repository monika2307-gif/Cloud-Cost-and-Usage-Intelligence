# ☁️ Cloud Cost & Usage Intelligence – Power BI Project

## 📌 Project Overview

Cloud Cost & Usage Intelligence is an interactive Power BI project designed to analyze cloud spending, monitor budget utilization, identify cost-saving opportunities, evaluate account performance, and detect unusual spending patterns.

The project transforms cloud cost data into meaningful business insights through interactive dashboards, data modelling, Power Query, and DAX measures.

## 🎯 Project Objectives

- Monitor overall cloud spending and usage trends.
- Track actual spending against allocated budgets.
- Analyze cost savings and optimization opportunities.
- Evaluate cloud spending across different accounts and services.
- Identify unusual spending patterns and cost anomalies.
- Support data-driven cloud cost management decisions.

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft Excel
- Data Visualization

## 📊 Dashboard Overview

The project consists of five interactive dashboards:

### 1. Cloud Spending Overview
- Analyze total cloud expenditure.
- Track monthly spending trends.
- Compare costs across cloud providers and services.
- Monitor spending by department, region, and environment.

### 2. Budget Utilization Analysis
- Compare actual cloud spending with allocated budgets.
- Monitor budget utilization percentages.
- Identify accounts exceeding their allocated budgets.
- Track monthly budget performance.

### 3. Cost Savings Analysis
- Analyze potential cost-saving opportunities.
- Identify areas with high cloud expenditure.
- Monitor savings trends.
- Highlight opportunities for cloud cost optimization.

### 4. Account Performance Analysis
- Compare spending across different cloud accounts.
- Analyze account-level cost distribution.
- Identify high-spending accounts.
- Enable account-level drill-through analysis.

### 5. Cost Anomaly Detection
- Identify unusual cloud spending patterns.
- Analyze anomaly scores.
- Monitor unexpected cost variations.
- Highlight accounts and services requiring attention.

## 🗂️ Data Model

The project follows a Star Schema approach to organize data and improve reporting performance.

**Dimension Tables:**
- DimAccount
- DimRegion
- DimDate
- DimService

**Fact Tables:**
- FactCloudCost
- FactMonthlyBudget

The data model connects dimension tables with fact tables to enable efficient filtering, aggregation, and interactive analysis.

## ⚙️ Data Preparation & Transformation

Power Query was used for:
-Data cleaning and preprocessing.

Handling missing and inconsistent values.

Data type correction.

Date formatting and transformation.

Preparing structured datasets for analysis.

📐 DAX & Measures

DAX was used to create calculated measures for:

Total Cloud Cost

Total Budget

Budget Utilization %

Cost Savings

Monthly Cost Trends

Account-wise Spending

Anomaly Count

📈 Key Business Insights

The dashboards help users:

Understand overall cloud expenditure.

Monitor budget performance.

Identify high-cost accounts and services.

Recognize unusual spending patterns.

Explore potential cost optimization opportunities.

Make informed cloud spending decisions.

🚀 Future Enhancements

Integrate real-time cloud billing data.

Implement advanced anomaly detection using Machine Learning.

Add predictive cloud cost forecasting.

Develop automated cost optimization recommendations.

👩‍💻 Author

Monika Neel

Data Science & Analytics | Power BI | Python | SQL
