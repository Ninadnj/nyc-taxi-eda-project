# Executive Summary

## Project Overview

This analysis explores a dataset of NYC yellow taxi trips to identify patterns in ride behavior, fare and tip amounts, seasonal trends, and location-based activity. The insights aim to help the NYC Taxi and Limousine Commission (TLC) make data-driven operational decisions.

---

## Key Findings

- 🛣️ The majority of rides are short (under 5 miles) with an average duration of 17 minutes.
- 💳 Credit card users tip more frequently and generously than cash users.
- 🗓️ The busiest months are March, April, May, and October — ideal for peak resource planning.
- 📍 A small group of drop-off locations generate a disproportionately high share of revenue.
- 🚫 Invalid trips (e.g., 0 distance or 0 passengers) were excluded to ensure clean analysis.

---

## Recommendations

- Allocate more drivers around high-revenue drop-off zones like airports and tourist areas.
- Promote digital payments to increase tipping and streamline transactions.
- Prepare for seasonal spikes in the spring and fall months.
- Consider separate analysis of canceled or zero-distance trips for operational improvement.

---

## Deliverables

- A cleaned dataset of ~22,000 valid trips
- Visualizations in Python (notebook.ipynb)
- A Tableau-ready export (`cleaned_taxi_data.csv`)
