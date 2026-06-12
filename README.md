# 📊 Sales Analysis Project (2021–2024)  
### *From Raw Data to Actionable Business Insights*

---

## 🚀 Executive Summary for Managers

This project delivers a **complete, data‑driven analysis** of retail sales over four years.  
We transformed raw transactional data into **clear KPIs, risk warnings, and concrete recommendations** – all backed by statistical evidence and visual dashboards.

**Key business questions answered:**
- Which products drive revenue? (Spoiler: one product accounts for **60%** – a major risk.)
- Where is the company most profitable? (East region leads; West lags.)
- When are sales highest? (December peak – real, not random.)
- How do discounts affect profit? (Discounts >20% **halve** average profit.)

**The bottom line:**  
With a **$136M revenue** and **16% profit margin**, the business is healthy – but it faces **extreme product concentration risk** and an **inefficient discount strategy** that erodes earnings.

---

## 📌 Key Performance Indicators (KPIs)

| Metric | Value | Insight |
|--------|-------|---------|
| Total Revenue | **$136.5M** | Solid 4‑year performance |
| Total Profit | **$21.8M** | Healthy absolute profit |
| Profit Margin | **16.0%** | Within healthy retail range (10‑20%) |
| Average Order Value | **$6,595** | High‑ticket B2B / premium model |
| Return Rate | **~0.06%** | Excellent product quality |

---

## 🔍 Critical Findings (What Managers Need to Know)

### 1. ⚠️ Extreme Product Concentration – **High Risk**
- **One product** – *Cisco TelePresence System* – generates **60% of total revenue**.
- The next nine products together add only ~27%.
- **Risk:** A demand drop or supply disruption would collapse revenue.

### 2. 📈 Seasonal Sales Pattern – **Q4 Opportunity**
- December sales are **statistically higher** than January (p=0.000).
- Sales rise steadily from February to December.
- **Action:** Increase marketing and inventory from **October to December**.

### 3. 💸 Discount Strategy Is Hurting Profit
| Discount Range | Average Profit per Order |
|----------------|--------------------------|
| 0‑10%          | $1,058                   |
| 10‑20%         | **$1,167** (best)        |
| 20‑30%         | $604  (‑48%)             |
| 30‑50%         | $599                     |
| 50‑100%        | $971 (inconsistent)      |

- Discounts above 20% **slash profit by nearly half**.
- **Recommendation:** Cap discounts at 25% for most products.

### 4. 📍 Regional Performance – Hidden Profit Gaps
| Region | Revenue | Profit Margin |
|--------|---------|----------------|
| East   | $31.1M  | **16.6%** (best) |
| South  | $36.7M  | 16.1%          |
| Central| $34.0M  | 16.1%          |
| West   | $34.8M  | **15.2%** (worst) |

- West region lags in profitability – investigate higher costs or discounting.

### 5. 📅 Yearly Growth – Finally Turning Around
- 2021‑2023: flat revenue (~$33.5M).
- **2024: +5.1% growth** to $35.6M.
- **Question:** What changed? (New product? Marketing campaign?) – replicate those drivers.

---

## 💡 Actionable Recommendations (For Management)

| Priority | Action | Expected Benefit |
|----------|--------|------------------|
| 🔴 High | **Diversify product portfolio** – reduce reliance on Cisco TelePresence | Mitigate single‑SKU risk |
| 🔴 High | **Cap discounts at 25%** | Protect profit margins |
| 🟡 Medium | **Increase Q4 marketing** (Oct‑Dec) | Capture seasonal peak |
| 🟡 Medium | **Investigate West region** – lower margins | Unlock hidden profit |
| 🟢 Low | **Loyalty program for top 10 customers** | Retain high‑value clients |

---

## 🛠 Technical Summary (For the Team)

- **Dataset:** ~24k rows, 20 columns (superstore sales, 2021–2024)
- **Tools:** Python (pandas, numpy, matplotlib, seaborn, scipy), Jupyter Notebook
- **Process:**
  1. Data cleaning (missing values, type conversion, discount capping)
  2. KPI calculation (revenue, profit, AOV, return rate)
  3. Advanced analysis (region, product concentration, seasonality t‑test)
  4. Visualisations (7 charts: monthly trend, top products, regional revenue/margin, discount scatter, yearly sales)
  5. Export of PDF report + CSV summaries
- **Outputs:**
  - `Sales_Analysis_Report.pdf` – complete report with charts
  - `kpi_summary.csv`, `region_performance.csv`, `top_products.csv`
  - `one_page_summary.txt` – quick reference

---

## 📂 Project Structure (Simplified)
Sales_Analysis_Project/
├── Data/ # Place superstore_sales.csv here
├── Notebook/ # Jupyter notebook with full analysis
├── Charts/ # Generated PNG images
├── Reports/ # Final PDF report, CSV and text summaries
├── requirements.txt # Python dependencies
└── README.md # This file

text
