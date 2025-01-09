# **Crypto RSI Signals Dataset**

This repository contains datasets of weekly close prices and RSI values for 10 cryptocurrencies used in the analysis of adjusted RSI thresholds (30/80) for identifying trading opportunities. The datasets were obtained from publicly available sources and formatted for consistent analysis.

## **Description**
The datasets include:
- **Date**: The end-of-week date corresponding to the recorded data.
- **Weekly Close Price**: The weekly closing price of the cryptocurrency in USD.
- **Weekly RSI**: The Relative Strength Index (RSI) values are calculated using a 14-week rolling window.

### **Cryptocurrencies Covered**
1. Bitcoin (BTC)
2. Ethereum (ETH)
3. Cardano (ADA)
4. Binance Coin (BNB)
5. Dogecoin (DOGE)
6. Solana (SOL)
7. Ripple (XRP)
8. Tron (TRX)
9. Avalanche (AVAX)
10. Lido Staked Ether (STETH)

### **Important Notes**
- **Missing RSI Values**: RSI values for the initial periods are missing in some files due to the 14-week rolling window required for calculation. These missing values are retained in the datasets to maintain data integrity.
- **Purpose**: These datasets were used to evaluate the profitability of trading strategies based on RSI thresholds of 30 (oversold) and 80 (overbought).
- **Format**: The data is stored in CSV format for ease of access and analysis.

## **Repository Contents**
- `/datasets/`: Folder containing individual CSV files for each cryptocurrency.
- `/examples/`: Examples of processed data or charts generated during the analysis.
- `README.md`: This file, describes the repository and its purpose.

## **How to Use**
1. Download the repository or clone it using:
   ```bash
   git clone https://github.com/crypto-rsi-signals-dataset.git
