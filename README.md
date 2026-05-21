# US Housing Market Analysis
## Python · Tableau · Power BI | Zillow ZHVI Data (2015–2024)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## Project Overview
A comprehensive end-to-end analysis of the US housing
market using Zillow's Home Value Index (ZHVI) data across
50 states and 100+ metro areas. Built across three tools
to demonstrate a full analyst toolkit — Python for deep
statistical analysis, Tableau for interactive web
visualization, and Power BI for enterprise BI reporting.

---

## 📊 Interactive Dashboards

### Tableau Dashboard
👉 **[View Tableau Dashboard](https://public.tableau.com/app/profile/varshini.karuppusamy/viz/USHousingMarketAnalysisDashboard_17793122619840/Dashboard1)**

### Power BI Dashboard
📄 **[View Power BI PDF](US Housing Market Analysis using Zillow data_PowerBI)**

---

## 📊 Dashboard Previews

### Power BI Dashboard
📄 **[View Power BI PDF](PowerBI/US_Housing_Market_Analysis_using_Zillow_data_PowerBI.pdf)**

![Power BI Dashboard](plots/US_Housing_Market_PowerBI.png)

### Tableau Dashboard
👉 **[View Tableau Dashboard](YOUR TABLEAU PUBLIC URL HERE)**

![Tableau Dashboard](plots/US_Housing_tableau.png)

---

## Dataset
| Detail | Value |
|--------|-------|
| Source | Zillow Research Data (ZHVI) |
| Geography | 50 States + 100+ Metros + Cities |
| Period | January 2015 – December 2024 |
| Frequency | Monthly |
| Key Metric | Zillow Home Value Index (ZHVI) |
| Access | Free at zillow.com/research/data |

---

## Business Questions Answered
- How have home prices trended across US states (2015–2024)?
- Which cities and metros are most overvalued vs affordable?
- How did COVID-19 impact housing prices across markets?
- What is the affordability index by state?
- Can we predict future home values using regression?
- Which markets show the fastest appreciation rates?

---

## Tools Used

| Tool | Purpose | Output |
|------|---------|--------|
| Python (Pandas) | Data cleaning, EDA, regression | Jupyter Notebook |
| Seaborn/Matplotlib | Statistical visualizations | 12 PNG charts |
| Scikit-learn | Linear regression + forecast | Predictive model |
| Folium | Interactive choropleth map | HTML map |
| Tableau Public | Interactive web dashboard | Published URL |
| Power BI Desktop | Enterprise BI dashboard | .pbix + PDF |

---

## Python Analysis Sections

### Day 1–2: Data Acquisition & Cleaning
- Downloaded 3 Zillow CSV files (state, metro, city)
- Reshaped wide-format data to long format
- Fixed date types and removed nulls
- Saved clean files for Tableau and Power BI

### Day 3: National Trend Analysis
- National home value trend with COVID annotation
- Year-over-year price change bar chart

### Day 4: State-Level Analysis
- Top 15 most expensive states
- Price appreciation ranking (2015–2024)
- Trend comparison for top 5 states

### Day 5: Metro Market Analysis
- Most expensive vs most affordable metros
- COVID-19 impact by metro area

### Day 6: Affordability Index
- Home value ÷ median household income by state
- Reference lines at 3x, 5x, and 8x thresholds

### Day 7: Correlation Analysis
- Mortgage rate vs home price dual-axis chart
- Pearson correlation calculation

### Day 8: Linear Regression Model
- Train on 2015–2022, test on 2023–2024
- 24-month forecast with confidence band
- R² score and MAE metrics
- State-level monthly appreciation rates

### Day 9: Folium Interactive Map
- Choropleth map of home values by state
- Tooltips showing value and affordability ratio

### Day 10: Summary Dashboard
- 4-panel summary visualization
- 6 key findings and business insights

---

## Key Findings

1. **National home values grew ~50%** from 2015–2024
   driven by COVID-era demand and low mortgage rates

2. **Hawaii, California, and Massachusetts** are
   consistently the most expensive states with
   typical values exceeding $700K–$800K

3. **Affordability crisis** — California and Hawaii
   have ratios exceeding 8–10x median annual income

4. **COVID surge (2020–2022)** caused the sharpest
   price increase in modern housing history —
   some Sun Belt metros saw 40–50% gains

5. **Regression model (R² > 0.90)** forecasts
   continued appreciation through 2026 at
   ~$1,000–1,500/month nationally

6. **Sun Belt markets** (Florida, Texas, Arizona)
   showed the fastest appreciation driven by
   migration and relative affordability

---

## Tableau Dashboard Features
- National trend area chart with year filter
- Filled US map colored by home value
- Top 15 states ranked bar chart
- Affordability index with reference lines
- Cross-filtering — click any state to filter all charts

## Power BI Dashboard Features
- 3 KPI cards (national avg, latest value, states count)
- National trend line chart
- Filled state map with color saturation
- Top 15 states bar chart
- YoY price change column chart
- Affordability index bar chart
- Year range slicer and state dropdown slicer

---

## How to Run Python Notebook

```bash
# Clone the repository
git clone https://github.com/yourusername/
US-Housing-Market-Analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn
pip install scikit-learn folium requests

# Download Zillow data from zillow.com/research/data
# Save as zhvi_state.csv, zhvi_metro.csv, zhvi_city.csv

# Open notebook
jupyter notebook US_Housing_Market_Analysis.ipynb

# Run all cells top to bottom
```

---

## Skills Demonstrated
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn`
`Scikit-learn` `Linear Regression` `Folium`
`Time-Series Analysis` `Predictive Modeling`
`Tableau` `Power BI` `DAX` `Data Storytelling`
`Housing Analytics` `Affordability Analysis`
`Statistical Testing` `Interactive Dashboards`

---

## Author
**Varshini Karuppusamy**
MS Engineering Management — Northeastern University '26
📧 karuppusamy.v@northeastern.edu

---

## Data Attribution
Zillow Home Value Index (ZHVI) data provided by
Zillow Research — zillow.com/research/data
All data used under Zillow's public data terms of use.

---

