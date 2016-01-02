finarm
======

Financial Armageddon - displays financial quotes, and the value of your Bitcoin and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and the quotes you want to track and run it.  
An example of the output produced:

```
2016-01-02 14:26:47 - 1048 B sent / 3960 B received
XAU/XAG=77.01  XBT/XAU=0.409  XPT/USD=891.7  XPD/USD=560.8  EUR/USD=1.086  USD/CNY=6.512
GBP/EUR=1.360  GBP/USD=1.478  USD/JPY=120.6  USD/SEK=8.460
USDX=98.68  USTNO13W=0.150  USTNO5Y=1.760  USTNO10Y=2.270  USTNO30Y=3.010  GBTC=63.00
NYXBT=431.4  VIX=18.21  S&P1200=1'835  S&P500=2'044  NASDAQ=5'007  HSI=21'914
Nikkei225=19'034  ESTX50EUR=3'268  DAX=10'743  FTSE100=6'242  CAC40=4'637  MIB=21'418
ATHEX=183.3  AAPL=105.3  GOOG=758.9  MSFT=55.48  AMZN=675.9  FB=104.7
FCAU=13.99  Miners=45.30  SP-CI=311.7  GS-CI=317.2  Oil=37.07  Gas=2.350
Gold=1'060  Silver=13.80  Platinum=890.7  Palladium=549.7  Aluminum=1'642  Copper=2.129
Corn=358.2  Oats=217.0  Rice=11.84  SoyM=265.7  SoyO=30.79  Soy=864.2
L.Cattle=136.2  F.Cattle=163.3  Hogs=59.88  Cotton=63.28  Coffee=126.7  Cocoa=3'211
Lumber=257.9  OJ=145.0  Sugar=15.24

SYM  PRICE  PRICE  PRICE    QTY  WEIGHT  VALUE  VALUE  VALUE  VALUE  VALUE  VALUE
       USD    EUR    GBP              g      %    USD    EUR    GBP    XBT    XAU

XAU  1'061  976.8  718.0  1.997      62   66.2  2'118  1'950  1'434  4.884  1.997
XAG  13.78  12.68  9.323  36.37   1'131   15.7    501    461    339  1.156  0.473
XBT  433.6  399.3  293.5  1.000           13.5    434    399    293  1.000  0.409
GBP  1.478  1.360  1.000  100.0            4.6    148    136    100  0.340  0.140
                                  -----  -----  -----  -----  -----  -----  -----
                                  1'193  100.0  3'200  2'947  2'166  7.381  3.018
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  
The only accepted command-line argument is -q to print only the quotes and not the portfolio.

On a unix system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
