# Auditable Design Resources

TROPIC01 is built on open architecture. The hardware design, firmware source code, and security architecture are available for review and audit.

## Hardware

**[RTL Design](https://github.com/tropicsquare/tropic01-rtl)**  
Register Transfer Level hardware design written in SystemVerilog. Includes testbench, documentation, and verification plans.

## RISC-V Software

**[Application Firmware](https://github.com/tropicsquare/ts-tr01-app)**  
Firmware running on TROPIC01's RISC-V CPU. Includes build system with Docker support and code analysis tools.

**[Software Development Kit](https://github.com/tropicsquare/ts-tr01-sdk)**  
Internal SDK for firmware development. Currently under maintenance and restructuring.

## SPECT (ECC Co-Processor)

**[SPECT Compiler](https://github.com/tropicsquare/ts-spect-compiler)**  
Compiler and instruction set simulator for the SPECT ECC engine.

**[SPECT Firmware](https://github.com/tropicsquare/ts-spect-fw)**  
Firmware for the ECC co-processor. Includes tests, ROM constants, and build scripts.
