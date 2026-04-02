# 🛒 Olist E-Commerce Analysis

End-to-end exploratory data analysis of 100K+ real Brazilian e-commerce orders,
covering customer segmentation, sales trends, and geospatial profitability insights.

---

## 📁 Project Structure

```
olist-ecommerce-analysis/
├── notebooks/
│   ├── 01_eda.ipynb                       # Data cleaning & merging
│   ├── 02_sql_analysis.ipynb              # SQL queries with pandasql
│   └── 03_rfm_segmentation.ipynb          # RFM scoring & segmentation
├── Olist_BrazilianEcommerce_Report.pdf/   # Detailed Report with Visuals
└── README.md
```

---

## 🛠️ Technologies

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| pandasql | SQL queries on DataFrames |
| Seaborn / Matplotlib | Static visualizations |
| Plotly | Interactive geospatial map |
| Jupyter Notebook | Development environment |

---

## 🔍 Key Insights

**1. Southeast dominance:**
Order volume and profitability are heavily concentrated in São Paulo and Rio de Janeiro.
Northern and inland regions show low market penetration — a potential opportunity
for targeted logistics and marketing strategies.

**2. Customer retention risk:**
RFM analysis reveals that the majority of customers haven't placed an order in 300+ days.
The high-value active segment (Champions & Loyal) is small but drives disproportionate revenue —
making retention campaigns a high-ROI priority.

**3. Delivery time impacts satisfaction:**
Median delivery time is 10 days, with a right-skewed distribution indicating
a significant tail of late deliveries. Late deliveries correlate with lower review scores,
suggesting logistics optimization could directly improve customer satisfaction.

---

## 📊 Analyses Performed

- Data cleaning & multi-table merging (8 datasets)
- Category-level profitability analysis
- Monthly sales trend (2016–2018)
- SQL window functions: top product per category
- RFM segmentation: Champion, Loyal, Potential, At Risk, Lost
- Geospatial order density map (Brazil)
- Delivery time distribution analysis

---

## 📂 Dataset

[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
