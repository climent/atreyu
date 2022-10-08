# Atreyu keyboard

![A picture of the original, handwired Atreyu](pictures/PXL_20210609_174723137.jpg?raw=true "The original, handwired Atreyu keyboard")
![A picture of the Atreyu (v1)](pcb/v1/pictures/keeb.jpg?raw=true "The Atreyu v1 keyboard")

It all started with a handwired Lily58fied version of the Atreis keyboard.

Based on [Dekonnection's Atreis keyboard design files](https://github.com/dekonnection/atreis),
modified to achieve the same layout in a single-piece form-factor.

## Why ?

Because the Atreis is the most convenient keyboard to take when on the go, but I thought i needed a couple of extra keys, like the Lily58.

## What happened next?

Learning KiCad was fun, and I ended up creating a new version of the keyboard on a PCB, with the option of having they inner keys as rotary encoders, and with two additional keys at the bottom of the outer columns to be pressed with the palm. In all honesty I think I could do with less keys, but using the same amount of pins in the micro controller I could have all 60 keys in the matrix defined.

In retrospect I think I could remove some keys and be happy and productive, but at the same time I enjoyed doing the design, and I like it.

## Why this name ?

Because it looks a lot like the Atreis keyboard, but with the Lily58 layout.

## How do I build one ?

You can find a [PCB](http://github.com/climent/atreyu/tree/main/pcb) for it. The board has been fully tested and the firmware is functional out of the box.

## Can I do the handwired version?

Sure. The SVG files are available. The wiring is quite straightforward: all rows are independent, and columns are combined together across both sides (columns are connected from outside to inside). You can [check this picture](pictures/atreyu-wired.jpg?raw=true "The wires"). You just have to flash the right firmware with the right keymap, all of which are available from the link below.

# Firmware

You can find my copy of the keyboard mapping [here.](http://github.com/climent/qmk_firmware/tree/master/keyboards/atreyu/)

There are 2 different revisions: handwired and rev1.

I will eventually do a merge request in upstream QMK.
