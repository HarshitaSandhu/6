# CAPM Web Application using Streamlit
The Capital Asset Pricing Model (CAPM) is a financial model that helps investors and analysts understand the expected return on an investment based on its systematic risk. It provides a framework for calculating the appropriate required return on an investment given its risk profile. The CAPM formula is as follows:

Expected Return = Risk-Free Rate + Beta * (Market Return - Risk-Free Rate)

The web application integrates these libraries to gather stock data from Yahoo Finance, a popular financial data provider. It retrieves historical price data and other relevant information for the specified stocks.

Using the gathered data, the application performs CAPM calculations for each stock. It calculates the expected return by applying the CAPM formula, utilizing the risk-free rate, beta, and market return.

Finally, the application presents the calculated expected returns to the user in an interactive and visually appealing manner using Plotly charts. Users can input different stocks and obtain their respective expected returns, helping them make informed investment decisions.
