# OCuLink to PCIe adapter
Copyright (c) 2025 [Antmicro](https://www.antmicro.com)

[![image](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Hardware%20Portal-332d37?style=flat-square)](https://openhardware.antmicro.com/boards/oculink-to-pcie-adapter)

![](img/oculink-pcie-adapter-render.png)

## Overview

This project includes PCB design files for an adapter card which break-routes a regular OCuLink x4 connector into x16 PCIe edge card slot.
This board was designed for use with Antmicro [Jetson Orin Baseboard OCuLink Expansion](https://github.com/antmicro/job-oculink-expansion).
Please inspect the schematics and verify the connection diagrams if you plan to use that board with any other OCuLink-compliant accessories.
The PCB design files were prepared in KiCad 9.x 

## Key features

- Supports 4x PCIe link via an OCuLink connector over an x16 card edge connector
- PCIe cards can be powered via USB-C Power Delivery, EPS-12V or Molex Nano-Fit connector
- Optional on-board PCIe clock generator for SRSI and SRNS clocking configurations
- Mechanical outline optimized for  dual slot PCIe cards

## Project structure

The main directory contains KiCad PCB project files and README. 
The remaining files are stored in the following directories:

-   `img` - contains graphics for this README

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
