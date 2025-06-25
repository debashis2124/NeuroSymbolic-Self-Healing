# NeuroSymbolic-Self-Healing
NeuroSymbolic Self-Healing is an AI-driven framework that not only detects when a network node has been compromised—by fusing neural-network anomaly scores with rule-based checks—but also automatically remediates and restores it.

# NeuroSymbolic Risk Modeling & Self-Healing

This repository implements:
1. LSTM autoencoder for anomaly (risk) scoring  
2. Symbolic rule-based scoring  
3. Hybrid fusion + MLP classification  
4. Synthetic / adversarial / transfer-learning variants  
5. Epoch-wise training plots + final evaluation figures  
6. “Self-healing” recovery counts of compromised vs recovered samples  

## Repo layout

── data/
│ └── dod_contracts.csv
│ ├── allinone.py
├── results/
│ └── summary_results.csv
└── README.md
