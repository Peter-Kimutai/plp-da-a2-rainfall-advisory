# plp-da-a2-rainfall-advisory

Rainfall analysis for a farmer-support NGO across five Kenyan counties. The notebook cleans a hand-typed Machakos record, builds a 5 × 12 NumPy array, and derives annual totals, wettest months, dry-month counts and planting windows.

## How to run
1. `pip install -r requirements.txt`
2. Open `rainfall_analysis.ipynb` and run all cells top to bottom (outputs are already committed).

## Planting advisory
- **Nairobi, Nakuru, Kisumu and Mombasa peak in April–May**, so one coordinated April SMS works for four counties.
- **Kisumu is the safest early-planting county** (~420 mm, zero dry months); Mombasa is close (~390 mm) but has two dry months to monitor.
- **Machakos should plant in November–December** (~278 mm); its mid-year is dry, so an April advisory there would mislead.
