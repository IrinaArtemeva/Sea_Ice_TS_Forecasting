# Arctic Sea Ice Forecasting with Recurrent Neural Networks

This repository contains Jupyter notebooks developed as part of the master's thesis:
**"Forecasting of the Sea Ice Situation Using Recurrent Neural Architectures"**  
Irina Artemeva, 2025, Master's program in Machine Learning Engineering.

## Project Overview

The goal of the project was to develop and compare predictive models for 7 days ahead forecasting of sea ice concentration across five Arctic seas using daily data from 2015–2023.

Models evaluated:
- SARIMA (baseline statistical model)
- LSTM
- IndRNN
- SegRNN (segmented recurrent neural network)

The SegRNN model demonstrated the most promising results in terms of accuracy, stability, and practical usability.

---

## Repository Structure
├── notebooks/ → main Jupyter notebooks with data processing and modeling
├── metrics/ → saved evaluation results, plots, and analysis tables
├── README.md → project overview and usage instructions

### Requirements
- Python 3.10+
- Recommended environment: Google Colab or Jupyter Lab
- Install packages (if running locally):

```bash
pip install numpy pandas matplotlib scikit-learn statsmodels torch