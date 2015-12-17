finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and
the quotes you want to track and run it.  
The script produces some text with the quotes and the value of your portfolio.  
An example of the output produced:

```
2015-12-17 22:25:37 - sent 911 received 3342 from yahoo.co.uk
XAU/XAG=76.61  XBT/XAU=0.433  XPT/USD=844.5  XPD/USD=556.8  EUR/USD=1.083  USD/CNY=6.480
GBP/EUR=1.376  GBP/USD=1.490  USD/JPY=122.5  USD/SEK=8.562
GBTC=62.00  NYXBT=455.6  USDX=99.04  USTNO5Y=1.720  USTNO10Y=2.240  USTNO30Y=2.940
VIX=18.94  S&P1200=1'828  S&P500=2'042  NASDAQ=5'003  HSI=21'872  Nikkei225=19'354
ESTX50EUR=3'306  DAX=10'738  FTSE100=6'103  CAC40=4'678  MIB=21'523  ATHEX=182.0
AAPL=109.0  GOOG=749.4  MSFT=55.70  AMZN=670.6  FB=106.2  FCAU=13.81
Gold=1'052  Silver=13.70  Platinum=877.7  Palladium=558.6  Aluminum=1'595  Copper=2.034
Oil=39.39  Gas=2.195  Corn=381.0  Oats=267.2  Cattle=119.0  Hogs=55.48
Cotton=62.27  Coffee=117.8  Cocoa=3'328

SYM  PRICE  PRICE  PRICE    QTY    WGT  VALUE  VALUE  VALUE  VALUE  VALUE  VALUE
USD    EUR    GBP             g      %    USD    EUR    GBP    XBT    XAU

XAU  1'048  967.6  703.4  1.997     62   68.7  2'093  1'932  1'404  4.610  1.997
XAG  13.68  12.63  9.181  36.37  1'131   16.3    498    459    334  1.095  0.476
XBT  454.1  419.1  304.7  1.000          14.9    454    419    305  1.000  0.433
GBP  1.490  1.376  1.000  1.000           0.0      1      1      1  0.003  0.001
                                 -----  -----  -----  -----  -----  -----  -----
                                 1'193  100.0  3'046  2'812  2'044  6.708  2.908
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
