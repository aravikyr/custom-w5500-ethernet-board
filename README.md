
# Custom W5500 Ethernet Module (ESP32-S3)

This repo contains the schematic for a custom Ethernet board based on the W5500 chip, connected to an ESP32-S3 over SPI.

## Goals
- W5500 + integrated RJ45 (HR911105A or J1B1211CCD)
- SPI interface with ESP32-S3 (MicroPython)
- Working Link/Activity LEDs

## Issues I'm Facing
- SPI works (`0x04` version reg read is successful)
- Link and ACT LEDs not turning on when cable is connected
- Want help reviewing LED wiring + general schematic quality

## Files
- `schematic/`: contains schematic source and rendered versions
- `board/`: (optional) PCB screenshots or layout files

## How You Can Help
- Check if LED wiring is correct
- Confirm proper W5500 wiring and decoupling
- Suggest improvements or test points
