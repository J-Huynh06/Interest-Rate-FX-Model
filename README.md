> **Key Features:**
1. **Data collection and processing:** Live macroeconomic data is fetched using yfinance and FRED's API. Pandas was used to clean data and to calculate new metrics
2. **Regression Analysis:** Uses OLS to determine if our chosen macroeconomic data has a statistically significant impact on FX returns for trading and to calculate the sensitivity of FX returns after changes to interest rate spreads
3. **Logistic Regression:** Logistic regression used to predict market direction based on historical data
4. **Strategy Backtesting:** Simulates the model's trade performance against a standard Buy & Hold strategy and compares percentage returns
5. **Excel P&L Calculator:** Excel sheet generated using Python for quick estimated P&L calculation by adjusting BoE or Fed Reserve interest rates, trade direction and size

> **Required Python Packages:**
- requests
- pandas
- yfinance
- numpy
- scikit-learn
- matplotlib
- statsmodels
- openpyxl
