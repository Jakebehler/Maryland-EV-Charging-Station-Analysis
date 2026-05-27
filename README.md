# Maryland EV Charging Station Analysis

## Project Overview
Analyzed 1,680 public EV charging stations across Maryland using SQL and MySQL Workbench to uncover infrastructure gaps, network dominance, and charging accessibility patterns. Data sourced from the U.S. Department of Energy's Alternative Fuels Data Center.

---

## Key Findings

### Baltimore Dominates but Fast Charging is Concentrated Elsewhere
Baltimore has 107 stations, more than 8x the next city, but the highest concentrations of DC fast chargers are in Salisbury (ZIP 21801) and Annapolis (ZIP 21401), suggesting long-distance corridor charging is prioritized outside the city.

### Tesla Controls Fast Charging Infrastructure
Tesla accounts for 164 of Maryland's 231 total DC fast chargers, representing 100% of its charger mix dedicated to fast charging. ChargePoint, despite having 88 stations, has only 7 DC fast chargers, making it primarily a Level 2 network.

### Most of Maryland Has No Fast Charging Access
120 out of 135 cities in Maryland have zero DC fast chargers. Level 2 chargers are the backbone of the state's infrastructure with 739 total ports vs. 231 DC fast, leaving most communities without fast charging options.

### Pricing Data is Largely Unknown
Only 15 stations have confirmed paid pricing and 151 are confirmed free. The remaining 158 stations have no pricing information, representing a significant data gap that limits consumer transparency.

### Station Growth Peaked in 2018
New station openings grew steadily from 2011 to a peak of 69 in 2018, then dropped sharply in 2019 and 2020, likely reflecting COVID-related slowdowns. Data for 2021 through 2024 is missing from the dataset.

---

## Technical Skills Demonstrated
- **SQL:** Aggregations, GROUP BY, HAVING, CASE statements, date functions, subqueries, CTEs, window functions (RANK, ROW_NUMBER)
- **Data Cleaning & Preparation:** Python (Pandas)
- **Database:** MySQL / MySQL Workbench

---

## Data Notes
Open Date data is incomplete for 2021 through 2024, limiting full trend analysis. Some station names appear more than once due to duplicate entries in the source data.
