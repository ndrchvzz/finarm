finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and run it.
The script produces some text with a breakdown of your portfolio. An example of the output produced:

```
2014-05-23 22:26:59 - Prices from: winkdex.com query.yahooapis.com
XAU/XAG = 66.69  XBT/XAU = 0.41  EUR/USD = 1.36  GBP/EUR = 1.23  GBP/USD = 1.68

SYM    PRICE  PRICE  PRICE        QTY     WGT  VALUE   VALUE   VALUE   VALUE
         USD    EUR    GBP                 KG      %     USD     EUR     GBP

XAG     19.4   14.2   11.5    403.809  12.560   42.8   7'829   5'744   4'651
XAU  1'292.9  948.6  768.1      5.215   0.162   36.8   6'743   4'947   4'006
EUR      1.4    1.0    0.8  1'500.000           11.2   2'044   1'500   1'215
XBT    527.5  387.0  313.4      3.200            9.2   1'688   1'238   1'003
                                       ‒‒‒‒‒‒  ‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒
                                       12.722  100.0  18'304  13'429  10'875
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
