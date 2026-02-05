# DevKit Quick Start

This guide covers initial setup steps for TROPIC01 development boards.

## Which DevKit Do I Have?

**TS13 / TS1302 / TS1303 - USB DevKit**  
USB-C development board with STM32 microcontroller acting as USB-to-SPI bridge.

**TS1401 - Arduino Shield**  
Arduino UNO R3-compatible shield. [Hardware files](https://github.com/tropicsquare/tropic01-arduino-shield-hw)

**TS1501 - Raspberry Pi HAT**  
Raspberry Pi GPIO-compatible shield. Supports Pi 3, 4, and 5.

**TS1701 - Mini Module**  
Bare chip on castellated PCB for custom integration.

**MikroE Click Board**  
MikroBus-compatible module.

## First Steps (Every DevKit)

### 1. Check Your Chip

Before anything else, read your chip ID and firmware versions. Save this output somewhere. You'll need it for support requests.

The libtropic-linux and libtropic-stm32 repos include a `show_chip_id_and_fw_ver` example.

### 2. Update Firmware

TROPIC01 ships with factory firmware that might be outdated. Update both Application FW and SPECT FW before testing.

Use the `fw_update` example in the same repos. This ensures compatibility with the SDK.

### 3. Run Examples

The SDK includes [reversible and irreversible examples](https://tropicsquare.github.io/libtropic/latest/get_started/examples/). Reversible operations can be undone; irreversible operations permanently modify chip configuration.

Start with reversible examples to learn the API safely.

## Platform-Specific Guides

**[libtropic SDK Documentation](https://tropicsquare.github.io/libtropic/latest/)** covers setup for each platform.

### USB DevKit (TS1302/TS1303)

**Hardware Files:** [tropic01-stm32u5-usb-devkit-hw](https://github.com/tropicsquare/tropic01-stm32u5-usb-devkit-hw)  
**Code Examples:** [libtropic-linux](https://github.com/tropicsquare/libtropic-linux)  
**Platform Guide:** [Linux Setup](https://tropicsquare.github.io/libtropic/latest/other/supported_host_platforms/linux/)

Connects via USB-C. STM32 acts as USB-to-SPI bridge. Compatible with Linux, macOS, and Windows.

### Arduino Shield (TS1401)

**Hardware Files:** [tropic01-arduino-shield-hw](https://github.com/tropicsquare/tropic01-arduino-shield-hw)  
**Platform Guide:** [Arduino Setup](https://tropicsquare.github.io/libtropic/latest/other/supported_host_platforms/arduino/)

Arduino UNO R3-compatible. Connects via SPI interface.

### Raspberry Pi HAT (TS1501)

**Hardware Files:** [tropic01-raspberrypi-shield-hw](https://github.com/tropicsquare/tropic01-raspberrypi-shield-hw)  
**Code Examples:** [libtropic-linux](https://github.com/tropicsquare/libtropic-linux)  
**Platform Guide:** [Raspberry Pi Setup](https://tropicsquare.github.io/libtropic/latest/other/supported_host_platforms/linux/)

Connects via Raspberry Pi GPIO. Tested on Raspberry Pi OS and Ubuntu. Enable SPI in raspi-config before use.

### MikroE Click Board

**Hardware Files:** [tropic01-mikroe-click-shield-hw](https://github.com/tropicsquare/tropic01-mikroe-click-shield-hw)

Compatible with MikroBus-enabled development boards. Follow the platform guide for your specific host board.

### Mini Module (TS1701)

**Hardware Files:** [ts17-tropic01-mini-pcb](https://github.com/tropicsquare/ts17-tropic01-mini-pcb)

Chip mounted on castellated PCB for direct integration into custom designs. Connect SPI + power per datasheet pinout.

## Command-Line Testing

Once setup is complete, use libtropic-util for quick testing and debugging.

**Tool:** [libtropic-util](https://github.com/tropicsquare/libtropic-util)

This command-line utility lets you send API commands directly to the chip. Useful for testing without writing code.

## What's Next

After your devkit works, explore the SDK documentation:

- **[Integration Examples](https://tropicsquare.github.io/libtropic/latest/get_started/integrating_libtropic/integration_examples/)** - Platform-specific integration guides
- **[API Reference](https://tropicsquare.github.io/libtropic/latest/doxygen/build/html/)** - Complete API documentation
- **[Reversible Examples](https://tropicsquare.github.io/libtropic/latest/get_started/examples/reversible_examples/)** - Safe examples to start with

For custom integration into your product, see [Integration Resources](integration-resources.md).
