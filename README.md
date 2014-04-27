finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and run it.
The script produces some text with a breakdown of your portfolio. An example of the output produced:

```
2014-04-27 09:21:22 - Prices from: www.bitstamp.net query.yahooapis.com
XAU/XAG = 66.21  XBT/XAU = 0.35  EUR/USD = 1.38  GBP/EUR = 1.21  GBP/USD = 1.68

SYM     PRICE   PRICE   PRICE       QTY    WGT   VALUE      VALUE      VALUE      VALUE
          USD     EUR     GBP               KG       %        USD        EUR        GBP

XAG     19.68   14.23   11.72    403.81  12.56   43.70   7'948.98   5'745.97   4'730.97
XAU  1'303.40  942.17  775.74      5.22   0.16   37.37   6'797.33   4'913.49   4'045.55
EUR      1.38    1.00    0.82  1'500.00          11.41   2'075.10   1'500.00   1'235.03
XBT    456.43  329.93  271.65      3.00           7.53   1'369.29     989.80     814.96
                                         ‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒
                                         12.72  100.00  18'190.70  13'149.27  10'826.51
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
