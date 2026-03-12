# Multi-Phase Curriculum Learning for MARL in Water Resource Management

This repository accompanies the paper:
> Vidhyalakshmi Amarnath, Robust Control of Water Distribution Networks under Drought Stress: A Multi-Agent Curriculum Learning Approach *(under review at Water Resources Management)*.

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

The notebook contains the full training pipeline, evaluation scripts, and figure generation used in the manuscript.



