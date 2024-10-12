## Deep Learning for Stock Predictions (Academic Study) 
**Date**: April 2024 - September 2024  
**Link**: [View Project](https://github.com/ammaro101/final_project)  

### Objective  
Develop a deep learning model to predict U.S. stock prices using historical technical data. The project serves as a foundation for future stock prediction systems, with potential applications in commodities and broader markets.

### Methodology  
- **Data Collection**: Gathered stock data using yfinance API for S&P 500 stocks, focusing on weekly intervals.
- **Feature Engineering**: Generated 66 technical indicators using pandas-ta for price, volume, and volatility analysis.
- **Model Types**: Developed and optimized SimpleRNN, LSTM, and GRU models for time-series forecasting.
- **Hyperparameter Tuning**: Used keras_tuner for optimizing layers, dropout, batch sizes, and optimizers.

### Key Findings  
- **Best Model**: GRU with 55% accuracy on the XYL stock.
- **Challenges**: High volatility in model performance, especially with larger intervals like monthly data.
- **Computational Issues**: Limited by available hardware, causing slower training times.

### Results  
The final model provided a baseline for stock predictions with promising but varied results across different stocks and data intervals.

---

- [Home](index.md)
