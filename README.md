# LED Panel Board

![](img/led-panel-render.png)

## Overview

This project includes PCB design files for a simple 10x14 LED matrix panel.
The individual LEDs from the matrix can be controlled either with Raspberry Pi RP2040 MCU or Lattice ICE40UP5K FPGA.
The LED sequences displayed by the matrix can be synchronized with external triggering signal. 
The LED Panel Board can then be used for measuring latency in vision systems.
The custom paterns displayed by the LED Panel board can also be used for training and evaluation of extended reality (XR gogles, mobile robots and any other devices that use machine vision for environment mapping. 

The PCB design files for the LED Panel Board were prepared in KiCad 9.x.

## Key features

* 10x14 LED matrix of individually controllable LEDs
* LED control possible with RP2040 MCU or iCE40 FPGA
* External trigger signal
* Fastening studs compliant with VESA display holders and similar accessories 

## Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `img` - contains graphics for this README
* `assets` - includes visual assets for showcasing this board on Antmicro Open Hardware Portal and System Designer

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
