# ESP-32 TFT Display

This repository contains the source code and documentation for the ESP-32 TFT Display project. The ESP-32 TFT Display is a low-cost development board with a TFT display, ideal for IoT and display applications.

## Features

- ESP-32 microcontroller with built-in Wi-Fi and Bluetooth
- TFT display

## Where to Buy
- [AliExpress](https://www.aliexpress.us/item/3256806674575493.html?spm=a2g0o.order_list.order_list_main.41.55981802IPeurq&gatewayAdapt=glo2usa#nav-review)
- [Lilygo](https://lilygo.cc/products/lilygo®-ttgo-t-display-1-14-inch-lcd-esp32-control-board?srsltid=AfmBOorOqkywQFXpKBCzzPzD8ERHK11SlDCSlTF4Rrkf_rZTov_g6gKC)
- [Amazon](https://www.amazon.com/LILYGO-T-Display-Arduino-Development-CH9102F/dp/B099MPFJ9M/ref=cm_cr_arp_d_product_top?ie=UTF8)

## Youtube Tutorial
- [Watch Tutorial](https://www.youtube.com/watch?v=f9CnjAR_gBU)

## Steps

### 1. Arduino Setup
1. Install Arduino IDE
2. Install 'esp32 by Expressif Systems'
3. Install TFT_eSPI library
   - Change the header file to include in `~/Documents/Arduino/libraries/TFT_eSPI/User_Setups/User_Setup.h`
   - Comment out `#include <User_Setup.h>`
   - Uncomment `#include <User_Setups/Setup25_TTGO_T_Display.h>    // Setup file for ESP32 and TTGO T-Display ST7789V SPI bus TFT`

### 2. Executing Sample Code
1. Select "ESP Dev Module" as the board
2. Navigate to `File -> Examples -> TFT_eSPI -> 160x128 -> TFT_Print_Test`
3. Reduce the "upload speed" to 460800
4. Upload the code