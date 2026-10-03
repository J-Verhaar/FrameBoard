# FrameBoard 

[![Framework Compatible](https://img.shields.io/badge/Framework_12-Compatible-blue?style=flat-square)](https://frame.work)
[![RP2040](https://img.shields.io/badge/MCU-RP2040_Zero-emerald?style=flat-square)](https://www.raspberrypi.com/products/rp2040/)

**FrameBoard** is an open-source 70% mechanical keyboard chassis that houses an entire **Framework Laptop 12 Mainboard** directly inside its body. By integrating your computer into your primary input device, FrameBoard declutters your workspace into a single, compact workstation.

Designed for the **Printables Framework Laptop 12 Mainboard Re-Use Contest**.

## Hardware Setup
1. Wire the matrix switches and diodes according to the diagram
2. Solder wires from the RP2040 to the rows, columns and encoder.

## Firmware Setup

1. Clone or download the firmware configuration folder located in `/firmware`.
2. Put the **RP2040 Zero** into bootloader mode by holding the `BOOT` button while plugging it into your computer via USB-C.
3. Drag and drop the compiled `.uf2` firmware file onto the mounted drive.
