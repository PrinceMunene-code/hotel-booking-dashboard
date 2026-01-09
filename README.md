# Hotel Booking Performance & Cancellation Risk Dashboard

## Project Overview
This project presents an executive-level Tableau dashboard designed to analyze hotel booking performance and forward-looking cancellation risk. The dashboard focuses on separating realized revenue from revenue at risk due to cancellations, while highlighting seasonal cancellation behavior.

## Business Problem
Hotel revenue is highly sensitive to booking cancellations, which vary by season, customer type, and market segment. Without clear separation between earned revenue and revenue at risk, decision-makers may underestimate financial exposure and misinterpret short-term performance.

## Key Metrics
- **Realized Revenue**: Total revenue from non-canceled bookings.
- **Revenue at Risk**: Revenue associated with canceled bookings, representing potential loss.
- **Booking Cancellation Rate**: Percentage of bookings that were canceled.
- **Occupied Nights**: Total nights stayed from non-canceled bookings.

## Dashboard Design Decisions
- KPIs are intentionally **global** to preserve full-period context.
- Monthly selection is used as a **diagnostic tool**, not a KPI filter.
- Full-year revenue trends remain independent of month selection to avoid misleading interpretations.
- Seasonal cancellation analysis includes an annual benchmark for risk comparison.

## Tools Used
- Tableau Desktop / Tableau Public
- Calculated fields and date handling (Year–Month granularity)
- Dashboard actions and reference lines

## Live Dashboard
[View the interactive dashboard on Tableau Public](PASTE_LINK_HERE)
