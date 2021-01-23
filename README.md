# Gamesir X2 usb-c Xbox layout

TLDR; This module changes Gamesir X2 usb-c from NS layout to Xbox layout.

## Installation

zip the contents of this repo and install it in your rooted phone with magisk-Manager.

## Details

Gamesir X2 is an usb-c otg gamepad from [gamesir](https://www.gamesir.hk/). 
The X2 button layout is the same as Nintendo Switch.

To use Gamesir X" as an Xbox controller we remap the next buttons in a new keylayout file:
- A->B 
- B->A
- X->Y
- Y->X

This module injects the keylaout file in /system/usr/keylayout.
