finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and
the quotes you want to track and run it.  
The script produces some text with the quotes and the value of your portfolio.  
An example of the output produced:

```
2015-12-13 21:12:09 - sent 924 received 3392 from yahoo.co.uk
XAU/XAG=77.50  XBT/XAU=0.409  XPT/USD=843.5  XPD/USD=544.0  EUR/USD=1.099  USD/CNY=6.458
GBP/EUR=1.385  GBP/USD=1.522  USD/JPY=121.1  USD/SEK=8.506

GBTC=63.00  NYXBT=433.5  USDX=97.68  USTNO5Y=1.570  USTNO10Y=2.140  USTNO30Y=2.880
VIX=24.39  S&P1200=1'807  S&P500=2'012  NASDAQ=4'933  HSI=21'464  Nikkei225=19'230
ESTX50EUR=3'203  DAX=10'340  FTSE100=5'953  CAC40=4'550  MIB=21'015  ATHEX=170.0
Gold=1'076  Silver=13.89  Platinum=877.7  Palladium=542.3  Aluminum=1'595  Copper=2.096
Oil=39.39  Gas=2.195  Corn=373.0  Oats=267.0  Cattle=121.2  Hogs=56.00
Cotton=62.27  Coffee=118.1  Cocoa=3'350  AAPL=113.2  GOOG=738.9  MSFT=54.06
AMZN=640.2  FB=102.1  FCAU=13.60

SYM  PRICE  PRICE  PRICE    QTY    WGT  VALUE   VALUE   VALUE   VALUE  VALUE  VALUE
       USD    EUR    GBP             g      %     USD     EUR     GBP    XBT    XAU

XAU  1'074  977.1  705.5  10.20    317   49.1  10'954   9'965   7'195  24.92  10.20
XBT  439.5  399.8  288.6  18.00          35.5   7'911   7'196   5'196  18.00   7.37
XAG  13.86  12.61  9.102  133.6  4'156    8.3   1'852   1'684   1'216   4.21   1.72
EUR  1.099  1.000  0.722  1'450           7.1   1'594   1'450   1'047   3.62   1.45
                                 -----  -----  ------  ------  ------  -----  -----
                                 4'473  100.0  22'310  20'296  14'653  50.76  20.74
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  
The only accepted argument is -h to print only the quotes and not the portfolio.

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
