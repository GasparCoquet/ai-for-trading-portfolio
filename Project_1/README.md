# Momentum-Based Trading Strategy

## Overview

This project implements a momentum-based trading strategy inspired by the **Udacity AI for Trading Nanodegree**. The project focuses on using quantitative finance techniques to develop a trading signal based on stock momentum, compute returns, and assess the potential profitability of the strategy.

## Project Structure
```
Project_1/
├── eod-quotemedia.csv          # Dataset contenant des données boursières
├── helper.py                   # Fonctions utilitaires
├── project_1_starter.ipynb     # Notebook Jupyter principal
├── project_helper.py           # Fonctions auxiliaires pour l'analyse
├── project_tests.py            # Tests unitaires pour valider le code
├── README.md                   # Documentation pour ce projet
├── requirements.txt            # Liste des packages nécessaires
└── tests.py                    # Suite de tests pour les fonctionnalités
```

## Key Features

- **Resampling Prices**: Adjust daily prices into monthly prices for long-term trading signals.
- **Log Returns**: Compute log returns to identify stock momentum.
- **Signal Shifting**: Shift returns to calculate future or past signals.
- **Top Stock Selection**: Identify top-performing stocks for each month.
- **Portfolio Returns**: Calculate expected portfolio returns based on long/short signals.

## Execution

1. **Clone the repository**:
   git clone https://github.com/GasparCoquet/ai-for-trading-portfolio.git
   cd ai-for-trading-portfolio/Project_1

2. **Install dependencies**:
   pip install -r requirements.txt

3. **Run the notebook**: Open project_1_starter.ipynb in Jupyter Notebook or JupyterLab and follow the instructions to execute the code step-by-step.

## Results
This project computes momentum signals, selects the top-performing stocks, and calculates portfolio returns based on equal-weighted investments. The results demonstrate the application of quantitative trading strategies in a practical environment.

## License
This project is released under the MIT License. See the LICENSE file for more details.

## Acknowledgments
This project is inspired by the **Udacity AI for Trading Nanodegree**.
