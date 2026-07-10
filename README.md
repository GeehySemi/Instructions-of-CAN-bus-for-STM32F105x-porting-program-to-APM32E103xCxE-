# STM32F105 CAN 移植至 APM32F103 指南 / STM32F105-to-APM32F103 CAN Porting Guide

[中文](#中文说明) | [English](#english)

## 中文说明

本仓库提供将 STM32F105x CAN 应用移植至 APM32F103xCxE 的技术说明，以及相关在线调试解决方案 PDF。移植时应重点核对 CAN 时钟、GPIO 复用、波特率参数、过滤器、收发器及中断名称。仓库名称中的 APM32E103 与资料文件中的 APM32F103 存在差异，请以 PDF 的准确目标型号为准并在使用前向技术支持确认。

### 使用建议

1. 核对目标 MCU、开发板、引脚和工具链。
2. 阅读仓库内技术说明或示例源码。
3. 在受控硬件上完成编译、下载与功能验证。
4. 更多资料请访问 [www.geehy.com](https://www.geehy.com/)。

---

## English

This repository provides technical notes for porting an STM32F105x CAN application to the APM32F103xCxE, plus an online-debugging solution PDF. Review CAN clocks, GPIO alternate functions, bit timing, filters, transceiver hardware, and interrupt names. The repository name references APM32E103 while the documents reference APM32F103; confirm the intended target before use.

### Recommended workflow

1. Verify the target MCU, board, pins, and toolchain.
2. Read the technical notes or example sources in the repository.
3. Build, program, and validate the project on controlled hardware.
4. For more resources, visit [www.geehy.com](https://www.geehy.com/).
