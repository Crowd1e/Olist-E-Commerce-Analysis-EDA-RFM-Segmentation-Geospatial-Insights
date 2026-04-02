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

**1. Invest in Customer Retention:**
The RFM analysis reveals a critical retention gap. A targeted win-back campaign for At Risk customers — 
using personalized discounts or reminders — is the highest-ROI short-term action available.

**2. Focus on High-Margin Categories:**
Category profitability is highly concentrated. Marketing spend and seller acquisition 
efforts should prioritize the top 5 categories identified in this analysis to maximize platform-level returns.

**3. Optimize Logistics for Distant Regions:**
The delivery time distribution and geospatial map together suggest that customers in northern and inland Brazil experience longer, 
more variable delivery times. Partnering with regional logistics providers could simultaneously reduce delivery times,
improve review scores, and open new market segments.


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
