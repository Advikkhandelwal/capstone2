# Tableau Dashboard Links

## Primary Dashboard

**Title:** IPL Performance Analytics — Capstone 2 Interactive Dashboard

**URL:** https://public.tableau.com/app/profile/manu.pal/viz/ipl_anlytics/IPL_Performance_Analytics_Capstone2?publish=yes

---

## Dashboard Views

### View 1: Team Performance Hub
- KPI cards: Win Rate, Total Wins, Toss Win Rate
- Bar chart: Team win rates (all franchises)
- Line chart: Season-by-season performance per team
- Filter: Team, Season Range

### View 2: Player Leaderboard
- Top 15 batsmen — career runs and strike rate
- Top 15 bowlers — career wickets and economy rate
- Filter: Season, Team, Player Search

### View 3: Phase Analysis Board
- Runs per ball by phase (Powerplay / Middle / Death)
- Boundary % by phase
- Wicket density heat map by over number
- Filter: Season, Team

### View 4: Scoring Evolution (2008–2024)
- Dual-line chart: 1st innings vs 2nd innings avg by season
- Year-over-year growth annotation
- Trend line overlay

---

## Screenshots

Screenshots committed to: `tableau/screenshots/`

Files:
- `dashboard_team_performance.png`
- `dashboard_player_leaderboard.png`
- `dashboard_phase_analysis.png`
- `dashboard_scoring_evolution.png`

---

## Technical Notes

- Dashboard built on Tableau Public (free tier)
- Data source: `data/processed/matches_clean.csv` + `data/processed/deliveries_clean.csv`
- All filters are cross-dashboard actions
- Published: April 2026
- Last refreshed: April 2026

---

*Dashboard maintained by: Manu Pal (KPI & Tableau Lead)*
