# AdafruitColorTFTJoystickFeatherWing

*Particle Library for Adafruit Mini Color TFT with Joystick FeatherWing*


This library makes it easy to use the [Adafruit Mini Color TFT with Joystick FeatherWing](https://www.adafruit.com/product/3321) with Particle mesh devices (Argon, Boron, Xenon). Additional information the board is available [here](https://learn.adafruit.com/adafruit-mini-tft-featherwing).

| Pin | Function | 
| --- | --- |
| D2 | TFT CS | 
| D3 | TFT CD | 
| SCK | TFT SCK | 
| MOSI | TFT DI |

This library basically just pulls in the necessary libraries and provides working examples. It directly depends on:

- [Adafruit_ST7735_RK](https://github.com/rickkas7/Adafruit_ST7735_RK)
- [Adafruit_Seesaw](https://github.com/bsatrom/Adafruit_Seesaw)

The ST7735_RK library further depends on:

- [Adafruit_GFX_RK](https://github.com/rickkas7/Adafruit_GFX_RK)



## Examples

### 2-basic

This is the basic example from the Adafruit\_ST7735. It does some basic graphics and also shows how to handle the joystick and buttons.

### 3-graphicstest

This is the graphics example from the Adafruit\_ST7735. It does more advanced graphics and text on the display.










