# MicroPython 示例

[English](README.md)

## 功能

示例演示 GC9A01 屏幕的文字、字体、图片和旋转显示，以及 CST816S 触摸输入。

## 硬件需求

ESP32-S3-Touch-LCD-1.28 开发板和 USB-C 数据线。

## 怎么运行

按[微雪文档](https://docs.waveshare.net/ESP32-S3-Touch-LCD-1.28/)安装板卡专用的 MicroPython 固件。将选定脚本和所需的字体、图片或驱动文件按原目录结构复制到开发板，再用 Thonny 运行脚本。

## 预期现象

运行 `hello.py` 后，屏幕会在不同位置以不同颜色显示 “Hello!”。运行 `cst816s_example.py` 后，串口控制台会输出触摸坐标和手势。

## 常见问题

显示示例依赖板卡固件提供的 `gc9a01` 模块。如果 `bluemarble.mpy` 与所用固件不兼容，请使用匹配版本的 `mpy-cross` 从 `bluemarble.py` 重新生成。
