finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and
the quotes you want to track and run it.
The script produces some text with the quotes and the value of your portfolio.
An example of the output produced:

```
2015-06-10 08:42:27 - Prices from: query.yahooapis.com
XAU/XAG:74.29  XBT/XAU:0.193  XPT/USD:1'108  XPD/USD:739.4  EUR/USD:1.136
GBP/EUR:1.360  GBP/USD:1.545  USD/JPY:122.0  USD/SEK:8.217  GBTC:29.00
USDX:94.44  USTNO5Y:1.740  USTNO10Y:2.420  USTNO30Y:3.150  VIX:14.47
S&P1200:1'942  S&P500:2'080  NASDAQ:5'014  HSI:26'637  Nikkei225:20'046
ESTX50EUR:3'457  DAX:11'017  FTSE100:6'755  CAC40:4'849  MIB:22'615
ATHEX:230.5  Oil:61.06  Copper:2.730  Gas:2.810  AAPL:127.4
GOOG:526.7  MSFT:45.65  AMZN:425.5  FB:80.67

SYM  PRICE  PRICE  PRICE    QTY     WGT  VALUE   VALUE   VALUE  VALUE
       USD    EUR    GBP              G      %     USD     EUR    GBP

XAG  15.95  14.04  10.32  403.8  12'560   42.8   6'440   5'670  4'169
XAU  1'185  1'043  767.1  5.215     162   41.0   6'179   5'441  4'000
EUR  1.136  1.000  0.735  1'500           11.3   1'704   1'500  1'103
XBT  229.2  201.8  148.4  3.200            4.9     734     646    475
                                 ‒‒‒‒‒‒  ‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒
                                 12'722  100.0  15'057  13'257  9'748

```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
