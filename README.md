# HSPR-PCN: Hybrid Secure Predictive Routing for Payment Channel Networks

A machine learning-based secure routing framework for blockchain Payment Channel Networks (PCNs) that improves transaction success rate using predictive routing, liquidity-aware optimization, privacy-cost modeling, and incentive-driven node selection.

---

## Overview

Traditional routing approaches in blockchain-based Payment Channel Networks often suffer from:
- failed transactions
- liquidity imbalance
- inefficient path selection
- privacy leakage

HSPR-PCN introduces a hybrid predictive routing mechanism that uses machine learning and network analytics to intelligently select optimal routing paths while improving routing efficiency and preserving privacy.

---

## Key Features

- Machine learning-based routing decisions
- Privacy-aware path evaluation
- Liquidity-sensitive path optimization
- Incentive-based node scoring
- Comparative routing analysis
- Transaction success prediction
- Routing simulation framework

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- NetworkX
- Matplotlib

---

## Project Architecture

```text
Input Network Data
        ↓
Feature Extraction
        ↓
Path Scoring & Privacy Modeling
        ↓
Machine Learning Prediction
        ↓
Optimal Route Selection
        ↓
Routing Evaluation & Visualization
```

---

## Results

| Routing Strategy | Success Rate |
|---|---|
| ML Routing (HSPR-PCN) | **94.0%** |
| Shortest Path (Dijkstra) | 84.3% |
| Random Routing | 59.3% |

### Improvement
- ML-based routing achieved approximately **9.67% improvement** over traditional shortest-path routing.

---

## Output Visualization

![Routing Comparison](comparison.png)

---

## Files

```text
HSPR_PCN.ipynb              → Main implementation notebook
comparison.png              → Routing comparison graph
routing_demo_results.csv    → Routing simulation results
README.md                   → Project documentation
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/HSPR-PCN.git
```

2. Install dependencies

```bash
pip install pandas numpy scikit-learn xgboost networkx matplotlib
```

3. Open the notebook

```bash
jupyter notebook HSPR_PCN.ipynb
```

4. Run all notebook cells

---

## Applications

- Blockchain payment routing
- Lightning Network optimization
- Secure financial transaction systems
- Privacy-preserving network routing
- Intelligent decentralized finance systems

---

## Future Improvements

- Reinforcement learning-based routing
- Real-time Lightning Network integration
- Blockchain deployment testing
- Federated learning for decentralized routing
- Advanced privacy-preserving mechanisms

---

## Research Status

Research Manuscript in Preparation

---

## Author
Khushi Soni
