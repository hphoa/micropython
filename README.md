# micropython
micropython for STM32F411CEU6 Boards
STM32F401CCU6 CORE BOARD

In the F401 series, the IO port contains all the basic functions.

25MHZ high speed crystal oscillator 32.768k low speed crystal oscillator
STM32F411CEU6 core board 128KB RAM 512KB Flash
No DAC feature
LED PC13
Switch is on PB2

BOOT settings are changed from jumper to button to reduce the installation trouble by pressing 

BOOT0 and NRST, releasing NRST to access serial port download, DFU download, providing ST official multi-in-one STM32 Cube Programmer burning software. 

The GND is changed to 5V B9 5V GND, which can directly connect a small steering gear without additional wiring and reduce development time.

data from STM32CubeMX/STM32CubeIDE, please refer to file mpconfigboard.h

// HSE is 25MHz, CPU freq set to 96MHz
#define MICROPY_HW_CLK_PLLM (25)
#define MICROPY_HW_CLK_PLLN (192)
#define MICROPY_HW_CLK_PLLP (RCC_PLLP_DIV2)
#define MICROPY_HW_CLK_PLLQ (4)
