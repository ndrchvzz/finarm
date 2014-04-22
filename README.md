finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and run it.
The script produces some text with a breakdown of your portfolio. An example of the output produced:

```
2014-04-22 21:54:06 - Prices from: www.bitstamp.net query.yahooapis.com
XAU/XAG = 66.37  XBT/XAU = 0.38  EUR/USD = 1.38  GBP/EUR = 1.22  GBP/USD = 1.68

SYM     PRICE   PRICE   PRICE       QTY    WGT   VALUE      VALUE      VALUE     VALUE
          USD     EUR     GBP               KG       %        USD        EUR       GBP

XAG     19.35   14.02   11.50    385.81  12.00   49.31   7'465.79   5'408.03  4'437.32
XAU  1'284.35  930.35  763.36      3.22   0.10   27.27   4'129.28   2'991.15  2'454.25
EUR      1.38    1.00    0.82  1'500.00          13.68   2'070.75   1'500.00  1'230.76
XBT    491.52  356.04  292.14      3.00           9.74   1'474.56   1'068.13    876.41
                                         ‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒
                                         12.10  100.00  15'140.38  10'967.32  8'998.74
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.

If you are running it on a unix-like system you can have a window displaying the output refreshed every N seconds by running:
watch -n N finarm
(replace N with the required number of seconds between updates)
