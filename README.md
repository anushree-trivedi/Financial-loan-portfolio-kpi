# Financial Loan Portfolio- Risk & KPI Analysis
### SQL + Python + Power BI | 9,578 Loans Analysed

## 📌 Business Problem
Banks and credit unions need real-time visibility into portfolio health through 
default rates, interest rate trends, and risk distribution across borrower 
segments. This project builds a complete KPI reporting system from raw loan 
data to an executive dashboard.

## 🛠️ Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- SQL (SQLite CTEs, aggregations, GROUP BY)
- Power BI (Dashboard, DAX)

## 🔍 Key Findings

| Metric | Value |
|---|---|
| Total Loans Analysed | 9,578 |
| Overall Default Rate | 16.01% |
| Average FICO Score | 711 |
| Average Interest Rate | 12.26% |
| Highest Risk Segment | Small Business (27.79% default) |
| Safest Segment | Major Purchase (11.21% default) |

## 📈 SQL Queries Built
- Default rate by loan purpose
- Portfolio health by FICO credit band
- Overall KPI summary aggregation

## 💡 Key Business Insights
- Small business loans carry nearly 3x the default risk of major purchase loans
- High Risk borrowers (FICO below 650) default at 32% vs 7.4% for Excellent borrowers
- Debt consolidation is the largest loan category with 3,957 loans: biggest absolute risk
- Interest rates correctly reflect risk: High Risk borrowers pay 15.3% vs 9.4% for Excellent

## 📁 Files
- `financial_kpi.ipynb`: Full Python + SQL analysis
- `loans_clean.csv`: Cleaned loan dataset
- `default_by_purpose.csv`: Default rates by loan purpose
- `portfolio_health.csv`: FICO band risk analysis
- `kpi_summary.csv`: Overall portfolio KPIs
- `dashboard_screenshot.png`: Power BI dashboard
