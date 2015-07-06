finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and
the quotes you want to track and run it.  
The script produces some text with the quotes and the value of your portfolio.  
An example of the output produced:

```
2015-07-06 23:33:25 - Prices from: query.yahooapis.com
XAU/XAG:74.42  XBT/XAU:0.233  XPT/USD:1'066  XPD/USD:675.2  EUR/USD:1.105
USD/CNY:6.207  GBP/EUR:1.411  GBP/USD:1.560  USD/JPY:122.0  USD/SEK:8.460
XAU/Oil:19.77  GBTC:30.50  USDX:96.25  USTNO5Y:1.550  USTNO10Y:2.280
USTNO30Y:3.070  VIX:17.01  S&P1200:1'914  S&P500:2'069  NASDAQ:4'992
HSI:25'236  Nikkei225:20'112  ESTX50EUR:3'365  DAX:10'891  FTSE100:6'536
CAC40:4'712  MIB:21'601  ATHEX:241.2  Oil:59.20  Copper:2.540
Gas:2.810  AAPL:126.0  GOOG:522.9  MSFT:44.39  AMZN:436.0
FB:87.55

SYM  PRICE  PRICE  PRICE    QTY    WGT  VALUE   VALUE   VALUE   VALUE
       USD    EUR    GBP             G      %     USD     EUR     GBP

XAU  1'170  1'059  750.1  13.22    411   77.9  15'466  13'992   9'913
XBT  272.9  246.9  174.9  10.00          13.7   2'729   2'469   1'749
USD  1.000  0.905  0.641  1'000           5.0   1'000     905     641
XAG  15.73  14.23  10.08  42.15  1'311    3.3     663     600     425
                                 -----  -----  ------  ------  ------
                                 1'722  100.0  19'859  17'965  12'728
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  
The only accepted argument is -h to print only the quotes and not the portfolio.

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
