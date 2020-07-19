# python-rsi

RSI (Relative Strength Index) written in Python

![Python RSI Image](https://github.com/mtamer/python-rsi/blob/master/src/images/example.png)

## About

Relative Strength Index written in Python. The whole point of this application is to be able to come up with a list of as many different types of stocks (stock tickers) that you want to screen and see if it meets the Relative Strength criteria. A combination of the RSI and the 20 and 200 day Moving Average (MA) tend to be strong and popular indicators to determine the future behavior of a stock.

At the end of pulling stock data, a table is shown displaying metrics of the stocks pulled along with a link to view the chart.

![Stock Data Table](https://github.com/mtamer/python-rsi/blob/master/src/images/pulled-data-table.png)

## To Install

1. Clone repo: `git clone https://github.com/mtamer/python-rsi.git`
2. `cd src`
3. `pip install -r requirements.txt`
4. Look inside the `main.py` file and put all the stocks you want to monitor in there or inside of `stocks.txt`
5. To run: `python main.py`
6. Enjoy!

## Disclaimer

This repository is only for educational purposes. The owner and contributors of this repository are not responsible for how you use this code and the gains/losses you accumulate.
