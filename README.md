finarm
======

Financial Armageddon - displays financial quotes, and the value of your Bitcoin and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and the quotes you want to track and run it.  
An example of the output produced:

```
2016-02-01 21:04:30 - 1112 B sent / 4020 B received
XAU/XAG=78.76  XBT/XAU=0.328  XPT/USD=868.8  XPD/USD=501.6  EUR/USD=1.089  USD/CNY=6.582
GBP/EUR=1.326  GBP/USD=1.444  USD/JPY=121.0  USD/SEK=8.529
USDX=98.99  USTNO13W=0.300  USTNO5Y=1.380  USTNO10Y=1.970  USTNO30Y=2.780  GBTC=42.99
NYXBT=374.8  VIX=19.75  S&P1200=1'732  S&P500=1'939  NASDAQ=4'620  HSI=19'596
Nikkei225=17'865  ESTX50EUR=3'021  DAX=9'758  FTSE100=6'060  CAC40=4'392  MIB=18'486
ATHEX=155.0  AAPL=96.51  GOOG=751.0  MSFT=54.84  AMZN=573.4  FB=115.0
FCAU=7.030  Miners=47.37  SP-CI=292.9  S&PFut=1'934  GS-CI=301.0  Oil=31.49
Gas=2.142  Gold=1'130  Silver=14.36  Platinum=872.5  Palladium=505.0  Aluminum=1'640
Copper=2.060  Corn=371.0  Oats=196.8  Rice=11.02  SoyM=269.7  SoyO=30.80
Soy=878.8  L.Cattle=134.6  F.Cattle=158.2  Hogs=70.58  Cotton=61.79  Coffee=117.8
Cocoa=2'852  Lumber=241.3  OJ=134.0  Sugar=12.83

SYM  PRICE  PRICE  PRICE    QTY  WEIGHT  VALUE  VALUE  VALUE  VALUE  VALUE  VALUE
       USD    EUR    GBP              g      %    USD    EUR    GBP    XBT    XAU

XAU  1'129  1'036  781.6  1.997      62   68.5  2'253  2'069  1'561  6.091  1.997
XAG  14.33  13.16  9.924  36.37   1'131   15.8    521    478    361  1.407  0.462
XBT  369.9  339.7  256.2  1.000           11.2    370    340    256  1.000  0.328
GBP  1.444  1.326  1.000  100.0            4.4    144    133    100  0.390  0.130
                                  -----  -----  -----  -----  -----  -----  -----
                                  1'193  100.0  3'289  3'020  2'278  8.888  2.916
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.  
The only accepted command-line argument is -q to print only the quotes and not the portfolio.

On a unix system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
