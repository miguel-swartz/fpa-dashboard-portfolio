# Vegapunk Semiconductor — FP&A Dashboard

**Live demo:** [miguel-swartz.github.io/fpa-dashboard-portfolio](https://miguel-swartz.github.io/fpa-dashboard-portfolio)

A fully interactive Financial Planning & Analysis dashboard built as a portfolio project to demonstrate real-world FP&A skills. The fictional company Vegapunk Semiconductor, Inc. serves as the data context — a fabless logic chip design company based in Austin, TX.

---

## What This Dashboard Does

This project simulates the core outputs of a corporate FP&A function: a 12-month rolling budget vs actual analysis with executive-ready visualizations, management commentary, and AI-generated CFO summaries.

**Five analysis views:**
- **Monthly Table** — Full budget vs actual variance table across Revenue, COGS, Gross Profit, OpEx, and EBITDA for all 12 months with dollar and percentage variances
- **Revenue Trends** — Line chart comparing monthly revenue budget vs actual
- **EBITDA Bridge** — Grouped bar chart showing EBITDA budget, actual, and monthly variance
- **Margin Trends** — GP% and EBITDA% trend lines showing margin stability throughout the year
- **YTD Cumulative** — Running total view showing how the budget gap opened and closed across the year

**Additional sections:**
- KPI cards for FY Revenue, EBITDA, Margin, Best Month, and Hardest Month
- Quarterly management commentary with business-context explanations for each variance
- Full Year Waterfall comparing Revenue → COGS → Gross Profit → OpEx → EBITDA
- Rolling Forecast for Q1 2026 with methodology and assumptions
- AI-powered CFO executive summary via Claude API (requires Anthropic API key)

---

## Skills Demonstrated

| Category | Skills |
|---|---|
| **FP&A Methodology** | Budget vs actual variance analysis, rolling forecasts, P&L structure, EBITDA bridge, management commentary |
| **Financial Modeling** | DCF valuation, 3-statement modeling, sensitivity analysis, Monte Carlo simulation (coursework) |
| **Technical** | Advanced Excel (PivotTables, VLOOKUP, INDEX/MATCH, VBA), Python, JavaScript, HTML/CSS |
| **Tools** | Claude AI, Chart.js, GitHub Pages, Bloomberg Financial Fundamentals |
| **Languages** | Bilingual — English & Spanish |

---

## How to Use the AI Summary Feature

1. Get a free API key at [console.anthropic.com](https://console.anthropic.com)
2. Enter the key in the "Anthropic API Key" field on the dashboard
3. Click **Generate Summary** — Claude produces a structured four-section CFO report from the actual variance data

Your key is used only in your browser and is never stored or logged.

---

## About the Data

All financial figures are fictional and designed to reflect a realistic semiconductor manufacturing company. The dataset deliberately includes a challenging year with a Q1 miss, mid-year recovery, Q3 OpEx pressure, and strong December close — to demonstrate meaningful variance analysis rather than a flat, predictable dataset.

---

## Built By

**Miguel Eduardo Swartz**  
BBA Finance, Texas Tech University — Rawls College of Business  
Bilingual: English & Spanish  
[LinkedIn](https://linkedin.com/in/miguel-swartz) · Austin, TX
