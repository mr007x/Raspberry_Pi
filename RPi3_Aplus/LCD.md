# Waveshare 3.5 inch RPi LCD version B

Some facts about the LCD.

## Features

* 480x320 Hardware Resolution
* Resistive Touch Control
* Supports any revision of Raspberry Pi
* Drivers provided
* Supports FBCP software driver, allows software resolution config and dual-display setup
* IPS Technology

## Key Parameters

* LCD Type:                     IPS
* LCD Interface:                SPI
* Touch Screen Type:            Resistive
* Touch Screen Controller:      XPT2046
* Colors:                       65536
* Backlight:                    LED
* Resolution:                   320x480 pixels
* Aspect Ratio:                 0,336805556

## Interface

* PIN No.                   Symbol          Description
* 1, 17                     3.3V            Power Positive (3.3V Power Input)
* 2, 4                      5V              Power Positive (5V Power Input)
* 3,5,7,8,10,12,13,15,16    NC              NC
* 6,9,14,20,25              GND             Ground
*                           11PT_IRQ        Touch Panel Interrupt, low level while touch detect
*                           18LCD_RS        Instruction/data Register Selection
*                           19LCD_SI/TP_SI  SPI Data Input of LCD/Touch
*                           21TP_SO         SPI Data Output of Touch
*                           22RST           Reset
*                           LCD_SCK/23      SPI Clock of LCD/Touch
*                           24LCD_CS        LCD Chip selection, low active
*                           26TP_CS         Touch Panel chip selection, low active

Type C, TFT display with 125MHz High-Speed SPI.

## Development Resources

Wiki:
https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B)
