# BlankSTM32 Projects

Here lists some common STM32 MCUs that we use for our projects. The blank project files can help to quickly identify the pinout, memory leyout, and IO capability for the target design.

## STM32F030F4

STM32F030F4 is the cheapest and smallest one in our selection. Note that it only comes with 16kB Flash space, and the HAL library will take about 50% of it.

It is suitable for small IoT sensor designs. With the TSSOP20 footprint, it can fit in small PCB boards.

## STM32F031F6

If the code is larger than 16kB, STM32F031F6 is the best replacement for F030 series. It is suitable for small IoT sensor designs with more complex functionalities like wireless communication etc.

With the TSSOP20 footprint, it can fit in small PCB boards.

## STM32F042F6

STM32F042 is the smallest one in our selection that is equipped with CAN interface.

With the TSSOP20 footprint, it can fit in small PCB boards.

## STM32F103C8

STM32F103C8 is the most common MCU. It is good for most of the starter projects, and there are many evaluation boards available to test code on.

STM32F103CB is another possible drop-in variant.

## STM32F446RE

STM32F446RE is a bit more advanced compared to STM32F103Cx, with more pin available and running at a higher clock frequency. We use this in our microbasic design.

## STM32G431CB

STM32G431CB is optimized towards mixed signal applications, with three on-chip opamps and CORDIC accelerators. It also has the faster FDCAN interface that can exceed the 1Mbps rate of CAN 2.0.
