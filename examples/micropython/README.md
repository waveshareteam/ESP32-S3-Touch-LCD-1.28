# MicroPython examples

[简体中文](README_ZH.md)

## What It Does

These examples demonstrate display text, fonts, images, and rotation on the GC9A01 LCD, as well as touch input from the CST816S.

## Hardware Required

An ESP32-S3-Touch-LCD-1.28 development board and a USB-C data cable.

## How to Run

Install the board-specific MicroPython firmware from the [Waveshare documentation](https://docs.waveshare.com/ESP32-S3-Touch-LCD-1.28). Copy the selected script and its matching font, image, or driver files to the board, keeping the directory structure, then run the script with Thonny.

## Expected Result

Run `hello.py` to see “Hello!” drawn at varying positions and colors. Run `cst816s_example.py` to see touch coordinates and gestures in the serial console.

## Troubleshooting

The display examples require the `gc9a01` module supplied by the board firmware. If `bluemarble.mpy` is incompatible with your firmware, rebuild it from `bluemarble.py` with a matching version of `mpy-cross`.
