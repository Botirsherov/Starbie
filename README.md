# Starbie

A tiny motion-controlled digital pet—basically a desktop Tamagotchi. Totally not a Starboy.

## Overview

Starbie is a Half Life 1st week project featuring:
- **OLED Display**: 128x64 monochrome screen showing your pet
- **Motion Control**: Built-in accelerometer for shake detection and menu tilt
- **Pet Interactions**: Tap buttons to feed, play, pet, or nap your Starbie
- **Environmental Sensing**: Optional temperature and humidity monitoring
- **Persistent State**: Your pet's mood is saved between power cycles

## Quick Start

### Firmware
See [`firmware/README.md`](firmware/README.md) for Arduino IDE setup and upload instructions.

### Hardware
See [`hardware/kicad/README.md`](hardware/kicad/README.md) for PCB design files.

### Building
Refer to [`docs/BUILD.md`](docs/BUILD.md) for assembly instructions and component list.

## Project Structure

```
Starbie/
├── firmware/              # Arduino sketch and firmware code
├── hardware/
│   ├── kicad/            # KiCad schematic and PCB files
│   └── gerbers/          # Fabrication files for manufacturing
├── docs/                 # Documentation, BOM, and build guides
├── assets/               # 3D models and visual resources
└── README.md             # This file
```

## Pictures

![Starbie schematic](https://github.com/user-attachments/assets/6b141636-510d-4f0a-833e-400260b6a81f)
![Starbie PCB layout](https://github.com/user-attachments/assets/014172a1-87ef-411f-99af-5095f40af249)
![Starbie device rendering](https://github.com/user-attachments/assets/1491dcce-6a49-414e-a763-eadbcbf62d84)
![Starbie assembled](https://github.com/user-attachments/assets/e227210f-f3a0-460b-b0c1-7234daa68df0)

## License

Open source—feel free to build, modify, and share your own Starbies!
