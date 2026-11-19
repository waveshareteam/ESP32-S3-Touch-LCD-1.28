# LVGL_Arduino

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

LVGL user interface on the round display.

## Hardware Required

- ESP32-S3-Touch-LCD-1.28 development board
- USB-C cable

## How to Run

1. Install Arduino IDE and Arduino-ESP32 **3.3.11**.
2. Set the sketchbook location to `examples/arduino/`, or copy `examples/arduino/libraries/` into the sketchbook `libraries` folder.
3. Select `ESP32S3 Dev Module` and set these options:

   | Tools menu | Value |
   | --- | --- |
   | Flash Size | 16MB |
   | PSRAM | OPI PSRAM |
   | Flash Mode | QIO |
   | Partition Scheme | 16M Flash (3MB APP/9MB FATFS) |
   | USB Mode | Hardware CDC and JTAG |
   | USB CDC On Boot | Enabled |

4. Open the `.ino` file and upload it.

## Expected Result

Starts LVGL on the GC9A01 display and shows the sample interface with touch input.

## Troubleshooting

The display and touch wiring are fixed by the board configuration bundled with this example.
