# Atreyu V2 choc keyboard

![A picture of the Atreyu V2 choc](../../pictures/atreyu-v2-choc.jpg?raw=true "The Atreyu keyboard")

# Changes from V1

* New options for MCUs:
  * Pro Micro: with this MCU the functionality of the keyboard is only reduced by not being able to use encoders.
  * Elite-C, Elite-Pi, Puchi, Frood: all the functioinality, i.e., OLED, encoders, all keys.
  * Nice!Nano v2: all functionality plus wireless! (Some restrictions apply)

| MCU     | OLED |Encoders | Bluetooth (ZMK) | LEDs |
|---------|------|---------|-----------------|------|
|ProMicro | ✅   | 🚧      |                 | ✅   |
|Elite-C  | ✅   | ✅      |                 | ✅   |
|nice!nano| 🚧   | ✅      | ✅              | ✅   |

* OLED pins for a 32x128 screen over the MCU
* Space for a battery, with power kill switch and pins for soldering the battery to the PCB, currently for a 500mAh
  * Different versions of the PCB will be released for different battery sizes.
* 5 underglow LED (SK6812Mini-E slots) as status indicators.

The new Rev2 revision is not pin-compatible with Rev1.

Due to the fact that some pins are shared across the OLED, the encoders and the LEDs, some configurations require sacrificing some features in favour of others. E.g., in a board with OLED and LEDs, one can only have one encoder.

NOTE: Elite-pi, Frood, and similar rp2040-based boards work the same way as the Elite-C board, as they have the same number of pins available.

# Firmware

You can find my copy of the keyboard mapping [here.](http://github.com/climent/qmk_firmware/tree/master/keyboards/atreyu/)

QMK firmware is available upstream, under the rev2 folder.

ZMK configuration for the Nice!nano board is available [here](https://github.com/climent/zmk-config)
