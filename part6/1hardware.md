---
sort: 1
---
# 硬件


## 主控板

STM32 Nucleo-F446RE

- [NUCLEO-F446RE 产品概述](https://www.st.com/zh/evaluation-tools/nucleo-f446re.html)
- [设计文件下载](https://www.st.com/zh/evaluation-tools/nucleo-f446re.html#cad-resources)





## 功率板

- [Arduino-SimpleFOCShield](https://github.com/simplefoc/Arduino-SimpleFOCShield)

功率板只是完成对主板板输出的PWM信号的放大，因此无所谓用什么板。初学可以直接使用开源的驱动板，到后面应用于大功率电机时自己设计也可以。

## 转子位置传感器

有好几种可以用

### 编码器

正交编码器，直接输出编码信号，由MCU硬件解码。

测转速。

### 磁传感器

SPI通信和IIC通信都有，传感器内部已经做了一些初步运算。

输出转角信息

也有输出模拟信号的，用模拟信号指代转角。

AS5600

### 霍尔传感器

工控最常见的，检测转子位置的传感器。








