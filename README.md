# HSPR-PCN: Hybrid Secure Predictive Routing for Payment Channel Networks

A machine learning-based routing framework for blockchain Payment Channel Networks (PCNs) that improves transaction success rate using predictive routing, liquidity management, privacy cost modeling, and incentive-based node selection.

---

## Results

| Routing Strategy | Success Rate |
|---|---|
| ML Routing (HSPR-PCN) | **94.0%** |
| Shortest Path (Dijkstra) | 84.3% |
| Random Routing | 59.3% |

**ML Improvement over baseline: 9.67%**

---

## Tech Stack
Python · NetworkX · Scikit-learn · XGBoost · Pandas · Matplotlib

---

## Files
- `HSPR_PCN.ipynb` — Main implementation notebook
- `final_rf_model.pkl` — Trained Random Forest model
- `routing_demo_results.csv` — Output results
- `comparison.png` — Success rate comparison graph

## Status
Research paper — Manuscript in Preparation
