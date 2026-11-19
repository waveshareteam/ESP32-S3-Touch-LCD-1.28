# ESP32-S3-Touch-LCD-1.28-Test

[English](README.md) | [简体中文](README_ZH.md)

## 功能

LCD、触摸、IMU 和电池 ADC 测试。

## 硬件需求

- ESP32-S3-Touch-LCD-1.28 开发板
- USB-C 数据线

## 怎么运行

1. 安装 Arduino IDE 和 Arduino-ESP32 **3.3.11**。
2. 把项目文件夹位置设为 `examples/arduino/`，或把 `examples/arduino/libraries/` 复制到项目文件夹下的 `libraries` 文件夹。
3. 选择 `ESP32S3 Dev Module`，并设置以下选项：

   | 工具菜单 | 取值 |
   | --- | --- |
   | Flash Size | 16MB |
   | PSRAM | OPI PSRAM |
   | Flash Mode | QIO |
   | Partition Scheme | 16M Flash (3MB APP/9MB FATFS) |
   | USB Mode | Hardware CDC and JTAG |
   | USB CDC On Boot | Enabled |

4. 打开 `.ino` 文件并上传。

## 预期现象

初始化 GC9A01 显示屏、CST816S 触摸控制器和 QMI8658 传感器测试，并显示图形、通过串口输出读数。

## 常见问题

屏幕和触摸接线由本示例附带的开发板配置固定。
