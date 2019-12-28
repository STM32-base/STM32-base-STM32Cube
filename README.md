# STM32-base-STM32Cube

This repository contains the official CMSIS and HAL source files as they are provided by [STMicroelectronics](https://www.st.com) in their STM32Cube packages. Please note that this repository _only_ contains the CMSIS and HAL source files. If you are looking for any of the other files, please download the STM32Cube package for your device directly from the [STMicroelectronics website](https://www.st.com/en/embedded-software/stm32cube-mcu-packages.html).

This repository is part of the [STM32-base project](https://github.com/STM32-base). This repository is meant to be a simple way to get hold of the official CMSIS and HAL code without having to download the packages individually from STMicroelectronics. Because this repository contains code provided by STMicroelectronics, its licence deviates from the license used for all other STM32-base project repositories.

## STM32Cube packages

This repository contains the code of the following STM32Cube packages:

| Device series  | STM32Cube download website                                                | Version | Patch  |
| -------------- | ------------------------------------------------------------------------- |:------- |:------ |
| STM32F0        | [STM32CubeF0](https://www.st.com/en/embedded-software/stm32cubef0.html)   |  1.10.0 |      - |
| STM32F1        | [STM32CubeF1](https://www.st.com/en/embedded-software/stm32cubef1.html)   |   1.7.0 |  1.7.1 |
| STM32F2        | [STM32CubeF2](https://www.st.com/en/embedded-software/stm32cubef2.html)   |   1.7.0 |      - |
| STM32F3        | [STM32CubeF3](https://www.st.com/en/embedded-software/stm32cubef3.html)   |  1.10.0 |      - |
| STM32F4        | [STM32CubeF4](https://www.st.com/en/embedded-software/stm32cubef4.html)   |  1.24.0 |      - |
| STM32F7        | [STM32CubeF7](https://www.st.com/en/embedded-software/stm32cubef7.html)   |  1.15.0 |      - |
| STM32G0        | [STM32CubeG0](https://www.st.com/en/embedded-software/stm32cubeg0.html)   |   1.2.0 |      - |
| STM32H7        | [STM32CubeH7](https://www.st.com/en/embedded-software/stm32cubeh7.html)   |   1.4.0 |      - |
| STM32L0        | [STM32CubeL0](https://www.st.com/en/embedded-software/stm32cubel0.html)   |  1.11.0 | 1.11.2 |
| STM32L1        | [STM32CubeL1](https://www.st.com/en/embedded-software/stm32cubel1.html)   |   1.9.0 |        |
| STM32L4        | [STM32CubeL4](https://www.st.com/en/embedded-software/stm32cubel4.html)   |  1.14.0 |      - |
| STM32MP1       | [STM32CubeMP1](https://www.st.com/en/embedded-software/stm32cubemp1.html) |   1.0.0 |      - |
| STM32WB        | [STM32CubeWB](https://www.st.com/en/embedded-software/stm32cubewb.html)   |   1.0.0 |      - |

Since 2019, STMicroelectronics hosts the STM32Cube packages on GitHub. The following table presents links to these official repositories.

| Device series | STM32Cube MCU/MPU Package                                          | STM32Cube CMSIS Device                                                   |
| ------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| STM32F0       | [STM32CubeF0](https://github.com/STMicroelectronics/STM32CubeF0)   | [cmsis_device_f0](https://github.com/STMicroelectronics/cmsis_device_f0) |
| STM32F1       | [STM32CubeF1](https://github.com/STMicroelectronics/STM32CubeF1)   | [cmsis_device_f1](https://github.com/STMicroelectronics/cmsis_device_f1) |
| STM32F2       | [STM32CubeF2](https://github.com/STMicroelectronics/STM32CubeF2)   | [cmsis_device_f2](https://github.com/STMicroelectronics/cmsis_device_f2) |
| STM32F3       | [STM32CubeF3](https://github.com/STMicroelectronics/STM32CubeF3)   | [cmsis_device_f3](https://github.com/STMicroelectronics/cmsis_device_f3) |
| STM32F4       | [STM32CubeF4](https://github.com/STMicroelectronics/STM32CubeF4)   | [cmsis_device_f4](https://github.com/STMicroelectronics/cmsis_device_f4) |
| STM32F7       | [STM32CubeF7](https://github.com/STMicroelectronics/STM32CubeF7)   | [cmsis_device_f7](https://github.com/STMicroelectronics/cmsis_device_f7) |
| STM32G0       | [STM32CubeG0](https://github.com/STMicroelectronics/STM32CubeG0)   | [cmsis_device_g0](https://github.com/STMicroelectronics/cmsis_device_g0) |
| STM32G4       | [STM32CubeG4](https://github.com/STMicroelectronics/STM32CubeG4)   | [cmsis_device_g4](https://github.com/STMicroelectronics/cmsis_device_g4) |
| STM32H7       | [STM32CubeH7](https://github.com/STMicroelectronics/STM32CubeH7)   | [cmsis_device_h7](https://github.com/STMicroelectronics/cmsis_device_h7) |
| STM32L0       | [STM32CubeL0](https://github.com/STMicroelectronics/STM32CubeL0)   | [cmsis_device_l0](https://github.com/STMicroelectronics/cmsis_device_l0) |
| STM32L1       | [STM32CubeL1](https://github.com/STMicroelectronics/STM32CubeL1)   | [cmsis_device_l1](https://github.com/STMicroelectronics/cmsis_device_l1) |
| STM32L4       | [STM32CubeL4](https://github.com/STMicroelectronics/STM32CubeL4)   | [cmsis_device_l4](https://github.com/STMicroelectronics/cmsis_device_l4) |
| STM32MP1      | [STM32CubeMP1](https://github.com/STMicroelectronics/STM32CubeMP1) |                                                                          |
| STM32WB       | [STM32CubeWB](https://github.com/STMicroelectronics/STM32CubeWB)   | [cmsis_device_wb](https://github.com/STMicroelectronics/cmsis_device_wb) |

Other than these device-specific repositories, there’s also the [cmsis_core](https://github.com/STMicroelectronics/cmsis_core) repository.
