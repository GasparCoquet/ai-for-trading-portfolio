# Breakout Trading Strategy

## Overview

This project implements a breakout trading strategy inspired by the **Udacity AI for Trading Nanodegree**. It focuses on identifying price breakout opportunities using historical stock price data. By analyzing price highs and lows, this strategy generates actionable trading signals, filters redundant signals, and evaluates performance using statistical metrics.

## Project Structure
```
Project_2/
├── eod-quotemedia.csv           # Stock price dataset
├── helper.py                    # Fonctions utilitaires
├── terbium_mining_companies.csv # Dataset for synthetic TB sector stocks
├── project_2_starter.ipynb      # Notebook Jupyter principal
├── project_helper.py            # Fonctions auxiliaires pour l'analyse
├── project_tests.py             # Tests unitaires pour valider le code
├── README.md                    # Documentation pour ce projet
├── requirements.txt             # Liste des packages nécessaires
└── tests.py                     # Suite de tests pour les fonctionnalités
```

## Key Features

- **High-Low Signal Analysis**: 
  - Calculate price highs and lows over a specified lookback window.
- **Trading Signal Generation**: 
  - Generate long and short signals based on price breakout criteria.
- **Signal Filtering**: 
  - Remove redundant signals within a defined lookahead window.
- **Statistical Testing**: 
  - Use Kolmogorov-Smirnov Test to identify outliers in signal returns.
- **Synthetic Stock Generation**: 
  - Create synthetic data for a new TB mining sector to enhance analysis.

## Execution

1. **Clone the repository**:
   git clone https://github.com/GasparCoquet/ai-for-trading-portfolio.git
   cd ai-for-trading-portfolio/Project_2

2. **Install dependencies**:
   pip install -r requirements.txt

3. **Run the notebook**: Open project_2_starter.ipynb in Jupyter Notebook or JupyterLab and follow the instructions to execute the code step-by-step.

## Results
This project demonstrates the application of a breakout trading strategy. It provides tools for signal generation, filtering, and statistical evaluation, offering insights into the profitability and robustness of the strategy.

## License
This project is released under the MIT License. See the LICENSE file for more details.

## Acknowledgments
This project is inspired by the **Udacity AI for Trading Nanodegree**.