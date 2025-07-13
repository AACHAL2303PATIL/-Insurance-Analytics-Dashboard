# 📊 Power BI Project: Insurance Data Analysis with MSSQL & Sentiment Insights

## 📝 Short Description:
This project demonstrates an end-to-end Power BI dashboard for analyzing insurance data, sourced from MSSQL Server and enhanced with sentiment analysis through Power Query. It includes key KPIs, role-level security (RLS), scheduled refresh, and modern visualizations to derive business insights.

## 🎯 Purpose:
To provide a dynamic and secure reporting solution for insurance metrics that helps stakeholders monitor performance, customer sentiment, and operational KPIs effectively using Power BI.

## 🧰 Tech Stack / Tools Used:
- Power BI Desktop & Service
- Microsoft SQL Server
- Power Query
- DAX
- Power BI Service (for publishing and scheduled refresh)
- Role-Level Security (RLS)

## 🔢 Data Source:
- **Source:** MSSQL Server (imported manually)
- **Type:** Insurance customer and sentiment data
- **Fields Included:** Customer ID, Policy Type, Premium, Claim Status, Age, Gender, Region, Sentiment Score, Feedback

## 🧠 Key Features:
- Connected Microsoft SQL Server to Power BI for raw data import
- Transformed raw data using Power Query (data cleaning, profiling)
- Developed impactful visuals including:
  - Multi-row cards
  - Matrix tables
  - Donut, bar, line, and ribbon charts
- Implemented Drill-Through filters for deeper data exploration
- Conducted sentiment analysis using Power Query
- Visualized sentiment trends with custom visuals
- Applied Role-Level Security (RLS) to restrict user access based on roles
- Published the report to Power BI Service with scheduled refresh
- Ensured dashboard interactivity with slicers and filters (Region, Policy, Claim Type)


## 📊 Example Visualizations:
- Multi-row card with Premium, Policy, Claims KPIs
- Bar and Line chart for premium trends over time
- Donut chart showing claim status distribution
- Ribbon chart for premium by policy type
- Sentiment analysis visual with customer feedback

## ❓ Business Questions Answered:
- What is the total and average insurance premium collected?
- What’s the trend of claims by policy type?
- Which region or demographic has the highest claim rate?
- What is the sentiment trend from customer feedback?
- Are specific agents or branches underperforming?

## 💡 Business Impact & Insights:
- Enabled the business to assess performance KPIs at a glance
- Delivered insights into customer sentiment for strategic improvements
- Empowered secure access using Role-Level Security (RLS)
- Automated refresh ensured always-updated insights
- Created interactive drill-down and drill-through features to support decision-making

## 🖼️ Screenshots:

- **Dashboard Overview**  
  ![Insurance Data Analysis Dashboard 1](https://github.com/AACHAL2303PATIL/House-Market-Analysis-using-Google-BigQuery/blob/main/House%20Dashboard%201.png)
  ![Insurance Data Analysis Dashboard 2](https://github.com/AACHAL2303PATIL/House-Market-Analysis-using-Google-BigQuery/blob/main/House%20Dashboard%202.png)
  ![Insurance Data Analysis Dashboard 3](https://github.com/AACHAL2303PATIL/House-Market-Analysis-using-Google-BigQuery/blob/main/House%20Dashboard%203.png)

## 🚀 How to Use:
1. Clone or download the `.pbix` file from this repo
2. Connect it to your MSSQL database (replace with your server credentials)
3. Review and edit DAX or Power Query if using a different schema
4. Publish to Power BI Service for scheduled refresh and RLS testing

## 📂 Dataset:
🔗 [Click here to access the dataset](https://drive.google.com/file/d/1PpuWPloKOtTau5yG7QkXP2fuoDpQdXK4/view)


