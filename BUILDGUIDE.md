# Parts

Note that all the links below are from major reputable elecronics sites. You can do this for much cheaper if you search for these same parts on aliexpress.com

For this pcb, here are the components you will need:

| Component   | Quantity    | Link |
| ----------- | ----------- | ------------ |
| MCU (Pro Micro compatible, Elite-c compatible, or nice!nano compatible     | 2       | Google it, they're everywhere |
| SMD Diodes 0805   | 42       | https://www.lcsc.com/product-detail/Switching-Diode_TWGMC-1N4148W_C727110.html |
| SMD 10k resistor (optional)   | 2       | https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0805W8F1002T5E_C17414.html |
| M2 10mm standoffs | 8 | https://keeb.io/products/m2-screws-and-standoffs?variant=47432051590 |
| M2 4-5mm screws | 16 | https://www.amazon.com/uxcell-0-4mm-Stainless-Socket-DIN912/dp/B01M5DVE9R |
| Reset switch | 2 | https://www.digikey.com/en/products/detail/c&k/PTS526%2520SM15%2520SMTR2%2520LFS/10056633 |
| TRRS jack | 2 | https://keeb.io/collections/diy-parts/products/trrs-jack-3-5mm |
| SK6812 mini-e LED (optional)   | 36       | https://www.adafruit.com/product/4960 |
| EC11 Rotary encoder (optional)   | 2       | https://www.adafruit.com/product/377 |
| Pimoroni trackball (optional) | 1 | https://shop.pimoroni.com/products/trackball-breakout |

# Case

You will need to have the case before you solder, since the switches are soldered to the pcb.

https://github.com/sadekbaroudi/bgkeeb/tree/master/cases/case

Print the left case and bottom plate. You can use your slicing software to do horizontal mirroring to print the right case and plate.

# Building

Building these is very straight forward. Solder all the components per the footprints on the board, in the following order:

Top side:
* Resistor
* Reset switch
* Aux jack

Bottom side:
* Diodes
* Per key leds
* Headers or socket for the Pro micro compatible MCU (recommend you do this before the switches, so you can solder the headers from the top of the pcb)
* Switches
* Pro micro (the pro micro should go in the correct direction, please be careful about this, as it's easy to put it in backwards)

Top side:
* Note that before starting on the rotary encoders, if your encoders have the wide legs on the sides, you should clip them, since this pcb does not have holes for those legs. Please note that I'm *not* talking about the sides that have 2 or 3 pins. Thoes are important to keep.
* Rotary encoders (Note: there is text 'here' on both sides of the pcb. While placing the encoder in from the top, make sure you put the encoder in the holes that are closest to the word 'here')

Note: Once you solder the pro micro, you can no longer access the solder points below it. So make sure everything is done before you do this

Also, If you add rotary encoders, there are some nice covers you can 3d print and put on top for a cleaner look. This is optional, but recommended as it looks much better. See the stls directly in this folder:
* https://github.com/sadekbaroudi/bgkeeb/tree/master/cases/covers

