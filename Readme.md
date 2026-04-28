# IPL Performance Analytics — Capstone 2

> **Uncovering the Winning Formula in Indian Premier League Cricket**

**Data Visualization & Analytics Program | Capstone 2 | April 2026**

---

## Project Overview

This project delivers a complete end-to-end analytics solution for the Indian Premier League (IPL), covering 17 seasons of cricket data from 2008 to 2024. Using Python for the full ETL and analysis pipeline and Tableau for interactive visualisation, we answer the core business question:

> *What strategic, player, and situational factors most significantly determine match outcomes in IPL — and how can franchises use these insights to build winning teams and game plans?*

---

## Dataset

| File | Records | Columns | Source |
|------|---------|---------|--------|
| `matches.csv` | 1,095 | 20 | Kaggle — IPL Complete Dataset |
| `deliveries.csv` | 260,920 | 17 | Kaggle — IPL Complete Dataset |

**Coverage**: 2008–2024 (17 seasons) | 19 franchises | 58 venues

---

## Repository Structure

```
IPL_Capstone_Analytics/
│
├── data/
│   ├── raw/                        # Original unedited files (read-only)
│   │   ├── matches.csv
│   │   └── deliveries.csv
│   └── processed/                  # Cleaned outputs & KPI files
│       ├── matches_clean.csv
│       ├── deliveries_clean.csv
│       ├── kpi_teams.csv
│       ├── kpi_batters.csv
│       ├── kpi_bowlers.csv
│       ├── kpi_phases.csv
│       └── kpi_seasons.csv
│
├── notebooks/
│   ├── 01_data_overview.ipynb      # Dataset profiling
│   ├── 02_cleaning.ipynb           # ETL pipeline (9 transformations)
│   ├── 03_eda.ipynb                # Exploratory data analysis (9 charts)
│   ├── 04_statistical_analysis.ipynb  # Hypothesis testing (5 tests)
│   └── 05_final_load_prep.ipynb    # KPI computation & final export
│
├── tableau/
│   ├── screenshots/                # Dashboard screenshots
│   └── dashboard_links.md          # Tableau Public URL
│
├── docs/
│   └── data_dictionary.md          # Full column-level data dictionary
│
├── reports/
│   ├── figures/                    # All 12 charts (PNG, 150 DPI)
│   ├── IPL_Capstone2_Final_Report.pdf
│   └── IPL_Capstone2_Presentation.pptx
│
└── README.md
```

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/team/IPL_Capstone_Analytics.git
cd IPL_Capstone_Analytics

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scipy

# 3. Run notebooks in order
jupyter notebook notebooks/01_data_overview.ipynb
jupyter notebook notebooks/02_cleaning.ipynb
jupyter notebook notebooks/03_eda.ipynb
jupyter notebook notebooks/04_statistical_analysis.ipynb
jupyter notebook notebooks/05_final_load_prep.ipynb
```

---

## Key Findings

| Finding | Evidence |
|---------|----------|
| Field-first toss strategy wins 53.9% of matches | Chi-square p = 0.009 |
| Death overs generate highest scoring rate | 1.579 runs/ball vs 1.184 in middle |
| 1st innings score correlates with win margin | r = 0.37, p < 0.001 |
| 2024 avg 1st innings = 189.6 runs | Up 25% from 2008 |
| Mumbai Indians lead all-time wins | 144 wins, 55.2% win rate |
| V Kohli is all-time leading run-scorer | 8,014 career IPL runs |
| YS Chahal is all-time leading wicket-taker | 213 career wickets |

---

## Tools & Technologies

| Category | Tools |
|----------|-------|
| Language | Python 3.11 |
| Data Processing | pandas, numpy |
| Visualisation | matplotlib, seaborn |
| Statistical Analysis | scipy.stats |
| Dashboard | Tableau Public |
| Version Control | Git / GitHub |
| Reporting | ReportLab (PDF), PptxGenJS (PPTX) |

---

## Team

| Member | Role | GitHub |
|--------|------|--------|
| Member 1 | Project Lead / ETL Engineer | Advik Khandelwal |
| Member 2 | Data Analyst / Visualisation | Meet Kumar |
| Member 3 | Statistical Analyst | Sahil Kumar |
| Member 4 | KPI Design / Tableau | Manu Pal |
| Member 5 | Reporting & Documentation | Harsh Ahlawat |

---

## Dashboard

**Tableau Public:** https://public.tableau.com/app/profile/manu.pal/viz/ipl_anlytics/IPL_Performance_Analytics_Capstone2?publish=yes

Interactive features: Season filter | Team filter | Phase filter | Dynamic KPI cards

---



