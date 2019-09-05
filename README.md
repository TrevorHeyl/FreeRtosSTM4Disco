# FreeRtos STM4Disco
Demonstrates how to bypass the CMSIS_OS wrapper layer forFreeRTOS. This is useful when accessing the FreeRTOS docs and API directly without first needing to know which CMSIS wrapper is required.

The application starts 4 tasks, one for each of the Red,Green,Blue and Yellow LEDs. The application uses 25K flash code space and 5.7K SRAM

# Development environment and Tools
This port was done with the following environment
* STMCUBE IDE V1.0.2
* STM32Cube FW F4 Version 1.24.1
* STMF4DISCOVERY devkit
* FreeRTOS Version 10.0.1

* TIM3 used as HAL tick

* FreeRTOS settings:
  * Static task stacks
  * Premption enabled
  * 1ms Tick
  * Uses Systick as clock source




