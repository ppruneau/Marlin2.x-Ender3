# Marlin2.x for Ender 3
My personnal configuration for Marlin 2.x on the Ender 3

Check various branches for different configuration (SKR Mini E3 V1.2, SKR 1.4 Turbo, etc)

Mostly up to date, depending of the board I'm using at the moment.

Hoping it to be a good "example" for everyone starting to build a fresh Marlin from scratch.

## Branch : SKR1.4Turbo-Marlin2.0.x

Current setup in this configuration

 - SKR 1.4 Turbo with TMC 2209 drivers (UART Mode)
 - BTT TFT24 screen with touch and Marlin mode enabled (ex. : https://www.amazon.ca/gp/product/B0817P2BXT/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
 - Extruder :
  Recommended eSteps : 165 for Dual-gear extruder (ex. : https://www.amazon.ca/LEOWAY-Upgraded-Replacement-Extrusion-Aluminum/dp/B07XKKX2FY/ref=sr_1_5?crid=1L3K7M4DWMC6A&dchild=1&keywords=dual+gear+extruder&qid=1602210170&sprefix=dual+gear+%2Caps%2C141&sr=8-5)
  Recommended eSteps : 480 for BMG Clone Dual Gear extruder (ex. : https://www.amazon.ca/gp/product/B083FGFJCM/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
 - BLTouch enabled
 - Stock NEMA motor
 - E3D V6 Hotend (only the resistors type is change in the configuration everything else is stock)
 - Stock bed
 - Sensorless Homing enabled
 - Runout sensor configured with Normally Open  (NO) circuit (so if you "bypass" the sensor, no biggies everything works fine)
