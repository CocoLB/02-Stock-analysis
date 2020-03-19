# 02-Stock-analysis

### Course
To understand how to fully analyse a worksheet of stocks, we started by doing an analysis on a single stock (DQ) in 2018, finding total volume and Return thanks to a macro.

<img src="01 DQ Analysis.png" width="250">

While using an array, we did the same analysis for the 12 stocks in the sheet in 2018. Depending on output, we added color to help visualizing then outputs of each stock.

<img src="02 All Stocks 2018 no button.png" width="250">

Then, we started our macro by asking the year so that will work with both 2017 and 2018 (or any other year).

<img src="03 year.png" width="250">

Then we added buttons to first clear the worksheet, then launch the macro.

<img src="02 All Stocks 2018.png" width="250">
<img src="04 All Stocks 2017.png" width="250">

### Challenge

We updated our Macro AllStockAnalysis so it could work with any number of stocks/tickers by using several dynamic arrays. 
After setting up and initialzing all arrays, I refactored the precedent code so all arrays can be found out at the same time for each ticker in the same loop. Now this macro can work for any number of stocks/year.
