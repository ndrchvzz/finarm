finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and
the quotes you want to track and run it.
The script produces some text with the quotes and the value of your portfolio.
An example of the output produced:

```
2015-06-28 00:01:41 - Prices from: query.yahooapis.com
XAU/XAG:74.66  XBT/XAU:0.214  XPT/USD:1'081  XPD/USD:678.0  EUR/USD:1.117
GBP/EUR:1.410  GBP/USD:1.575  USD/JPY:123.5  USD/SEK:8.299  XAU/Oil:19.84
GBTC:29.00  USDX:95.40  USTNO5Y:1.750  USTNO10Y:2.480  USTNO30Y:3.250
VIX:14.02  S&P1200:1'970  S&P500:2'101  NASDAQ:5'081  HSI:26'664
Nikkei225:20'706  ESTX50EUR:3'621  DAX:11'492  FTSE100:6'754  CAC40:5'059
MIB:23'800  ATHEX:241.2  Oil:59.20  Copper:2.650  Gas:2.810
AAPL:126.8  GOOG:531.7  MSFT:45.26  AMZN:438.1  FB:88.01

SYM  PRICE  PRICE  PRICE    QTY     WGT  VALUE   VALUE   VALUE  VALUE
       USD    EUR    GBP              G      %     USD     EUR    GBP

XAG  15.74  14.09  9.992  403.8  12'560   42.5   6'354   5'689  4'035
XAU  1'175  1'052  746.0  5.215     162   40.9   6'127   5'486  3'891
EUR  1.117  1.000  0.709  1'500           11.2   1'675   1'500  1'064
XBT  251.8  225.5  159.9  3.200            5.4     806     721    512
                                 ‒‒‒‒‒‒  ‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒
                                 12'722  100.0  14'962  13'397  9'501
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
