finarm
======

Financial Armageddon - keeps track of the value of your currency and precious metal assets.

Simply edit the lines at the beginning of the script with the value of your assets and run it.
The script produces some text with a breakdown of your portfolio. An example of the output produced:

```
2014-05-17 22:50:05 - Prices from: www.bitstamp.net query.yahooapis.com
XAU/XAG = 67.012  XBT/XAU = 0.347  EUR/USD = 1.370  GBP/EUR = 1.228  GBP/USD = 1.682

SYM     PRICE   PRICE   PRICE        QTY     WGT  VALUE   VALUE   VALUE   VALUE
          USD     EUR     GBP                 KG      %     USD     EUR     GBP

XAG     19.29   14.09   11.47    403.809  12.560   43.2   7'790   5'688   4'633
XAU  1'292.80  943.93  768.79      5.215   0.162   37.4   6'742   4'923   4'009
EUR      1.37    1.00    0.81  1'500.000           11.4   2'054   1'500   1'222
XBT    448.31  327.33  266.60      3.200            8.0   1'435   1'047     853
                                          ‒‒‒‒‒‒  ‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒  ‒‒‒‒‒‒
                                          12.722  100.0  18'021  13'158  10'717
```

Various options to change the format of the output can be set by editing a few variables at the beginning of the script.

If you are running it on a unix-like system you can have a window displaying the output refreshed every 60 seconds by running:
```
watch -n 60 finarm
```
