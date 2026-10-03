# FrameBoard 

[![Framework Compatible](https://img.shields.io/badge/Framework_12-Compatible-blue?style=flat-square)](https://frame.work)
[![RP2040](https://img.shields.io/badge/MCU-RP2040_Zero-emerald?style=flat-square)](https://www.raspberrypi.com/products/rp2040/)

**FrameBoard** is an open-source 70% mechanical keyboard chassis that houses an entire **Framework Laptop 12 Mainboard** directly inside its body. By integrating your computer into your primary input device, FrameBoard declutters your workspace into a single, compact workstation.

Designed for the **Printables Framework Laptop 12 Mainboard Re-Use Contest**.

## Hardware Setup
_(If youre unfamiliar with how to handwire and solder a keyboard watch the following video: [Tutorial by Joe Scotto](https://www.youtube.com/watch?v=hjml-K-pV4E&t=14s))_

1. Wire the matrix switches and diodes according to the diagram. Connect the diodes between the row wires and the switches.
<img width="2560" height="1440" alt="KeyboardMatrix" src="https://github.com/user-attachments/assets/3082e2ec-ef17-498b-b02d-534b0d438e89" />
 
 
2. Solder wires from the RP2040 Zero to the rows, columns and encoder according to the diagram. 
<img width="2560" height="1440" alt="RP2040_Pinout" src="https://github.com/user-attachments/assets/5cd3b9d1-d9dd-4d35-942b-6c633c0a2e53" />

## Firmware Setup
1. Clone or download the firmware configuration folder located in `/firmware`.
2. Put the **RP2040 Zero** into bootloader mode by holding the `BOOT` button while plugging it into your computer via USB-C.
3. Drag and drop the compiled `.uf2` firmware file onto the mounted drive.
