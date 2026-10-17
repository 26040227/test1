# the first LED

STM32F103C8T6 最小系统板点灯实验。

## 环境
- Keil MDK-ARM 5.43a（AC6 编译器）
- STM32CubeMX 6.15.0
- STM32CubeF1 v1.8.7

## 硬件
- 板载 LED 接在 PC13，低电平点亮

## 代码
`Core/Src/main.c` 的 `while(1)` 循环中控制 PC13。

## 编译
打开 `MDK-ARM/the first LED.uvprojx`，按 F7 编译，F8 烧录。
