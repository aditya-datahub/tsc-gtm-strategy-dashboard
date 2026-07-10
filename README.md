<div align="center">

# 🌱 The Sustainability Cloud (TSC) — GTM Strategy Dashboard

### A data-driven Go-To-Market strategy for an ESG SaaS platform entering the Indian services sector (2026)

**Power BI · Business Strategy · ESG Analytics · India Market**

[![Power BI](https://img.shields.io/badge/Built%20with-Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)]()

[View Dashboard Screenshots](#️-dashboard-walkthrough) · [Explore the Data](#-data-model) · [Read the Summary Note](docs/TSC_GTM_Dashboard_Summary_Note.pdf)


</div>

---

## 📌 Overview

**The Sustainability Cloud (TSC)** is a fictional ESG SaaS company offering three integrated products — **Net Zero (carbon)**, **Energy**, and **Water Offset** — to help large Indian enterprises meet tightening sustainability regulations (BRSR, SEBI, CBAM, SBTi).

This project takes a narrative, text-heavy GTM strategy document and turns it into a **5-page interactive Power BI dashboard** that lets a reader grasp TSC's entire go-to-market plan in minutes — while still allowing them to drill into the underlying data through filters and tables.

**The core business question this project answers:**
> *Which industries should TSC target first, what should it sell to them, who should it talk to, and how should it execute the first 90 days?*

---

## 🎯 Why This Project

Indian companies in the services sector face rising pressure from regulators, investors, and customers to actively reduce — not just report — their environmental footprint. This creates a real market opportunity for an ESG software provider like TSC. The goal of this exercise was to:

- Convert a dense strategy document into a **clear, visual, interactive story**
- Apply a structured **industry prioritization framework** (not just gut-feel targeting)
- Map the **competitive landscape** to justify TSC's differentiation
- Identify the **exact stakeholders and regulations** that create urgency to buy
- Translate strategy into a **concrete, KPI-driven 90-day execution plan**

---

## 🖼️ Dashboard Walkthrough

The dashboard follows a single logical storyline across 5 pages — from the big picture down to day-by-day execution.

| # | Page | Guiding Question | What It Shows |
|---|------|-------------------|----------------|
| 1 | **Executive Overview** | What is this strategy about? | Headline KPIs, executive summary, product suite |
| 2 | **Industry & Market Analysis** | Where should TSC focus? | 8-criteria industry prioritization matrix, target account list, pain points |
| 3 | **Product Strategy & Competition** | What should TSC sell, and to whom? | Product-market fit, 10-company competitive benchmark, "Why TSC Wins" |
| 4 | **Stakeholder & Regulatory Landscape** | Who to engage, and why now? | Stakeholder priority map, India + global regulatory triggers |
| 5 | **90-Day GTM Execution Plan** | How and when to execute? | 3-phase rollout plan with KPI targets and key activities |

<br>

### 📊 Page 1 — Executive Overview

Sets the scale of the strategy: **3 target industries, 50 target companies, 90-day timeline, 2–3 early wins.** Summarizes the target market, key buyers (CFO, CSO, ESG Head), and TSC's 3-product suite.

![Executive Overview](images/Executive%20Overview.png)

<br>

### 📊 Page 2 — Industry & Market Analysis

An 8-criteria matrix (ESG maturity, regulatory pressure, spending capacity, ease of entry, etc.) compares **IT & ITES, BFSI, and Healthcare**, color-coded for instant readability.

**Result: IT & ITES ranks highest (5★)** — most ESG-mature, strongest budgets, easiest entry — followed by BFSI and Healthcare (4★ each).

![Industry & Market Analysis](images/Industry%20%26%20Market%20Analysis.png)

<br>

### 📊 Page 3 — Product Strategy & Competition

Maps TSC Net Zero / Energy / Water Offset against each industry's needs, then benchmarks TSC against **10 competitors** (Persefoni, IBM Envizi, Salesforce Net Zero Cloud, Schneider Electric, Honeywell, and others).

**Finding: no competitor offers Carbon + Energy + Water in a single, India-focused platform — TSC is the only integrated, India-first solution in the set.**

![Product Strategy & Competition](images/Product%20Strategy%20%26%20Competition.png)

<br>

### 📊 Page 4 — Stakeholder & Regulatory Landscape

Identifies the **"power triangle"** — CFO, Chief Sustainability Officer, and ESG Head — as the highest-priority buyers, and lists the regulations (BRSR, BRSR Core, SEBI, CBAM, CDP, SBTi, TCFD, GHG Protocol) that are converting sustainability from a reporting exercise into a budgeted, urgent initiative.

![Stakeholder & Regulatory Landscape](images/Stakeholder%20%26%20Regulatory%20Landscape.png)

<br>

### 📊 Page 5 — 90-Day GTM Execution Plan

Breaks execution into three phases:

- **Phase 1 — Foundation (Day 0–30):** 50 target companies, 100 key contacts, 20 discovery calls, 10 qualified opportunities
- **Phase 2 — Engagement (Day 31–60):** 20 customer meetings, 10 workshops, 5 proposals, 3 pilot discussions
- **Phase 3 — Conversion (Day 61–90):** 2–3 live pilots, 2 early wins, 1 reference account, 4x revenue pipeline

![90-Day GTM Execution Plan](images/90-Day%20GTM%20Execution%20Plan.png)

---

## 💡 Key Strategic Takeaways

- 🏆 **IT & ITES is the #1 target vertical** — highest ESG maturity, strongest spending capacity, easiest path to entry
- 🔺 **The "power triangle" of CFO + CSO + ESG Head** must all be aligned before any deal closes
- 🧩 **TSC's integrated 3-in-1 offering** (carbon + energy + water) is a clear differentiator — every competitor benchmarked covers only one dimension
- 📜 **Regulation is the sales trigger** — BRSR, SEBI, CBAM, and SBTi are converting sustainability into a budgeted, board-level priority
- 🗓️ **90 days, 3 phases** — a disciplined path from pipeline creation to 2–3 referenceable early wins

---

## 🗂️ Repository Structure

```
tsc-gtm-strategy-dashboard/
│
├── dashboard/                  # Power BI dashboard file (.pbix) & exports
├── data/                       # Source CSV data model
│   ├── 1_industry_matrix.csv
│   ├── 2_companies_and_products.csv
│   ├── 3_stakeholders.csv
│   ├── 4_competition.csv
│   └── 5_roadmap.csv
├── images/                     # Dashboard page screenshots
├── docs/                        # Supporting documents
│   ├── TSC_GTM_Dashboard_Summary_Note.pdf
│   └── TSC_Gallery_Carousel.pdf
├── problem_statement/          # Original GTM strategy brief
├── LICENSE
└── README.md
```

---

## 🧮 Data Model

The dashboard is powered by five structured CSV tables, each feeding a specific page:

| File | Rows Cover | Feeds Page |
|------|-----------|------------|
| `1_industry_matrix.csv` | 8 prioritization criteria × 3 industries, with numeric scores | Industry & Market Analysis |
| `2_companies_and_products.csv` | 11 target companies with ESG commitments, target years, product fit, pain points | Industry Analysis / Product Strategy |
| `3_stakeholders.csv` | 6 stakeholder roles + 10 regulations, each with a priority score | Stakeholder & Regulatory Landscape |
| `4_competition.csv` | TSC vs. 10 competitors across Carbon / Energy / Water / India Focus | Product Strategy & Competition |
| `5_roadmap.csv` | 14 KPI/activity rows across 3 execution phases | 90-Day GTM Execution Plan |

All matrices use a **weighted scoring model** (1–5 scale) so that qualitative judgments ("High", "Very Strong") are backed by a consistent, auditable numeric score — not just color and opinion.

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — data modeling, DAX-driven filters, interactive report pages
- **Excel / CSV** — source data structuring and scoring model
- **Business frameworks** — prioritization matrices, stakeholder mapping, competitive benchmarking, phased GTM planning
- **Regulatory research** — BRSR, BRSR Core, SEBI ESG norms, CBAM, CDP, GHG Protocol, ISSB S1 & S2, SBTi, TCFD

---

## 🚀 How to View the Dashboard

1. Clone or download this repository
2. Open `dashboard/TSC_GTM_Strategy_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft)
3. Use the **Filter by Industry** buttons (Page 2 & 3) and **Filter by Phase** buttons (Page 5) to explore the data interactively
4. Alternatively, browse the static screenshots in the [`images/`](images) folder or the [gallery carousel PDF](docs/TSC_Gallery_Carousel.pdf)

---

## 📄 Supporting Documents

- **[Project Summary Note](docs/TSC_GTM_Dashboard_Summary_Note.pdf)** — full written walkthrough of the business context, dashboard structure, and strategic takeaways
- **[Gallery Carousel](docs/TSC_Gallery_Carousel.pdf)** — a swipeable visual summary of all 5 dashboard pages, ready to share on LinkedIn
- **[Original Problem Statement](problem_statement)** — the GTM strategy brief this dashboard was built from

---

## 👤 Author

**Aditya Sharma**
*Prepared for internal circulation / portfolio demonstration*

📫 Feedback and suggestions for refinement are always welcome — feel free to open an issue or connect.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

<div align="center">

⭐ **If you found this project useful or interesting, consider starring the repo!** ⭐

</div>
