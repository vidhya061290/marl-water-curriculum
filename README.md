# Multi-Phase Curriculum Learning for MARL in Water Resource Management

This repository accompanies the paper:
> Vidhyalakshmi Amarnath, *A Multi-Phase Curriculum Learning Framework for Resilient Multi-Agent Reinforcement Learning in Water Resource Management* (submitted to *Environmental Modelling & Software*, 2025).

## Overview
This project introduces a Multi-Phase Curriculum Learning framework for Multi-Agent Proximal Policy Optimization (MAPPO), enhancing resilience and stability in decentralized water control systems.

## Repository Contents
- `MAPPO.ipynb`: Main training and analysis notebook.
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
jupyter notebook MAPPO.ipynb
