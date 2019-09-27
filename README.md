# micropython
micropython for STM32F411CEU6 Boards
STM32F401CCU6 CORE BOARD

In the F401 series, the chip is the cheapest, even cheaper than some F1, and crushed F1 on the main frequency, and has a floating-point arithmetic module, the IO port contains all the basic functions. Therefore, it is possible to provide a learning platform with a very high cost performance for beginners. In practical applications, it is not because the computing power is insufficient, and the IO port is incomplete and hinders development. 

25MHZ high speed crystal oscillator 32.768k low speed crystal oscillator
STM32F411CEU6 core board 128KB RAM 512KB ROM
No DAC
LED PC13
Switch is on PB2

BOOT settings are changed from jumper to button to reduce the installation trouble by pressing 

BOOT0 and NRST, releasing NRST to access serial port download, DFU download, providing ST official multi-in-one STM32 Cube Programmer burning software. 

The GND is changed to 5V B9 5V GND, which can directly connect a small steering gear without additional wiring and reduce development time.

