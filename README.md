# STM32 4-Channel DC Motor Drive @5V

Quick view of STM32F030C8T6 based 4-Channel Motor Driver board rated at 5V and powered either via a Mini USB connector or solder pads.

8 X Logic Input and 2 X +5V pads and that can accomodate standard 2.54mm dupont header or direct soldering of wiring

**All GPIO Inputs / Outputs are rated at 3.3V**

The board measures at approximately 28mm X 43mm.

<img width="432" alt="STM32 4 Channel Motor Driver" src="https://github.com/gxdeange/STM32-4-Channel-Driver-5V/assets/57690555/3a9d2180-9d7f-478c-9a03-9105e6498f13">

# STM32 4-Channel DC Motor Drive W/ UART @5V

**All GPIO Inputs / Outputs are rated at 3.3V**

<img width="434" alt="STM32 UART" src="https://github.com/gxdeange/STM32-4-Channel-Driver-5V/assets/57690555/f6466a39-403e-4256-aa9f-e4c59c417cae">

# Motor Input / Output mapping to MCU:

![image](https://github.com/gxdeange/STM32-4-Channel-Brushed-DC-Motor-Driver-5V/assets/57690555/fc530851-c15c-447c-875d-9efd35a9aa98)


<img width="953" alt="Motor Connections" src="https://github.com/gxdeange/STM32-4-Channel-Driver-5V/assets/57690555/8585ab62-06de-409f-9982-ed3c28404018">

# PROGRAMMING NOTE

This MCU does not use an external crystal. The Internal RC Clock (HSI) must be initialised at the start of your code.
