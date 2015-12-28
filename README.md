finarm
======

Financial Armageddon - displays financial quotes, and the value of your Bitcoin and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and the quotes you want to track and run it.  
An example of the output produced:

```
2015-12-28 20:31:20 - 920 B sent / 3393 B received
XAU/XAG=77.01  XBT/XAU=0.394  XPT/USD=880.0  XPD/USD=552.0  EUR/USD=1.097  USD/CNY=6.492
GBP/EUR=1.356  GBP/USD=1.488  USD/JPY=120.4  USD/SEK=8.368
USDX=97.94  USTNO13W=0.190  USTNO5Y=1.720  USTNO10Y=2.220  USTNO30Y=2.940  GBTC=60.50
NYXBT=425.4  VIX=17.12  S&P1200=1'843  S&P500=2'055  NASDAQ=5'033  HSI=21'920
Nikkei225=18'873  ESTX50EUR=3'256  DAX=10'654  FTSE100=6'255  CAC40=4'618  MIB=21'369
ATHEX=179.5  AAPL=106.8  GOOG=761.3  MSFT=55.89  AMZN=672.7  FB=105.4
FCAU=14.32  Gold=1'074  Silver=13.86  Platinum=880.5  Palladium=558.6  Aluminum=1'595
Copper=2.070  Oil=39.39  Gas=2.195  Corn=381.0  Oats=267.2  Cattle=130.1
Hogs=55.48  Cotton=62.27  Coffee=118.4  Cocoa=3'328

SYM  PRICE  PRICE  PRICE    QTY    WGT  VALUE  VALUE  VALUE  VALUE  VALUE  VALUE
       USD    EUR    GBP             g      %    USD    EUR    GBP    XBT    XAU

XAU  1'068  973.5  718.0  1.997     62   66.5  2'133  1'944  1'434  5.075  1.997
XAG  13.87  12.64  9.324  36.37  1'131   15.7    505    460    339  1.200  0.473
XBT  420.3  383.0  282.5  1.000          13.1    420    383    283  1.000  0.394
GBP  1.488  1.356  1.000  100.0           4.6    149    136    100  0.350  0.140
                                 -----  -----  -----  -----  -----  -----  -----
                                 1'193  100.0  3'207  2'922  2'155  7.625  3.003
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  
The only accepted command-line argument is -q to print only the quotes and not the portfolio.

On a unix system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
