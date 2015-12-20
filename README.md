finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and
the quotes you want to track and run it.  
The script produces some text with the quotes and the value of your portfolio.  
An example of the output produced:

```
2015-12-20 22:29:48 - sent 911 received 3343
XAU/XAG=75.71  XBT/XAU=0.413  XPT/USD=860.6  XPD/USD=558.3  EUR/USD=1.087  USD/CNY=6.483
GBP/EUR=1.371  GBP/USD=1.490  USD/JPY=121.3  USD/SEK=8.544
GBTC=62.00  NYXBT=460.0  USDX=98.75  USTNO5Y=1.680  USTNO10Y=2.200  USTNO30Y=2.910
VIX=20.70  S&P1200=1'804  S&P500=2'006  NASDAQ=4'923  HSI=21'756  Nikkei225=18'987
ESTX50EUR=3'261  DAX=10'608  FTSE100=6'052  CAC40=4'625  MIB=21'242  ATHEX=183.0
AAPL=106.0  GOOG=739.3  MSFT=54.13  AMZN=664.1  FB=104.0  FCAU=13.72
Gold=1'065  Silver=14.06  Platinum=847.0  Palladium=558.6  Aluminum=1'595  Copper=2.100
Oil=39.39  Gas=2.195  Corn=381.0  Oats=267.2  Cattle=120.2  Hogs=55.48
Cotton=62.27  Coffee=118.4  Cocoa=3'328

SYM  PRICE  PRICE  PRICE    QTY    WGT  VALUE  VALUE  VALUE  VALUE  VALUE  VALUE
       USD    EUR    GBP             g      %    USD    EUR    GBP    XBT    XAU

XAU  1'066  981.0  715.4  1.997     62   69.1  2'128  1'959  1'428  4.835  1.997
XAG  14.08  12.96  9.449  36.37  1'131   16.6    512    471    344  1.164  0.480
XBT  440.2  405.1  295.4  1.000          14.3    440    405    295  1.000  0.413
GBP  1.490  1.371  1.000  1.000           0.0      1      1      1  0.003  0.001
                                 -----  -----  -----  -----  -----  -----  -----
                                 1'193  100.0  3'082  2'836  2'069  7.002  2.891
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
