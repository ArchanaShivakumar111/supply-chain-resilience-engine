# AI-Powered Supply Chain Resilience Engine

Predicts supply chain disruptions using four geopolitical risk pillars engineered from 172,765 shipment records.

## Key Results
- XGBoost Classifier: AUC 0.7558, CV AUC 0.7535 ± 0.001
- RF Regressor: MAE 0.96 days, 85% within ±2 days
- 185 hidden bottlenecks discovered at 90%+ delay rate
- Engineered pillars drive 80.1% of model predictions (SHAP)

## Four Pillars
1. Geopolitical Friction Index (GFI)
2. Temporal Risk Factor
3. Route Fragility Score
4. Hidden Bottleneck Detection

## Tech Stack
Python, XGBoost, scikit-learn, SHAP, pandas, ipywidgets
