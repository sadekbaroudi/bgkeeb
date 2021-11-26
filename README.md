# Pronunciation

Baby Groot Keyboard (bgkeeb)

This is a reversible 100mm x 100mm pcb with support for mx switches (no hotswap), per key led, rotary encoders, and exposes the SDA/SCL/GND/VCC lines in the form of the pimoroni trackball pins (meaning you can add that as well, though the case doesn't support it, so you'll need to devise your own mechanism).

Given the pcb is so small, pcb prototype manufacturers will fab this for very cheap, or even free. As of this writing, nextpcb will ship fab and ship this keyboard 100% for free (in green only). jlcpcb will fab and ship these for $2 (USD).

# Support me!

I have spent a lot of time and money designing prototypes, testing, developing, etc. Any contributions would be greatly appreciated!

If you don't want to, or can't afford to support me, please send me a message to let me know you've built one, along with pictures. Also, feel free to submit a pull request with pictures into this repository. I'd be happy to showcase your build.

Reddit: /u/sadekbaroudi
Discord: sadekbaroudi#1258

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?business=N8D4SUZED96F6&no_recurring=0&item_name=Fund+my+open+source+keyboard+designs%21&currency_code=USD)

# Firmware

Link below. Remember that the left and right half use different firmware due to the fact that the diode direction is flipped between the halves. I created two configs, one for the left, and one for the right. If you copy the config.left.h/config.right.h to config.h before building, it will generate the appropriate firmware for that half.

I made a script to make this simpler if you run your builds in linux:
https://github.com/sadekbaroudi/qmk_firmware/blob/master/bin/build-bgkeeb-default.sh

The general folder for the firmware is here:
https://github.com/sadekbaroudi/qmk_firmware/tree/master/keyboards/xoiviox/bgkeeb/

# Pictures

![build](images/build.jpg)

![pcbs](images/pcbs.jpg)
