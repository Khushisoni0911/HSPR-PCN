# HSPR-PCN: Hybrid Secure Predictive Routing for Payment Channel Networks

A machine learning-based routing framework for blockchain Payment Channel Networks (PCNs) that improves transaction success rate using predictive routing, liquidity management, privacy cost modeling, and incentive-based node selection.

---

## Features
- ML-based routing decision system
- Privacy-aware path selection
- Incentive-driven node scoring
- Liquidity-aware routing
- Comparative routing evaluation
- Visualization of routing performance

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

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/HSPR-PCN.git
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib networkx scikit-learn xgboost
```

### 3. Open the notebook

```bash
jupyter notebook HSPR_PCN.ipynb
```


## Future Work
- Real-world Lightning Network simulation
- Reinforcement learning-based routing
- Blockchain-integrated deployment
- Advanced privacy-preserving routing

---

## Status
Research Paper — Manuscript in Preparation

---

## Author
Khushi Soni
