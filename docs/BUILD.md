# Starbie Build Guide

## Hardware Requirements

- Seeed XIAO ESP32-C3 microcontroller
- 128x64 OLED display (I2C)
- MPU6050 accelerometer/gyroscope
- DHT11 temperature/humidity sensor (optional)
- 2x Push buttons
- PCB and components (see BOM.md)

## Assembly

Refer to the KiCad PCB layout in `hardware/kicad/` for component placement.

## Flashing Firmware

1. Follow instructions in `firmware/README.md`
2. Upload using Arduino IDE

## Testing

- Verify all sensors respond
- Check button debouncing
- Test motion detection via shake
- Confirm OLED display works
