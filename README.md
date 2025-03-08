# Super-Stocks Profile Tool
Stock analysis tool based on the Jesse Stine's book "Insider Buys: Superstock". 

## Instructions
On the first tab "LIVE Stock Data" we are using the live stock connection with Refinitiv that Excel offers. To refresh the Data go to the Data Tab and click Refresh all. You can also add a new stock ticker to the bottom of the list at anytime and it should auto populate technicals data.
The "Imported Stock Data" tab is data imported from StockAnalysis.com to also get new fundamentals each quarter (after earnings season). Create a watchlist on StockAnalysis.com with the same stock symbols, and match up the fundamentals metrics from the Imported Stock Data sheet in the same column order, which are; (Symbol/ 200 DMA/ Float/ Shares Insiders/ Shares Institution/ Short%/ PS Ratio/ PE Ratio/ PEG Ratio/ OPerating Margin/ Profit Margin/ FCF/ Total Debt/ Debt to Equity/ Rev Growth Q/ Rev Growth YOY/ Rev Growth 3Y/ Rev Growth 5Y/ EPS/ EPS Growth/ EPS Growth 3Y/ EPS Growth 5Y/ Options/ Analyst Count/ IPO Date).

Download to .CSV. Copy and paste the data onto cell A5, in the "Imported Stock Data" Tab and run the Stock_Analysis_Import_Foramt Macro. And the new data will be automatically formatted into the table.
Next go to the "Is it a Super Stock" Tab and enter any of your stock symbols from the Stock Data tabs into cell C2. And you should be able to get a good idea if the stock is a Super Stock or not.
I've used a combination of XLOOKUP functions, IF statements, and Conditional Formatting to highlight or flag the stock metrics that do and don't adhere to the principles outlined in Jesse Stine's book Superstocks. As a side note this is an approximation of the prinicples as he doesn't give hard numbers for all metrics, for example Debt/Equity ratio there is no mention of 0.3, and this can vary widely by industry, but this is a pretty average benchmark. 
## Disclaimer 
This tool is for informational and educational purposes only and does not constitute financial or investment advice. I am not a financial advisor. I own shares in some the stocks included in this project, which may influence the data presented. Use at your own risk and conduct your own research before making any invesmtent decisions.
Enjoy!

![Screenshot of Stock Profile Tool](screenshot.png)
