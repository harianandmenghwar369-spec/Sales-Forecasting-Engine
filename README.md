# Sales-Forecasting-Engine

Excel-based sales forecasting engine with seasonal decomposition, FORECAST.ETS projections, confidence intervals, and a live KPI dashboard — no macros, no plugins.

# 📊 Sales Forecasting Engine — FreelanceDesk

> A production-ready Excel forecasting model using **FORECAST.ETS** with seasonal decomposition, confidence intervals, and automated KPI dashboards.

---

## 🔍 Overview

This model takes 3 years of monthly sales data and produces:
- 12-month forward revenue projections with **95% confidence intervals**
- Automatic **seasonality detection** (seasonal index per month)
- **Year-over-Year growth analysis** across all 12 months
- Live **KPI dashboard** that updates when you change inputs

Built for freelancers, small business owners, and finance analysts who want a robust forecasting tool without needing a data science background.

---

## 📁 File Structure

| Sheet | Description |
|-------|-------------|
| `1. Data Input` | Enter monthly sales data here (Units, Revenue, Product, Notes) |
| `2. Trend Analysis` | Auto-calculated seasonality index + YoY growth table |
| `3. Forecast Engine` | 12-month projection with confidence intervals + target tracking |
| `4. Dashboard` | Live KPIs — total revenue, growth rate, forecast vs target |

---

## 📈 What the Model Shows (Sample Data)

| Metric | Value |
|--------|-------|
| Total 2024 Revenue | **$707,592** |
| YoY Growth (2023 → 2024) | **+11.6%** |
| Best Month 2024 | **December ($75,800)** |
| 12-Month Forecast (2025) | **$828,490** |
| Peak Season | **Nov–Dec (Seasonal Index > 1.2x)** |
| Weakest Month | **February (Seasonal Index 0.74x)** |

---

## ⚙️ How to Use

1. **Open `1. Data Input`** — enter your own monthly data (Month, Year, Product, Units, Revenue)
2. All other sheets **auto-update** — no manual formulas needed
3. In `3. Forecast Engine`, adjust the yellow assumption cells:
   - Growth rate (default: 8%)
   - Confidence interval (default: 95%)
   - Monthly revenue target (default: $80,000)
4. Check `4. Dashboard` for live KPIs and automated insights

> 💡 Blue cells = inputs you can change. Yellow cells = key assumptions. Black cells = formulas (do not edit).

---

## 🧠 Methodology

- **Forecasting**: Excel `FORECAST.ETS` function — exponential smoothing that accounts for seasonal patterns
- **Seasonality**: 3-year average monthly index (e.g., December = 1.29x average, February = 0.74x)
- **Confidence Intervals**: `FORECAST.ETS.CONFINT` at 95% level
- **Growth Trend**: Rolling YoY average per month, tracked directionally

---

## 📊 Key Seasonal Insights (from sample data)

| Season | Months | Index | Status |
|--------|--------|-------|--------|
| 🔥 Peak | Jun, Aug, Nov, Dec | > 1.06x | High demand |
| ✓ Normal | May, Jul, Sep, Oct | ~1.0x | Baseline |
| ❄️ Low | Jan, Feb, Mar, Apr | < 0.93x | Plan cash flow carefully |

---

## 🚀 Use Cases

- **Freelancers** tracking project revenue and forecasting pipeline
- **Small business owners** doing monthly financial planning
- **Finance analysts** who need a clean, auditable Excel model
- **Startup founders** modeling revenue for investor decks

---

## 🛠️ Requirements

- Microsoft Excel 2016+ or Excel 365 (for `FORECAST.ETS` function)
- LibreOffice Calc 6.0+ (limited FORECAST.ETS support)
- No macros, no add-ins — pure Excel formulas

---

## 📂 Data Included

The file ships with **3 years of sample data** (2022–2024, Product A, 36 months) so you can see how the model works before entering your own numbers.

---

## 🤝 Contributing

Found a bug or want to add a feature? Open an issue or submit a PR. Suggestions welcome:
- Multi-product support
- Scenario comparison (base / bull / bear)
- Automated email alerts when forecast misses target

---

## 🧑‍💻 About the Author

**Hari — Data Analytics & Finance Specialist**
* 📍 **Location:** Karachi, Pakistan
* 📈 **Focus:** Translating operational volumes and transaction structures into polished, formula-driven financial frameworks.
* ⚙️ **Expertise:** Advanced Excel & VBA, Linked Financial Modeling, Interactive Dashboards, and Data Sanitization.

### Get In Touch
* **Fiverr:** [hari_dm](https://www.fiverr.com/hari_dm)
* **LinkedIn:** [Connect on LinkedIn](https://linkedin.com)
---

*Built with ❤️ using pure Excel formulas. No VBA. No plugins. Just math.*
