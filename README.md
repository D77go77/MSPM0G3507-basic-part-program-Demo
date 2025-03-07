# MSPM0G3507 基础功能演示程序

本仓库包含针对 MSPM0G3507 微控制器的一系列基础功能演示程序，每个功能模块都以 `.7z` 文件的形式提供。这些程序涵盖从基础工程模板到高级串口通信与传感器集成的多个功能，旨在帮助开发者快速上手和掌握 MSPM0G3507 的使用。

## 目录

1. [文件06_ws_00_空文工程模板.7z](#文件06_ws_00_空文工程模板)
2. [文件06_ws_01_定时器中断和时钟配置.7z](#文件06_ws_01_定时器中断和时钟配置)
3. [文件06_ws_02_按键.7z](#文件06_ws_02_按键)
4. [文件06_ws_03_普通串口接受与发送.7z](#文件06_ws_03_普通串口接受与发送)
5. [文件06_ws_04_pwm控制电机.7z](#文件06_ws_04_pwm控制电机)
6. [文件06_ws_05_adc采集电压.7z](#文件06_ws_05_adc采集电压)
7. [文件06_ws_06_编码器读取.7z](#文件06_ws_06_编码器读取)
8. [文件06_ws_07_蜂鸣器报警.7z](#文件06_ws_07_蜂鸣器报警)
9. [文件06_ws_08_pwm控制舵机.7z](#文件06_ws_08_pwm控制舵机)
10. [文件06_ws_09_修改时钟数为40Mhz.7z](#文件06_ws_09_修改时钟数为40Mhz)
11. [文件06_ws_10_读取mpu6050原始值.7z](#文件06_ws_10_读取mpu6050原始值)
12. [文件06_ws_11_读取6050_roll_pitch.7z](#文件06_ws_11_读取6050_roll_pitch)
13. [文件06_ws_12_采彩队列串口+超时中断.7z](#文件06_ws_12_采彩队列串口超时中断)

---

## 模块功能描述

### 文件06_ws_00_空文工程模板
- **功能描述**: 提供一个空白工程模板。
- **目的**: 用于快速创建新项目的标准化起点。

### 文件06_ws_01_定时器中断和时钟配置
- **功能描述**: 演示定时器中断和时钟的配置方法。
- **目的**: 帮助开发者掌握硬件定时器的基本用法。

### 文件06_ws_02_按键
- **功能描述**: 实现按键输入的检测。
- **目的**: 学习按键消抖与输入处理的基本技巧。

### 文件06_ws_03_普通串口接受与发送
- **功能描述**: 演示通过标准 UART 发送和接收数据。
- **目的**: 了解串口通信的基本原理和实现方法。

### 文件06_ws_04_pwm控制电机
- **功能描述**: 使用 PWM（脉宽调制）来控制电机。
- **目的**: 学习嵌入式系统中的电机控制技术。

### 文件06_ws_05_adc采集电压
- **功能描述**: 使用 ADC（模数转换）采集电压信号。
- **目的**: 掌握模拟信号采集与处理的基础。

### 文件06_ws_06_编码器读取
- **功能描述**: 读取编码器数据以获取位置信息。
- **目的**: 实现与旋转或线性编码器的集成。

### 文件06_ws_07_蜂鸣器报警
- **功能描述**: 实现蜂鸣器报警功能。
- **目的**: 用于声音提示或警报的实现。

### 文件06_ws_08_pwm控制舵机
- **功能描述**: 使用 PWM 控制舵机角度。
- **目的**: 掌握舵机控制技术，用于位置调节。

### 文件06_ws_09_修改时钟数为40Mhz
- **功能描述**: 修改系统时钟配置为 40MHz。
- **目的**: 学习系统时钟的修改及其影响。

### 文件06_ws_10_读取mpu6050原始值
- **功能描述**: 读取 MPU6050 的原始数据。
- **目的**: 初步接触 IMU（惯性测量单元）的基本用法。

### 文件06_ws_11_读取6050_roll_pitch
- **功能描述**: 通过 MPU6050 数据计算 Roll 和 Pitch 角度。
- **目的**: 使用传感器数据实现姿态测量。

### 文件06_ws_12_采彩队列串口+超时中断
- **功能描述**: 结合串口通信和超时中断进行数据处理。
- **目的**: 演示高级串口处理方法，包括队列和超时管理。

---

## 使用方法

1. 克隆本仓库：
   ```bash
   git clone https://github.com/D77go77/MSPM0G3507-basic-part-program-Demo.git
   ```
2. 解压 `.7z` 文件：
   请使用 [7-Zip](https://www.7-zip.org/) 或其他压缩工具解压各模块文件。
3. 按照每个模块中的代码和注释，运行并测试功能。

---

## 环境需求

- **开发环境**: 确保安装了适用于 MSPM0G3507 的编译器和调试器（如 TI Code Composer Studio）。
- **工具**: 解压软件（推荐 [7-Zip](https://www.7-zip.org/)）。

---

## 贡献

欢迎大家对本项目提出改进意见或提交新功能模块。如果您想贡献代码或文档，请提交 Pull Request 或创建 Issue 进行讨论。

---

## 许可证

本项目基于 [GNU General Public License v3.0 (GPLv3)](https://www.gnu.org/licenses/gpl-3.0.html) 协议开源。您可以自由使用、修改和分发本项目代码，但需遵守 GPLv3 的相关条款。

---
