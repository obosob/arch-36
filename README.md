# Obosob's arch-36 keymap

## Building

The `Makefile` in this repository assumes that
https://github.com/qmk/qmk_firmware is cloned into same parent directory as
this one and is named `qmk_firmware`. All prerequisites for QMK are required.

It will copy the source from this directory into the qmk_firmware tree and
build using the makefile there.

To build the hex file run:

    make

To build and flash the keyboard run:

    make flash

