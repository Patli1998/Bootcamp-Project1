# Bootcamp-Project1
Stock Market Analysis

Introduction

Stock Market Analysis is the project on performance analysis and visualization on a 10, 5, 3, and 1 year timeframe using data provided by Yahoo Finance. By looking at data from the stock market and its different industries, and compare the ETFs representing the indexes of the market. The list we chose is: 'SPY - S&P500 ETF', 'QQQ - NASDAQ-100 Index', 'VTI - Vanguard Total Stock Market Index Fund', 'XLK - Technology Select Sector SPDR Fund', 'XLY - Consumer Cyclical/Consumer Discretionary', 'XLP - Consumer Defensive/Consumer Staples', 'XLV - Healthcare', 'XLI - Industrials', 'XLF - Financials', 'VNQ - Real Estate', 'XLE - Energy', 'XLU - Utilities'. We use pandas to get ETF information from different resources, visualized different aspects of it, and finally looked at a few ways of analyzing the performance of each ETF, based on its previous performance history.

Purpose

The purpose of this project is to comparatively analyze the performance of each ETF during the time period, and get general insight on this data through visualization. The project encompasses the concept of Data Mining and Statistics. This project makes heavy use of Pandas and Data Visualization.

Process

Variables used are SPY, QQQ, VTI, XLK, XLY, XLP XLV, XLI, XLF, VNQ, XLE, XLU, we pulled this information into individual DataFrames. We dropped formatting that Yahooo provided, so that, we create standardized the data for further combination. Generate the Rate of Return for all stock ETF tickers we have using the Rate of Return formula. Made a DataFrame for the returns for 10,5,3,1 years for all Tickers. Then we Extracted the 10 Year Rate of Return and Plot it in a Bar Charts. Graphed the cumulative change line for all ETFs by different sectors since 2012/01/01.

Files used

Main.ipynb (main code)
Analysis.pdf (final anlysis)
Readme.md (read me)
Presentation.pdf (slides presentation)
ElevatorPitchPolished.pdf (hypothesis, original idea)
.gitignore (x)
