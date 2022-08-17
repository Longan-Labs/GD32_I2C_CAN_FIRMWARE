# GD32 I2C CAN FIRMWARE

[![Actions Status](https://github.com/arduino/arduino-cli-example/workflows/test/badge.svg)](https://github.com/arduino/arduino-cli-example/actions)
[![Spell Check](https://github.com/arduino/compile-sketches/workflows/Spell%20Check/badge.svg)](https://github.com/arduino/compile-sketches/actions?workflow=Spell+Check)
[![codecov](https://codecov.io/gh/arduino/compile-sketches/branch/main/graph/badge.svg?token=Uv6f1ebMZ4)](https://codecov.io/gh/arduino/compile-sketches)

This code uses GD32E103/GD32C103 to realize the function of I2C to CAN Bus.

Since the GD32E103 and GD32C103 are pin to pin compatible, these codes will work for both chips.

## Development environment and tools

This project is compiled with Keil, the version I use is 5.26.2.0, but other versions should be used as well.

Simulation tools can use ST-Link or JLink.

## Respository Contents

* [**/Firmware**](./Firmware) - Keil project
* [**/GD32C10x_AddOn_V1.0.0**](./GD32C10x_AddOn_V1.0.0) - AddOn file for GD32C103/GD32E103
* [**GD32C103_DATASHEET.PDF**](./GD32C103_DATASHEET.PDF) - Datasheet for GD32C103
* [**GD32C10x_Firmware_Library_V1.0.2**](./GD32C10x_Firmware_Library_V1.0.2) - Example code for GD32C103



## Get a Dev Board

If you need a Dev board, plese try,

- [CANBed Dual](https://www.seeedstudio.com/CANBed-DUAL-RP2040-based-Arduino-CAN-Bus-dev-board-2-independent-CAN2-0-CAN-FD-p-5377.html)
- [Wio E5 CAN FD dev board](https://www.seeedstudio.com/LoRa-E5-CAN-FD-dev-kit-CANBUS-p-5398.html)


## License

```
MIT License

Copyright (c) 2018 @ Longan Labs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contact us

If you have any question, please feel free to contact [info@longan-labs.cc](info@longan-labs.cc)
