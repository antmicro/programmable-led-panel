# Programmable LED Panel Board

Copyright (c) 2024-2025 [Antmicro](https://www.antmicro.com)

![](img/led-panel-render.png)

## Overview

This project includes PCB design files for a simple 10x14 LED matrix panel.
The individual LEDs from the matrix can be controlled either with a Raspberry Pi RP2040 MCU or a Lattice ICE40UP5K FPGA.
The LED sequences displayed by the matrix can be synchronized with an external triggering signal. 
The LED Panel Board can then be used for measuring latency in vision systems.
The custom patterns displayed by the LED Panel Board can also be used for training and evaluation of extended reality systems (XR goggles, mobile robots and any other device that uses machine vision for environment mapping). 

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
* `assets` - includes visual assets for showcasing this board on Antmicro's Open Hardware Portal and System Designer
* `doc` - includes board schematic in PDF format 

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
