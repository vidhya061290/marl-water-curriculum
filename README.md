# Multi-Phase Curriculum Learning for MARL in Water Resource Management

This repository accompanies the paper:
> **Vidhyalakshmi Amarnath**, *Robust Control of Water Distribution Networks under Drought Stress: A Multi-Agent Curriculum Learning Approach*, Water Resources Management, 40(5), 214 (2026).

---

## Intellectual Property & Patent Notice
Aspects of the methodology, algorithms, and system architectures implemented in this repository are the subject of a pending U.S. Provisional Patent Application (No. 63/944,327). 

This repository is shared strictly for academic evaluation and research reproduction. Commercial use, reproduction, or redistribution without a formal licensing agreement is prohibited.

---

## Overview
This repository provides the implementation of a Multi-Phase Curriculum Learning (MPCL) framework built on Multi-Agent Proximal Policy Optimization (MAPPO) to enhance resilience and operational stability in decentralized water distribution control systems.

## Repository Contents
- `marl_training.ipynb`: Main training and analysis notebook.
- `data/inflow_sample.csv`: Example precipitation dataset (publicly available).
- `data/preprocess_demand.py`: Illustrative preprocessing script for restricted demand data.
- `requirements.txt`: Python dependencies.
- `docs/`: Contains publication-ready figures and plots.

## Data Availability
- **Precipitation Data:** The inflow dataset is based on publicly available precipitation data. Download sources and citation links are provided in this repository.
- **Demand Data:** The municipal demand dataset used in this study is proprietary and cannot be publicly shared. However, this repository includes scripts demonstrating how the demand data were aggregated and anonymized to ensure methodological transparency.

## Reproducing Results
To reproduce experiments:
```bash
pip install -r requirements.txt
jupyter notebook marl_training_revised.ipynb

## Intellectual Property & Patent Notice
Aspects of the methodology, algorithms, and system architectures described in this repository and associated publication are subject to a pending U.S. Provisional Patent Application (No. 63/944,327). 

This source code is provided strictly for academic and non-commercial research evaluation. Commercial use, redistribution, or modification without a prior licensing agreement is strictly prohibited.



