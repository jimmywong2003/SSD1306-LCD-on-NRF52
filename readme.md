# nrf52 LCD display with SSD1306 through TWI interface

## Description
-----------
There are two examples to run on SSD1306 (128x32 / 128x64) resolution with nRF52840 DK.

1) Port the Adafruit SSD1306 Library / GFX Library (refer to http://electronut.in/bluey/)

2) Port on the SSD1306 driver (refer to https://github.com/monpetit/nrf52-spi-i2c-master-ssd1306)


## Configuration of the display resolution

Define in SSD1306.h

```c
#define SSD1306_128_64
//#define SSD1306_128_32
//#define SSD1306_96_16
```

![Image of SSD1306 128_32](/images/SSD1306_128_32_NRF52840_DK_board.png)

![Image of SSD1306 128_64](/images/SSD1306_128_64_NRF52840_DK_board.png)



# Requirements
------------
- nRF5 SDK version 15.2.0
- nRF52840 DK 

The project may need modifications to work with later versions or other boards. 

To compile it, clone the repository in the /nRF5_SDK_15.2.0/examples/ directory.

The application is built to be used with the official nRF5 SDK that can be downloaded from developer.nordicsemi.com

