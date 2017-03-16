## DataMining-StocksPrediction

# Resources

1) Stock Lists (http://www.set.or.th/set/commonslookup.do?language=en&country=US&prefix={prefix}) eg. NUMBER, A, B, ... Z

2) Stock Financial Highlight http://www.set.or.th/set/companyhighlight.do?symbol={stock-symbol}&ssoPageId=5&language=en&country=US

3) Stock Price (https://marketdata.set.or.th/mkt/stockquotation.do?symbol={stock-symbol}&ssoPageId=1&language=en&country=US)

# Point

1) 'EPS' increase every year

2) 'Net Profit Margin' increase every year

3) '% change' of EPS ==> Predict the next year EPS

4) 'Avg PE' with penalty to outlier (current year is the base)

# Calculation

1) Take the 'Avg PE' ==> Multiply it with 'Predicted EPS' to get the 'Real Price of that stock'
