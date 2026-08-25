# 🏆 FIFA World Cup 2026: Executive Tournament Intelligence & Tactical xG Analytics
### An End-to-End Enterprise Power BI Platform | Designed & Developed by Zahra Moradi

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Advanced-blue?style=for-the-badge)
![Data Model](https://img.shields.io/badge/Model-Star_Schema-green?style=for-the-badge)
![Transfermarkt](https://img.shields.io/badge/Data-Transfermarkt_Verified-red?style=for-the-badge)

---

## 📌 Project Overview
An executive-level Sports Analytics & Business Intelligence platform designed to analyze the expanded **FIFA World Cup 2026** (48 national teams, 104 matches across USA, Mexico, and Canada). 

The platform bridges **Tactical Match Analytics (Expected Goals - xG)** with **Sports Economics & Moneyball ROI Metrics** using 41,500+ verified Transfermarkt player valuations and official match event datasets.

---

## 📸 Dashboard Architecture (3 Interactive Pages)

### 🔹 Page 1: Tournament Executive Hub
* **Executive KPIs:** Total Matches (104), Total Goals (308), Avg Goals/Match (2.96), Total xG (276.32), Dynamic Champion Determination (**Spain 🇪🇸**).
* **Knockout Stage Matrix:** Drill-down match results, overtime / penalty decisions, and Man of the Match awards across all tournament phases.
* **Host Nation Infrastructure:** Match distribution across host venues (USA 76.9%, MEX 12.5%, CAN 10.6%).
* **Match Progression Analytics:** Expected Goals (xG) vs. Actual Goals scored trend from Group Stage to the Grand Final.

### 🔹 Page 2: Tactical & xG Intelligence
* **Attacking Efficiency Matrix (4-Quadrant Scatter Plot):** Categorizing teams into **Clinical Finishers (Overperforming xG)** vs. **Wasteful / Unlucky (Underperforming xG)** against the parity balance line.
* **Player of the Match Dominance:** Top superstar leaderboard (Lionel Messi with 6 MOTM wins).
* **Match Decision Types:** Analytical breakdown of 90-minute regulation wins vs. Extra Time (AET) and Penalty Shootouts by stage.

### 🔹 Page 3: Squad Financial Efficiency & Economics
* **Moneyball Financial ROI Matrix:** Squad Market Value (€M) vs. Tournament Wins.
* **Cost per Win Metric:** Benchmarking high-efficiency nations (Egypt, Canada, South Africa) against high-expenditure powerhouses (Brazil, Germany, England, France).
* **Global Talent Supply:** Top European clubs supplying tournament market valuation (Paris Saint-Germain, Manchester City, Arsenal, Real Madrid, Barcelona).
* **Continental Wealth Distribution:** Wealth breakdown across UEFA, CONMEBOL, CAF, CONCACAF, AFC, and OFC.

---

## 🛠️ Data Modeling & DAX Engineering
* **Star Schema Architecture:** Dimensional modeling linking `Fact_Matches`, `Dim_Teams`, `Dim_Venues`, and `Dim_Players`.
* **Advanced DAX Measures:**
  * Dynamic Champion detection: `SELECTEDVALUE`, `CALCULATE`, `TOPN`.
  * Multi-dimensional Team Wins calculation (Home / Away / Penalties context resolution using `ALL` & `FILTER`).
  * Financial Efficiency Indices: `Cost per Win`, `SUMMARIZE`, `MAXX`, `DIVIDE`, and string manipulations with `COALESCE` / `TRIM`.
* **UI / UX Design:** Inspired by modern Microsoft Fabric / DataFlip design standards with soft drop shadows, rounded container cards, and high-contrast color palettes.

---

## 👤 Author
* **Lead BI & Data Analyst:** Zahra Moradi
* **GitHub:** [@Zahraaa88](https://github.com/Zahraaa88)
