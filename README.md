# RGB Matrix Panel Library Multipanel
This is a fork of @protonmaster's multi-panel fork of Adafruit's RGB Matrix Panel Library. It has a couple small changes to compile in Arduino as of 2021.  

Original fork: https://github.com/protonmaster/RGB-matrix-Panel  
Relevant discussion: https://github.com/adafruit/RGB-matrix-Panel/issues/4  

Usage:  
RGBmatrixPanel(uint8_t a, uint8_t b, uint8_t c, uint8_t sclk, uint8_t latch, uint8_t oe, boolean dbuf, uint8_t pwidth);  
Example for 2 panels:  
RGBmatrixPanel matrix(A, B, C, CLK, LAT, OE, false, 2);  

# Adafruit RGB Matrix Panel library [![Build Status](https://github.com/adafruit/RGB-matrix-Panel/workflows/Arduino%20Library%20CI/badge.svg)](https://github.com/adafruit/RGB-matrix-Panel/actions)

This is an Arduino library for our 16x32 and 32x32 RGB LED matrix panels

Pick one up at http://www.adafruit.com/products/420 & http://www.adafruit.com/products/607 !


Written by Limor Fried/Ladyada & Phil Burgess/PaintYourDragon for Adafruit Industries.  
BSD license, all text above must be included in any redistribution

To download. click the ZIP (download) button, rename the uncompressed folder RGBLEDMatrix. 
Check that the RGBmatrixPanel folder contains RGBmatrixPanel.cpp and RGBmatrixPanel.h

Place the RGBmatrixPanel library folder your arduinosketchfolder/libraries/ folder. 
You may need to create the libraries subfolder if its your first library. 
Restart the IDE.

We also have a great tutorial on Arduino library installation at:
http://learn.adafruit.com/adafruit-all-about-arduino-libraries-install-use

If you need support for RGB888 (24bpp) and need to/can run on Teensy 3.1/3.2/3.5/3.6 or 
ESP32 chips (not supported by RGB-matrix-Panel), please look at
https://github.com/marcmerlin/SmartMatrix_GFX which offers a GFX compatibility layer on
top of https://github.com/pixelmatix/SmartMatrix
