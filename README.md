# Fin-GAN-forecasting
Implementation of a simplified Fin-GAN framework for probabilistic financial forecasting, with comparisons to LSTM and ARIMA models.

This repository contains an implementation of a simplified **Fin-GAN** framework for probabilistic forecasting in financial markets, applied to updated stock and ETF return data (2010–2025).  
The project benchmarks Fin-GAN against **LSTM** and **ARIMA** models, with evaluation metrics including **RMSE**, **Sharpe Ratio**, and **Profit and Loss (PnL)**.

## Overview
- **Goal**: Evaluate adversarial, recurrent, and classical models for financial forecasting.  
- **Models**:  
  - Generative Adversarial Network (Fin-GAN, tuned & baseline)  
  - Long Short-Term Memory (LSTM, tuned & baseline)  
  - ARIMA(1,0,0)  
- **Data**: S&P 500 stocks and sector ETFs (2010–2025).  
- **Metrics**: RMSE, Sharpe Ratio, Profit and Loss.  

## Results
- Fine-tuned **GANs** achieved superior risk-adjusted returns in high-volatility sectors.  
- **LSTMs** outperformed in stable environments.  
- **ARIMA** underperformed across all metrics, reaffirming the need for nonlinear models.  

## Repository Structure

├── data/ # Preprocessed stock & ETF returns
├── notebooks/ # Jupyter notebooks for training and evaluation
├── src/ # Source code (GAN, LSTM, ARIMA implementations)
├── results/ # Plots, evaluation metrics, and comparison tables
└── README.md


## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fin-gan-forecasting.git
   cd fin-gan-forecasting
   
2. Install requirements
pip install -r requirements.txt


## Acknowledgements

This project builds upon the **Fin-GAN** framework introduced by Vuletić et al. (2024).  
I would like to thank the authors for their contributions to financial forecasting research.

- 📄 [Fin-GAN Paper (Quantitative Finance, 2024)](https://doi.org/10.1080/14697688.2023.2299466)  
- 💻 [Fin-GAN GitHub Repository](https://github.com/FranziskaPrenzel/Fin-GAN)
