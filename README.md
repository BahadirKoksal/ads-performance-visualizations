# 📈 Ads Performance Visualizations — Google Sheets

## 🎯 Objective

This project visualizes annual Google Ads and Facebook Ads performance data for a Netflix marketing analytics scenario. The goal is to go beyond tables and communicate performance trends, budget efficiency, and channel comparisons through clear, actionable charts.

**Key Questions Answered Visually:**
- How did daily and monthly click volume change throughout the year?
- How did ad spend and return on ad spend (ROAS) move together month by month?
- Is there a relationship between monthly spend and revenue?
- How do Google Ads and Facebook Ads compare across key metrics?

---

## 📁 Data Source

**Platform:** Google Sheets  
**Live Spreadsheet:** [View on Google Sheets](https://docs.google.com/spreadsheets/d/1sJc2MrZ_zfRWvI5YhrLvpkknNtit-SCO8YDt7pPShG4/edit)  
**Period:** January – December 2023  
**Channels:** Google Ads, Facebook Ads

---

## 📊 Charts

### 1. Daily Clicks — Google Ads (2023)
![Daily Clicks - Google Ads](Daily%20Clicks%20-%20Google%20Ads.png)

A bar chart showing daily click volume throughout the year. This chart illustrates a key data visualization lesson: **when there are too many data points, daily granularity makes it nearly impossible to identify trends.** Moving to monthly aggregation is necessary for meaningful analysis. Daily clicks also have limited value as a standalone KPI — they don't reflect conversions, revenue, or true campaign success.

---

### 2. Monthly Clicks and Impressions
![Monthly Clicks and Impressions](Monthly%20Clicks%20and%20Impressions.png)

A dual-axis bar chart showing monthly clicks (left axis) and impressions (right axis). Two separate axes are used because the scale difference between clicks and impressions would make one metric nearly invisible on a shared axis. December shows a clear spike in both metrics, consistent with holiday season consumer behavior.

---

### 3. Monthly Ad Spend — Google Ads (2023)
![Monthly Ad Spend - Google Ads](Monthly%20Ad%20Spend%20-%20Google%20Ads.png)

A bar chart showing monthly ad spend across the year. Spend was relatively stable from January through November, with a significant spike in December — reflecting an intentional budget increase to capitalize on the Christmas shopping season.

---

### 4. Monthly Ad Spend + ROAS — Combo Chart
![Monthly Ad Spend + ROAS combo](Monthly%20Ad%20Spend%20+%20ROAS%20combo.png)

A combo chart with monthly spend as bars (left axis) and ROAS as a line (right axis). This chart reveals a critical insight: **higher spend does not necessarily mean higher ROAS.** Despite December's spend spike, ROAS stayed relatively flat — suggesting the marginal return on additional December budget was limited. Mid-year months (Jan–Feb) show stronger ROAS relative to spend.

---

### 5. Monthly Spend vs Revenue + Trend Line
![Spend + Revenue + Trend line](Spend%20+%20Revenue%20+%20Trend%20line.png)

A dual-axis combo chart comparing monthly spend (bars, left axis) and revenue (bars, right axis), with a trend line added to revenue. The R² value of 0.045 indicates a very weak correlation between spend and revenue month-to-month — meaning simply increasing budget does not reliably drive proportional revenue growth. Other factors (seasonality, audience intent, creative performance) play a significant role.

---

## 💡 Key Insights

**Granularity matters.** Daily data is useful for operational monitoring but too noisy for strategic decisions. Monthly aggregation reveals meaningful patterns.

**ROAS doesn't scale linearly with spend.** December's budget spike did not produce a proportional ROAS improvement — suggesting diminishing returns at high spend levels.

**Spend and revenue are weakly correlated (R² = 0.045).** Budget alone doesn't drive revenue. Campaign quality, seasonality, and audience targeting are equally important drivers.
