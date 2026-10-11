# Starbie Firmware

Arduino sketch for the Starbie motion-controlled digital pet.

## Installation

1. Open `Starbie.ino` in Arduino IDE
2. Install required libraries via Sketch > Include Library > Manage Libraries:
   - Adafruit GFX Library
   - Adafruit SSD1306
   - Adafruit MPU6050
   - DHT sensor library
3. Edit the BEGINNER SETTINGS section at the top of the sketch to configure pins and behavior
4. Upload to a Seeed XIAO ESP32-C3

## Customization

All beginner-friendly settings are in the BEGINNER SETTINGS section:
- GPIO pin assignments
- Starting pet stats (joy, energy, fullness)
- Menu items and their effects
- Sensor calibration
- Pet animation parameters
