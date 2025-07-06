# Blue Pill LED Blink (STM32F103C8T6)

Minimal firmware to blink the onboard PC13 LED on the STM32 Blue Pill board.

## Features
- Blinks onboard PC13 LED (active-low)
- Uses STM32 HAL libraries
- Compatible with STM32CubeIDE
- Simple main loop with delay-based timing

## Hardware
- **Board**: STM32F103C8T6 "Blue Pill"
- **LED**: Onboard PC13 (inverted logic: `0` = ON, `1` = OFF)
- **Clock**: Internal 8MHz HSI

## Setup
1. Clone this repo
2. Open project in STM32CubeIDE
3. Build & flash to Blue Pill
4. LED will blink at ~1Hz

## Configuration
- Clock: Default HSI 8MHz
- PC13 configured as:
  - Output push-pull
  - No pull resistor
  - Low speed

## Dependencies
- STM32CubeF1 HAL (included)
- STM32CubeIDE

