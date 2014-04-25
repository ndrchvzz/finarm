finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and run it.
The script produces some text with a breakdown of your portfolio. An example of the output produced:

```
2014-04-25 22:17:37 - Prices from: www.bitstamp.net query.yahooapis.com
XAU/XAG = 66.21  XBT/XAU = 0.36  EUR/USD = 1.38  GBP/EUR = 1.21  GBP/USD = 1.68

SYM     PRICE   PRICE   PRICE       QTY    WGT     WGT   VALUE      VALUE      VALUE      VALUE
          USD     EUR     GBP               KG     OZT       %        USD        EUR        GBP

XAG     19.68   14.23   11.72    403.81  12.56  403.81   43.65   7'948.98   5'745.56   4'731.25
XAU  1'303.35  942.07  775.76      5.22   0.16    5.22   37.32   6'797.07   4'912.95   4'045.63
EUR      1.38    1.00    0.82  1'500.00                  11.39   2'075.25   1'500.00   1'235.19
XBT    463.72  335.18  276.01      3.00                   7.64   1'391.16   1'005.54     828.02
                                         ‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒  ‒‒‒‒‒‒‒‒‒
                                         12.72  409.02  100.00  18'212.46  13'164.05  10'840.10
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.

If you are running it on a unix-like system you can have a window displaying the output refreshed every N seconds by running:
watch -n N finarm
(replace N with the required number of seconds between updates)
