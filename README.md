# BlankSTM32 Projects

Here lists some common STM32 MCUs that we use for our projects. The blank project files can help to quickly identify the pinout, memory leyout, and IO capability for the target design.

## STM32F030F4

STM32F030F4 is the cheapest and smallest one in our selection. Note that it only comes with 16kB Flash space, and the HAL library will take about 50% of it.

It is suitable for small IoT sensor designs. With the TSSOP20 footprint, it can fit in small PCB boards.

- User Manual: [RM0360](https://www.st.com/resource/en/reference_manual/dm00091010-stm32f030x4x6x8xc-and-stm32f070x6xb-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)

- JLC#: `C32908`

## STM32F031F6

If the code is larger than 16kB, STM32F031F6 is the best replacement for F030 series. It is suitable for small IoT sensor designs with more complex functionalities like wireless communication etc.

With the TSSOP20 footprint, it can fit in small PCB boards.

- User Manual: [RM0091](https://www.st.com/resource/en/reference_manual/rm0091-stm32f0x1stm32f0x2stm32f0x8-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)

- JLC#: `C465971`

## STM32F042F6

STM32F042 is the smallest one in our selection that is equipped with CAN interface.

With the TSSOP20 footprint, it can fit in small PCB boards.

- User Manual: [RM0091](https://www.st.com/resource/en/reference_manual/rm0091-stm32f0x1stm32f0x2stm32f0x8-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)

- Digikey [link](https://www.digikey.com/en/products/detail/stmicroelectronics/STM32F042F6P6/5268189)

- JLC#: `C81000`

## STM32F103CB

STM32F103CB is the most common MCU. It is good for most of the starter projects, and there are many evaluation boards available to test code on.

STM32F103C8 is another possible drop-in variant.

- User Manual: [RM0008](https://www.st.com/resource/en/reference_manual/cd00171190-stm32f101xx-stm32f102xx-stm32f103xx-stm32f105xx-and-stm32f107xx-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)

- JLC#: `C8304` (CBT6) `C8734` (C8T6)

## STM32F303RE

STM32F303RE comes with 4 independent OpAmps and 6 ADCs. Very good for multi-channel mixed-signal applications. Used in the 3D scale project.

- JLC#: `C183214`

## STM32F446RE

STM32F446RE is a bit more advanced compared to STM32F103Cx, with more pin available and running at a higher clock frequency. We use this in our microbasic design.

- User Manual: [RM0390](https://www.st.com/resource/en/reference_manual/dm00135183-stm32f446xx-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)

- JLC#: `C69336`

## STM32G431CB

STM32G431CB is optimized towards mixed signal applications, with three on-chip opamps and CORDIC accelerators. It also has the faster FDCAN interface that can exceed the 1Mbps rate of CAN 2.0.

- User Manual: [RM0440](https://www.st.com/resource/en/reference_manual/dm00355726-stm32g4-series-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)

- JLC#: `C529355`
