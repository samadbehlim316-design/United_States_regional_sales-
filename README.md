<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=USA%20Regional%20Sales%20Analysis&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=36&desc=End-to-End%20Sales%20Intelligence%20%7C%20Power%20BI%20%7C%20Python%20EDA&descAlignY=58&descSize=18"/>

<p>
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Orders-64K%2B-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Revenue-%241.2B-purple?style=flat-square"/>
  <img src="https://img.shields.io/badge/Profit%20Margin-37.36%25-green?style=flat-square"/>
</p>

**Maintained by [Samad](https://github.com/samadbehlim316-design)** · Original analysis by [Fateh Sayyed](https://github.com/fatehSayyed)

</div>

---

## 📌 Overview

> **An end-to-end sales analytics project** combining Python Exploratory Data Analysis (EDA) with an interactive Power BI dashboard to uncover revenue drivers, channel efficiency and regional performance patterns across the United States.

The project transforms raw transactional sales data into actionable business intelligence through statistical analysis, clear visualizations and an interactive executive dashboard, supporting data-driven decisions across product, sales and regional teams.

---

## ⚡ Key Metrics at a Glance

<div align="center">

| 💰 Total Revenue | 📈 Total Profit | 📦 Total Orders | 🎯 Profit Margin |
|:-:|:-:|:-:|:-:|
| **$1.2 Billion** | **$461.7 Million** | **64,000+** | **37.36%** |

</div>

---

## 📁 Repository Structure

```
usa-regional-sales-analysis/
│
├── SALES_REPORT.pbix                   # Interactive Power BI dashboard
├── EDA_Regional_Sales_Analysis.ipynb   # Python exploratory data analysis
├── EDA_Dashboard_Report.pdf            # Visual report & dashboard snapshot
├── LICENSE                             # MIT License
├── README.md                           # Project documentation
└── assets/                             # Screenshots & chart exports
    ├── dashboard_page1.jpg
    ├── dashboard_page2.jpg
    └── nb_*.png
```

---

## 📊 Power BI Dashboard — `SALES_REPORT.pbix`

A multi-page interactive dashboard with slicing across time, region, channel and product dimensions.

### Page 1 — Executive Overview, Product & Channel Performance

![Dashboard Page 1](assets/dashboard_page1.jpg)

- **KPI cards:** total revenue, profit, orders and profit margin
- **Profit Pulse:** monthly revenue momentum over time
- **Order Value Spectrum:** histogram of customer spending tiers
- **Unit Price vs. Profit Margin:** scatter plot identifying high-margin price bands
- **Channel Power Play:** revenue share by sales channel
- **Channel Efficiency Scorecard:** margin per sale by route to market
- **High-Margin Heroes:** top products ranked by profit margin
- **Revenue vs. Profitability Matrix:** strategic product positioning

### Page 2 — Geographic & Customer Insights

![Dashboard Page 2](assets/dashboard_page2.jpg)

- **Revenue by US Region:** donut chart of regional contribution
- **Profit Margin % by Region:** margin consistent at roughly 37% across all four regions
- **Bottom 5 Customers by Revenue:** SEINDNI Corp, Voonyx Group, Mycone Ltd, Yodoo Ltd, BB17 Company
- **Bottom 5 States by Revenue:** Wyoming, South Dakota, District of Columbia, Maine, Delaware
- **Customer Profit Margin Distribution:** margin spread across customers

---

## 🐍 EDA Notebook — `EDA_Regional_Sales_Analysis.ipynb`

A Python notebook that profiles the sales dataset and tells the story through visualizations.

### 1. Monthly Sales Trend
![Monthly Sales Trend](assets/nb_monthly_sales_trend.png)

> Monthly revenue fluctuates between **$21M and $26M** over 2014–2018, with a notable dip in early 2017. There is no systemic decline, and seasonal cycles repeat year on year.

### 2. Seasonal Revenue Pattern (Excluding 2018)
![Seasonal Trend](assets/nb_seasonal_trend.png)

> **May** is the peak month at about $102M in aggregate; **February** is the weakest at about $91.5M. This suggests a strong Q2 and a mid-winter lull, useful for timing promotions.

### 3. Top 10 Products by Revenue
![Top 10 Products Revenue](assets/nb_top10_products_revenue.png)

> **Product 26** leads at about $117M, followed by **Product 25** (~$109M) and **Product 13** (~$78M). The top three products account for a large share of sales, indicating revenue concentration risk.

### 4. Top 10 Products by Average Profit
![Top 10 Products Margin](assets/nb_top10_products_margin.png)

> **Product 18** has the highest average profit (~$8,500 per unit), followed by **Product 28** and **Product 5**. High-revenue products are not always the most profitable, which matters for portfolio decisions.

### 5. Total Sales by Channel
![Sales by Channel](assets/nb_sales_by_channel.png)

> **Wholesale** leads with **54.1%** of sales, followed by **Distributor** (31.3%) and **Export** (14.6%). All channels hold similar margins (~37–38%).

### 6. Distribution of Average Order Value
![Order Value Distribution](assets/nb_order_value_distribution.png)

> Most orders fall in the **$0–$100K** range, with a strongly right-skewed distribution. Orders above $300K are rare but may represent bulk buyers worth dedicated account management.

### 7. Profit Margin % vs. Unit Price
![Margin vs Unit Price](assets/nb_margin_vs_unitprice.png)

> Margins (15–60%) are spread fairly evenly across price bands ($0–$7K), suggesting margin depends more on product and cost structure than on price tier.

### 8. Total Sales by US Region
![Sales by Region](assets/nb_sales_by_region.png)

> **West** leads (~$370M), followed by **South** (~$335M) and **Midwest** (~$320M). **Northeast** trails at ~$210M, a possible growth opportunity.

### 9. Top & Bottom 10 Customers by Revenue
![Top Bottom Customers](assets/nb_top_bottom_customers.png)

> **Aibox Company** ($12.5M) and **State Ltd** ($12.3M) are the top customers. **BB17 Company** and **Yodoo Ltd** are among the lowest at under $4.5M, flagging accounts for development or review.

### 10. Average Profit Margin by Channel
![Margin by Channel](assets/nb_margin_by_channel.png)

> Margins are nearly identical: **Export 37.93%**, **Distributor 37.56%**, **Wholesale 37.09%**. No channel shows a markedly different margin from the others.

### 11. Customer Segmentation — Revenue vs. Profit Margin
![Customer Segmentation](assets/nb_customer_segmentation.png)

> Customers cluster between **$4M–$13M** in revenue and **34%–43%** in margin (bubble size = order volume). The upper-right quadrant holds high-revenue, high-margin accounts; high revenue with low margin warrants a cost review.

---

## 💡 Key Business Insights

**Regional strategy**
- All four regions keep a margin of about 37%, showing consistent pricing discipline.
- Northeast lags in revenue and is a candidate for sales expansion.
- Wyoming, Maine and Delaware are among the bottom-5 states, so localized campaigns may help.

**Channel efficiency**
- Margins are near-uniform (~37–38%) across channels.
- Wholesale drives the most volume (54%); scaling it has the largest revenue impact.
- Export has the highest margin (37.93%) on the smallest volume, so it has growth potential.

**Product portfolio**
- Product 26 leads revenue: protect and scale it.
- Product 18 leads profit per unit: promote it in high-value segments.
- High revenue does not imply high profitability, so the portfolio needs balance.

**Customer insights**
- Top customers contribute roughly $10–13M each, showing key-account dependency.
- February is the weakest month; plan promotions accordingly.
- May peaks at about $102M; use it for launches.

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| **Language** | Python 3.10+ |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **BI Dashboard** | Microsoft Power BI |
| **Notebook** | Jupyter Lab / Jupyter Notebook |
| **Version Control** | Git & GitHub |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10 or higher
- Jupyter Notebook or JupyterLab
- Power BI Desktop (to open the `.pbix` file)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/samadbehlim316-design/usa-regional-sales-analysis.git

# 2. Move into the project directory
cd usa-regional-sales-analysis

# 3. Install the required packages
pip install pandas numpy matplotlib seaborn plotly jupyter

# 4. Launch the notebook
jupyter notebook EDA_Regional_Sales_Analysis.ipynb
```

### Opening the Power BI Dashboard
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Open `SALES_REPORT.pbix`.
3. Use the slicers to filter by **Year**, **Month**, **Region** or **Channel**.

---

## 🔮 Future Enhancements

- [ ] Revenue forecasting with ARIMA / Prophet
- [ ] State-level choropleth map in Power BI
- [ ] Automated data refresh pipeline (Python + Power BI API)
- [ ] Automated report email distribution
- [ ] Customer segmentation with K-Means clustering
- [ ] Power BI mobile layout optimization
- [ ] Product affinity (market basket) analysis

---

## 🤝 Credits

- **Original analysis, notebook and dashboard:** [Fateh Sayyed](https://github.com/fatehSayyed) — [original repository](https://github.com/fatehSayyed/usa-regional-sales-eda)
- **Maintained and adapted by:** [Samad](https://github.com/samadbehlim316-design)

Shared and adapted with the original author's permission.

## 📬 Contact

**Samad**
- GitHub: [github.com/samadbehlim316-design](https://github.com/samadbehlim316-design)
- Email: samadbehlim316@gmail.com

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
