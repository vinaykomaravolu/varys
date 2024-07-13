# Varys

![varys](https://i.imgur.com/XDd9HKF.jpeg)

The Varys is an ergonomic split keyboard meticulously designed from the ground up to provide a superior typing experience. It features a custom PCB, dual rotary encoders, OLED displays, I2C/Serial communication, and per-key RGB lighting, making it a highly versatile and visually appealing keyboard.

Inspired by the popular [Lily58](https://github.com/kata0510/Lily58) layout, the Varys offers a familiar yet enhanced ergonomic design. The split layout promotes natural hand positioning and reduces strain during prolonged typing sessions.


## Features

- Custom PCB Design (Created using Ki-CAD)
- Embedded ATmega32U4
- Dual rotary encoders
- Oled Displays
- I2C/Serial communication
- QMK support
- VIA support
- Per-Key RGB matrix
- USB-C to USB-C communication that supports I2C (USB-C 2.0) and Serial (USB-C 3.0) communication

## Hardware

- MCU: [Atmega32U4](https://ww1.microchip.com/downloads/en/devicedoc/atmel-7766-8-bit-avr-atmega16u4-32u4_datasheet.pdf)
- RGB (common anode): [S4-3528RGBTA-A](https://www.lcsc.com/datasheet/lcsc_datasheet_2105242008_TUOZHAN-S4-3528RGBTA-A_C2827321.pdf)
- Encoders: any EC11e encoders
- OLED screen: [128x32 I2C OLED](https://www.robotshop.com/products/091-inch-128x32-i2c-oled-display-blue?srsltid=AfmBOopMBvhXWwSjL9UVT_jD7w8psHUryHTW6MubviTzbzZXddA6pHVc-_U) 
- PCB: Varys PCB (design files soon to be uploaded)
- Switchs: Kailh (or any of the same type) (3 and 5 pin supported)
- Keys: Preferably ortholinear keycaps

## Software

QMK firmware with VIA support