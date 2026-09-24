# FEP Propane Market Intelligence

Interactive propane-market dashboard for Flashpoint Energy Partners.

## Current source dates

- EIA stock week ending: September 18, 2026
- Daily price data through: September 23, 2026
- Dashboard update: September 24, 2026

## Data handling

The public site contains the observations needed to render its charts, but it does not contain the source Excel workbooks. Production and export figures are displayed as daily rates. Seven-day equivalents are calculated only when comparing flows with weekly inventory changes.

National, Midwest and Gulf Coast stocks use the actual workbook series. Total inventory and ready-for-sale propane remain separate measures. Historical level-versus-reported-build differences greater than 0.2 million barrels are retained and flagged in the dashboard rather than silently corrected.

## Inventory outlook

The peak and March-end outlook uses eight completed seasons from 2018–19 through 2025–26. The 2018–19, 2019–20 and 2023–24 El Niño winters receive twice the weight. The calculation is a historical-analog planning tool, not a deterministic forecast.

## Updating

Future releases should be rebuilt from the two source workbooks and checked as one synchronized snapshot. Cards, charts, narrative, dates and projections must be updated together.

