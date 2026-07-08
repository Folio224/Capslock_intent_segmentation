# Visitor Intent Segmentation — CapsLock

Home task for CapsLock: an XGBoost propensity model that segments landing-page visitors into intent tiers from behavioral session data. Also includes A/B variant analysis and lead-quality analysis.

## Files
- `MainNotebook.ipynb` — full pipeline: EDA → leakage handling → model → tiers → A/B → lead quality
- `Steps.txt` — detailed process notes (Development notes)
- `intent_propensity_xgb.json` — trained model artifact
- `lp_sessions.csv` — provided dataset (synthetic)
