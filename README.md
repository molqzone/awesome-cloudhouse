# Awesome Cloudhouse

Awesome Cloudhouse 项目受 Project Awesome 启发，旨在构建一个面向硬件与嵌入式开发领域的**优质资源合集**。本项目由广东工业大学大云屋众创空间硬件组发起并维护，系统整理并收录嵌入式及硬件方向中的优秀教程、工具、开源项目、技术文章等资源。

我们希望借鉴 Project Awesome 的开源协作模式，打造一个便于团队内部学习共享、共同进步的知识库，并为孵化高质量项目提供持续的灵感来源与技术支撑。

-   [学习资源](#学习资源)
    -   [硬件基础与电路设计](#硬件基础与电路设计)
    -   [MCU 与片上系统](#mcu-与片上系统)
    -   [信号处理](#信号处理)
    -   [编程语言与范式](#编程语言与范式)
-   [操作系统, SDKs 与中间件](#操作系统-sdks-与中间件)
    -   [RTOS](#rtos)
    -   [厂商 SDKs 与 HAL 库](#厂商-sdks-与-hal-库)
    -   [中间件](#中间件)
-   [项目与源码 (按领域)](#项目与源码-按领域)
    -   [机器人与自动化](#机器人与自动化)
    -   [物联网](#物联网)
    -   [电机控制](#电机控制)
    -   [机器视觉](#机器视觉)
    -   [音频与语音处理](#音频与语音处理)
    -   [边缘计算与 AIoT](#边缘计算与-aiot)
    -   [数字电源](#数字电源)
    -   [无线通信与射频](#无线通信与射射频)
-   [工具与软件](#工具与软件)
    -   [EDA 与仿真](#eda-与仿真)
    -   [编译与构建](#编译与构建)
    -   [调试与分析](#调试与分析)
-   [社区与生态](#社区与生态)
    -   [Awesome 列表](#awesome-列表)
    -   [博客与频道](#博客与频道)
    -   [社区与论坛](#社区与论坛)

## 学习资源

### 硬件基础与电路设计



### MCU 与片上系统

* [江协科技 STM32 入门教程](https://www.bilibili.com/video/BV1th411z7sn/) - 经典的 STM32 标准库入门系列教程
* [keysking 的 STM32 教程](https://space.bilibili.com/6100925/lists/1025423?type=season) - 以生动的动画为特色的 STM32 HAL 库入门系列教程

### 嵌入式操作系统

* [FreeRTOS Kernel Book](https://github.com/FreeRTOS/FreeRTOS-Kernel) - FreeRTOS 官方的入门教程
* [FreeRTOS 极速掌握](https://space.bilibili.com/6100925/lists/6566637?type=season) - keysking 主讲的易懂 FreeRTOS 教程

### 信号处理

* [PySDR](https://pysdr.org/index.html) - 使用 Python 学习软件无线电与信号处理

### 编程语言与范式

* [cppreference](https://cppreference.cn/w/) - C 和 C++ 语言的权威技术参考手册（中文镜像），包含详细的 API 文档和示例

## 操作系统, SDKs 与中间件

### RTOS

* [FreeRTOS](https://www.freertos.org/) - 行业标准，轻量级、简单且被广泛应用的嵌入式实时操作系统内核
* [RT-Thread](https://www.rt-thread.org/) - 源自中国的开源物联网操作系统，具有丰富的组件和易于使用的工具链
* [Zephyr](https://www.zephyrproject.org/) - Linux 基金会旗下项目，安全、可扩展且支持多种架构的实时操作系统


### 厂商 SDKs 与 HAL 库
* [Embassy](https://embassy.dev/) - 基于 Rust 异步 / await 机制构建的现代嵌入式框架 (HAL)
* [libxr](https://github.com/Jiu-xiao/libxr) - 基于 C++ 模块化设计的硬件抽象层，旨在简化跨平台嵌入式开发
* [XRobot](https://xrobot-org.github.io/) - 一套基于 libxr 的面向嵌入式系统的自动化代码生成工具，提升开发效率
* [STM32Cube](https://www.st.com/en/development-tools/stm32cubemx.html) - ST 官方提供的 STM32 系列微控制器图形化配置工具与底层驱动/中间件包 (HAL, LL)

### 中间件
* [LittlevGL](https://lvgl.io/) - 轻量级多功能图形库 (LVGL)，资源占用低，可轻松为嵌入式设备创建美观的 UI
* [TouchGFX](https://www.st.com/en/embedded-software/touchgfxdesigner.html) - ST 官方推出的高性能图形软件框架，针对 STM32 微控制器进行了优化
* [lwIP](https://savannah.nongnu.org/projects/lwip/) - 轻量级 TCP/IP 协议栈，专为资源受限的嵌入式系统设计，占用内存小
* [TinyUSB](https://github.com/hathach/tinyusb) - 一个开源、跨平台的 USB Host/Device 协议栈，结构清晰且易于移植
* [XRUSB](https://github.com/Jiu-xiao/xrusb) - 一个专注于可移植性、高性能和简单集成的现代 C++ USB 协议栈

## 项目与源码

### 机器人与自动化

### 物联网



### 电机控制

* [SimpleFOC](https://www.simplefoc.com/) - 一个开源、易于使用的无刷直流电机磁场定向控制 (FOC) 算法库，支持 Arduino, STM32 等多种平台

### 机器视觉



### 音频与语音处理



### 边缘计算与 AIoT

* [小智 AI](https://github.com/78/xiaozhi-esp32) - 基于 ESP32 的 LLM 语音助手

### 数字电源



### 无线通信与射频



## 工具与软件

### EDA 与仿真

* [KiCad](https://www.kicad.org/) - 业界领先的开源电子设计自动化 (EDA) 软件套件，用于原理图设计和 PCB 布局
* [立创 EDA](https://lceda.cn/) - 基于 Web 的国产 EDA 工具，与立创商城和嘉立创 PCB 制造深度集成，方便快速打样

### 编译与构建

* [ARM Compiler for Embedded 6](https://developer.arm.com/Tools%20and%20Software/Arm%20Compiler%20for%20Embedded) - Arm 官方基于 Clang/LLVM 技术的 C/C++ 编译器，为 Armv6-M/v7-M 提供最佳性能和代码大小优化，并支持精细内存布局
* [Arm Toolchain for Embedded](https://developer.arm.com/Tools%20and%20Software/Arm%20Toolchain%20for%20Embedded) - Arm 推出的新一代 LLVM 编译工具链，专注于 64 位 (AArch64) 处理器、GNU 兼容性，并提供 100% 开源版本
* [Arm GNU Toolchain](https://developer.arm.com/Tools%20and%20Software/GNU%20Toolchain) - Arm 官方维护的 GNU 工具链 (GCC)，是 Cortex-M 裸机和 RTOS 开发中最传统、应用最广泛的开源编译器

### 调试与分析

* [OpenOCD](https://openocd.org/) - 开源的片上调试器 (On-Chip Debugger) 软件，支持多种调试适配器 (如 ST-Link, J-Link, DAPLink) 和目标芯片
* [probe-rs](https://probe.rs/) - 一个现代、高性能的 Rust 工具集，用于调试和刷写 ARM 和 RISC-V 嵌入式目标，尤其在 Rust 嵌入式社区中流行
* [JLink Ozone](https://www.segger.com/products/development-tools/ozone-j-link-debugger/) - SEGGER 官方推出的功能强大的图形化 J-Link 调试器，以其高性能、实时数据可视化和代码分析而闻名

## 社区与生态

### Awesome 列表

* [Awesome C](https://github.com/inputsh/awesome-c) - 精选的 C 语言框架、库、资源和教程的集合
* [Awesome C++](https://github.com/fffaraz/awesome-cpp) - 精选的 C++ 框架、库、资源和教程的集合
* [Awesome Embedded Rust](https://github.com/rust-embedded/awesome-embedded-rust) - 精选的 Rust 嵌入式开发资源、库、工具和项目列表

### 博客与频道

* [Linux DO](https://www.linuxdo.org/) - 一个活跃的技术与开源社区，讨论氛围友好
* [硬汉嵌入式](https://space.bilibili.com/20320140) - 专注于嵌入式 Linux 驱动与系统开发的 Bilibili/公众号知识分享频道

### 社区与论坛

* [E 萌工作室](https://www.emoe.xyz/) - 起步于西安电子科技大学，旨在分享电子作品，传播电子技术知识的工作室

# 贡献

我们非常欢迎任何人的贡献！为确保流程顺畅，请先查阅 [贡献指南](CONTRIBUTING.md)。感谢您为 Awesome Cloudhouse 添砖加瓦！