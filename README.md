# My journey with freeBSD

## Setting the keyboard 

The standard keyboard layout, br-abnt2, for my Thinkpad T400 doens't
detect the key "/" properly in pure terminals tty. Thus I need to
correct the file responsible for mapping such keys.

The proper keyboard layout to be loaded on a tty
```
conf.d/br275.thinkpad.kbd
```


