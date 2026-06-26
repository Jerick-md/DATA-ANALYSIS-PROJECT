# 📊 Company Sales Performance (2013–2014) Dashboard

## 📌 Project Overview
The **Company Sales Performance (2013–2014) Dashboard** is an interactive Power BI project designed to analyze and visualize the company's financial and sales performance during the years 2013 and 2014.

This dashboard provides business insights into:
- Sales and revenue performance
- Profitability and profit margins
- Product performance
- Monthly sales trends
- Geographic sales distribution

The objective of this project is to support data-driven decision-making by transforming raw financial data into meaningful visual insights.

---

## 🎯 Project Objectives
- Monitor key financial metrics (Sales, Revenue, Profit, and Profit Margin).
- Identify top-performing products.
- Analyze monthly sales trends.
- Evaluate sales performance by country.
- Provide a professional executive-level dashboard for business reporting.

---

## 📊 Dashboard KPIs

| KPI | Value |
|------|--------|
| Total Sales | 118.73M |
| Revenue | 127.93M |
| Profit | 16.89M |
| Profit Margin | 13.21% |

---

## 🛠 Tools and Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Microsoft Financial Sample Dataset
- Data Visualization and Business Intelligence Techniques

---

## 📐 DAX Measures

### Revenue

```DAX
Revenue =
SUMX(
    financials,
    financials[Sale Price] * financials[Units Sold]
)
```

### Profit Margin

```DAX
Margin Profit =
DIVIDE(
    SUM(financials[Profit]),
    [Revenue],
    0
)
```

---

## 📊 Key Insights
- Generated **118.73M** in total sales.
- Earned **127.93M** in total revenue.
- Achieved a **13.21% profit margin**.
- **Paseo** is the highest-performing product.
- **October** recorded the highest monthly sales.
- The **United States** contributed the largest share of sales.

---

## 🚀 Future Improvements
- Add Year-over-Year (YoY) analysis.
- Implement forecasting and predictive analytics.
- Add customer segmentation analysis.
- Create drill-through and interactive report pages.
- Integrate real-time data sources.

---

## 👨‍💻 Author

**Jerick T. Comedia**  
Bachelor of Science in Computer Science
Power BI Dashboard Project

---

## 📄 License

This project is for educational and portfolio purposes only.
