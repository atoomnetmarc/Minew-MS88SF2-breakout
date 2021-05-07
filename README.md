This is a simple breakout board for the nRF52840 Minew MS88SF2 module.

![](Minew%20MS88SF2%20breakout.jpg)

# Assembly instructions

Solder all components except the module. Clean PCB.

Test if 3V3 regulator works by connecting 5V to VIN5V-pin (with 50mA power limit). The board should not use any significant current. Measure the 3V3O-pin, it should be 3.3V.

Now solder module.

Do not forget to connect an antenna if using the MS88SF2-U.FL module.

# Checklist (WIP) V1.0 PCB

Testing and working? (after bodge fix, see V1.1 changelog)

:ballot_box_with_check:SWD (SWDIO, SWCLK, SWO)\
:ballot_box_with_check:RESET (P0.18)\
:ballot_box_with_check:USB\
:black_square_button:NFC (P0.09, P0.10)\
:black_square_button:P0.02\
:black_square_button:P0.04\
:ballot_box_with_check:LED green (P0.06)\
:black_square_button:LED RGB red (P0.08)\
:ballot_box_with_check:LED RGB blue (P0.12)\
:black_square_button:P0.13\
:black_square_button:P0.15\
:black_square_button:P0.20\
:black_square_button:P0.22\
:black_square_button:P0.24\
:black_square_button:P0.26\
:black_square_button:P0.29\
:black_square_button:P0.31\
:ballot_box_with_check:LED RGB green (P1.09)\
:black_square_button:Button (P1.13)\
:black_square_button:P1.15

# Changelog

**V1.1**

- Attached VDDH to VBUS to enable USB to work.
- Removed series resistors from USB data lines.

**V1.0**

- Everything changed out of nothing.

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)