# Stock Data Analysis & Visualization

## Overview
This repository contains comprehensive stock analysis notebooks for technical analysis and trading signal generation using Python.

## Projects Included

### 1. Apple Stock Analysis (`apple stock practice.ipynb`)
- Technical analysis of Apple Inc. (AAPL) stock
- Moving averages (20, 50, 200-day)
- RSI (Relative Strength Index) calculation and analysis
- MACD (Moving Average Convergence Divergence) indicators
- Trading signal generation

### 2. Siemens India Analysis (`siemens.ipynb`)
- Complete analysis of Siemens Limited India (SIEMENS.NS)
- Technical indicators implementation
- Trading signals visualization
- Performance comparison with Apple stock

### 3. Main Analysis (`main.ipynb`)
- Consolidated analysis notebook
- Cross-stock comparisons
- Portfolio analysis concepts

## Key Features
- **Technical Indicators**: RSI, MACD, Moving Averages
- **Trading Signals**: Buy/Sell signal generation based on technical analysis
- **Data Visualization**: Interactive charts and plots using matplotlib and seaborn
- **Real-time Data**: Uses yfinance for live stock data fetching
- **Performance Metrics**: Return calculations, volatility analysis

## Technologies Used
- Python 3.x
- pandas - Data manipulation and analysis
- yfinance - Stock data fetching
- matplotlib & seaborn - Data visualization
- numpy - Numerical computations
- mplfinance - Financial plotting

## Getting Started

### Prerequisites
```bash
pip install yfinance pandas matplotlib seaborn numpy mplfinance
```

### Usage
1. Clone this repository
2. Install required dependencies
3. Open any of the Jupyter notebooks
4. Run the cells to perform stock analysis

## Analysis Methodology

### Moving Averages
- **20-day MA**: Short-term trend analysis
- **50-day MA**: Medium-term trend analysis  
- **200-day MA**: Long-term trend analysis

### RSI (Relative Strength Index)
- Momentum oscillator (0-100 scale)
- Overbought: RSI > 70
- Oversold: RSI < 30
- Neutral: RSI 30-70

### MACD (Moving Average Convergence Divergence)
- Trend-following momentum indicator
- MACD Line: 12-day EMA - 26-day EMA
- Signal Line: 9-day EMA of MACD Line
- Histogram: MACD Line - Signal Line

### Trading Signals
- **Buy Signal**: RSI < 30 AND MACD > Signal Line
- **Sell Signal**: RSI > 70 AND MACD < Signal Line

## Sample Output
The notebooks generate various visualizations including:
- Stock price charts with moving averages
- RSI oscillator plots
- MACD indicator charts
- Trading signal overlays
- Performance comparison tables

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is open source and available under the MIT License.

## Disclaimer
This analysis is for educational purposes only. Not financial advice. Always do your own research before making investment decisions.
