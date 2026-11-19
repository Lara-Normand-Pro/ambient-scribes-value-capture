# Who Captures the Value of AI Medical Scribes? Data and calculations

Companion repository to the individual report *Who Captures the Value of AI Medical Scribes? Generative AI, Clinical Documentation and Platform Strategy in Primary Care, 2024–2026* (Lara Normand, E-Business & Digital Disruption, ESSEC Business School, 2026).

## What it contains

| File | Content |
|---|---|
| `report_figures.ipynb` | Reproduces every value marked “author’s calculation” in the report and Figure 2, then checks each result against the value written in the report |
| `report_data.csv` | All inputs, one per row: *data* (with its APA reference, as in the report), *assumption* or *scenario* |
| `fig2_scenarios.png` | Figure 2 as produced by the notebook |

## Calculations reproduced

- **Section 4.3.** Monthly documentation time released; break-even of the €64–79 standalone subscription; gross receipts from extra visits.
- **Section 5.1.** Patient accounts per paying professional.
- **Section 5.3.** Theoretical GP time released in France if half of GPs used a scribe (101,000 × 50% × 16/480).
- **Figure 2.** Reported ARR (2024, 2025) and illustrative subscription receipts for the scribe and the patient side (scenarios, not forecasts; gross receipts not comparable with ARR).

## How to run

Python 3 with `pandas` and `matplotlib`. Open the notebook and run all cells, or view it directly on GitHub.

## Sources and limits

Every data row cites the source used in the report. Time savings come from American academic centres (Rotenstein et al., 2026) and have not been validated in French general practice. Hourly value, consultation fee and working days are illustrative assumptions. Adoption and conversion shares are scenarios applied to historical platform-wide user counts.
