# Atreyu keyboard

![A picture of the Atreyu](pictures/PXL_20210609_174723137.jpg?raw=true "The Atreyu keyboard")

Making a Lily58fied version of the Atreis keyboard.

Based on [Dekonnection's Atreis keyboard design files](https://github.com/dekonnection/atreis),
modified to achieve the same layout in a single-piece form-factor.

## Why ?

Because the Atreis is the most convenient keyboard to take when on the go, but I need a couple of extra keys, like the Lily58.

And because we can.

## Why this name ?

Because it looks a lot like the Atreis keyboard, but with the Lily58 layout.

## How do I build one ?

You can find a [PCB](http://github.com/climent/atreyu/tree/main/pcb) for it, but it is still untested, so for now you can download the SVG and get it cut from Ponoko.com or a similar place. The wiring is quite straightforward: all rows are independent, and columns are combined together across both sides (columns are connected from outside to inside). You can [check this picture](pictures/atreyu-wired.jpg?raw=true "The wires").

# Firmware

You can find my copy of the keyboard mapping [here.](http://github.com/climent/qmk_firmware/tree/master/keyboards/atreyu/)

I will eventually do a merge request in upstream QMK.
