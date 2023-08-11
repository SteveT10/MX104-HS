# mx_104

![mx_104](imgur.com image replace me!)

# Default MX-104 Layout

This is the default and only layout for the MX-104 board. Key layout is unchanged
from the full size ANSI layout.

* Keyboard Maintainer: [Steven Tieu](https://github.com/stevet10)
* Hardware Supported: *MX-104 Custom PCB*
* Hardware Availability: *Directly from designer*

Make example for this keyboard (after setting up your build environment):

    make mx_104:default

Flashing example for this keyboard:

    make mx_104:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
