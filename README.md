# a500plus-chipram-expansion

This is a 1MB chip RAM expansion designed for the Amiga 500+ in KiCad.

![a500plus-chipram board image](https://raw.githubusercontent.com/blark/a500plus-chipram-expansion/master/media/rev1_render.png)

It is in the experimental phase, but I've assembled it and it appears to be working great. However, you've been warned!

## Features

Small (42mmx52mm), simple design using only a 40 pin (2x20) female 2.54mm connector the remaining pins are for RTC which is on-board the A500+.

40 pin connectors are cheap and plentiful. However, one WARNING: make sure you plug it in correctly see the install section below).

## Schematic

A PDF file of the schematic can be found [in this repo](https://raw.githubusercontent.com/blark/a500plus-chipram-expansion/master/media/schematic.pdf).

## BOM
| Designator | Description |
| ---------- | ----------- |
| J1 | 40P (20x2) female header 2.54mm |
| J2 |     2P (1x2) male 90 degree header 2.54mm |
| U1-U2 |    IS41C16257-35T 4mbit DRAM (256 x 16) |
| C1-C6 |  100nF 805 capacitor |

## Install

Be careful during install to match pin 1 on the expansion with pin 1 on the A500+ memory expansion port! Here's an image of how it should be installed:

![a500plus-chipram board install orientation](https://raw.githubusercontent.com/blark/a500plus-chipram-expansion/master/media/install.png)

## Thanks

The parts library I've included in this repo is "borrowed" from [Kai Robinson](https://github.com/kr239) check out his great projects!
