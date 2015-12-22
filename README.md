finarm
======

Financial Armageddon - displays financial quotes, and the value of your Bitcoin and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and the quotes you want to track and run it.  
An example of the output produced:

```
2015-12-22 22:01:10 - 911 B sent / 3344 B received
XAU/XAG=75.01  XBT/XAU=0.407  XPT/USD=872.8  XPD/USD=554.9  EUR/USD=1.096  USD/CNY=6.476
GBP/EUR=1.353  GBP/USD=1.483  USD/JPY=121.1  USD/SEK=8.429
GBTC=59.40  NYXBT=435.0  USDX=98.21  USTNO5Y=1.710  USTNO10Y=2.240  USTNO30Y=2.960
VIX=16.60  S&P1200=1'821  S&P500=2'039  NASDAQ=5'001  HSI=21'830  Nikkei225=18'887
ESTX50EUR=3'214  DAX=10'489  FTSE100=6'083  CAC40=4'568  MIB=21'060  ATHEX=180.4
AAPL=107.2  GOOG=750.0  MSFT=55.35  AMZN=663.2  FB=105.5  FCAU=13.70
Gold=1'074  Silver=14.30  Platinum=847.0  Palladium=558.6  Aluminum=1'595  Copper=2.100
Oil=39.39  Gas=2.195  Corn=381.0  Oats=267.2  Cattle=126.2  Hogs=55.48
Cotton=62.27  Coffee=118.4  Cocoa=3'328

SYM  PRICE  PRICE  PRICE    QTY    WGT  VALUE  VALUE  VALUE  VALUE  VALUE  VALUE
       USD    EUR    GBP             g      %    USD    EUR    GBP    XBT    XAU

XAU  1'073  979.2  723.6  1.997     62   69.1  2'142  1'955  1'445  4.900  1.997
XAG  14.30  13.05   9.65  36.37  1'131   16.8    520    475    351  1.189  0.484
XBT  437.1  399.0  294.8  1.000          14.1    437    399    295  1.000  0.407
GBP  1.483  1.353  1.000  1.000           0.0      1      1      1  0.003  0.001
                                 -----  -----  -----  -----  -----  -----  -----
                                 1'193  100.0  3'101  2'830  2'091  7.093  2.889
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  
The only accepted command-line argument is -q to print only the quotes and not the portfolio.

On a unix system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
