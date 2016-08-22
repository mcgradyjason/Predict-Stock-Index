# Predict-Stock-Index
Analysis of relationship between Stock Index Price and Economic Variables in United States

#Software
Model was run on R studio

#Data
Most data were retrieved from FRED, Federal Reserve Bank of St. Louis

#Object
In the macroeconomic theory, there is a strong link between stock price and economic activities. The purpose of this research is to find the economic variables which can effect stock price efficiently. The variables that are selected in this research are seasonally adjusted gross domestic product in US from 2005 to 2014 (GDP), U.S. Dollar Index, the inflation represented by Consumer Price Index, the Federal funds rate in United States and risky free rate represented by 3-month T-Bill. And Dow Jones U.S. Total market index (2005-2014) is selected as the stock index. The research contains multiple linear regression model, and after test of the model, the data proves that there exist strong relationship between these four variables and stock index during the period of steady economic development, but the link is unapparent during the economic crisis.

#Model
Linear regression was applied.
Y=21910+3.037X_1-1286X_2-51230X_3-144X_4+0.5302X_5+1574X_6+ ε𝑋!+ 𝜀

Y: DJIA, X1 : GDP, X2 : FFR, X3 : CPI, X4 : USI, X5 : DJIA_LQ, X6 : 3MTB, 𝜀: Error terms

#Interpretation
GDP and Dow Jones Industrial Index is positively related, a unit increase in GDP of United State results in DJIA increasing about 3.037 units.
If Federal Fund Rate increase 1%, the DJIA will approximately drop 12.86 units. This means that if bank raise interest rate, more money will be deposit in the banking system rather than investing in stock market.
Consumer Price Index results in dropping 512.3 of DJIA when it increases 1%.
U.S. Dollar Index is negative related with DJIA, approximate 144 drop in DJIA if U.S. Dollar Index increase one unit.
DJIA from last quarter is a good indicator to DJIA of this quarter, about 0.5302 increasing in this quarter if the data from last quarter increased 1 unit.
1% increase in 3-Month Treasury Bill will lead to 15.74 increasing in DJIA.
