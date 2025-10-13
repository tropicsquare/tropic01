# TROPIC01

Welcome to TROPIC01 repository, an auditable Secure Element from [Tropic Square](https://tropicsquare.com/).

This repository provides references to all TROPIC01 related technical materials such as documentation, dev-kits and SW support.

To see what TROPIC01 brings you, or to get samples, see [TROPIC01 Product page](https://tropicsquare.com/tropic01).

## Documentation

### Available Parts

| Part Number (P/N) | Datasheet                                                            |  User API                                                           |
| ----------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------- |
| TR01-B2S-T005     |   [Datasheet - A.7](doc/TR01-B2S-T005/ODD_TR01_datasheet_vA_7.pdf)   | [User API - 1.1.2](doc/TR01-B2S-T005/ODU_TR01_user_api_v1_1_2.pdf)  |
| TR01-C2P-T101     |   [Datasheet - A.10](doc/TR01-C2P-T101/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.2.0](doc/TR01-C2P-T101/ODU_TR01_user_api_v1_2_0.pdf)  |
| TR01-C2P-T103     |   [Datasheet - A.10](doc/TR01-C2P-T103/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.2.0](doc/TR01-C2P-T103/ODU_TR01_user_api_v1_2_0.pdf)  |
| TR01-C2P-T202     |   [Datasheet - A.10](doc/TR01-C2P-T202/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.3.0](doc/TR01-C2P-T202/ODU_TR01_user_api_v1_3_0.pdf)  |
| TR01-C2P-T301     |   [Datasheet - A.10](doc/TR01-C2P-T301/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.3.0](doc/TR01-C2P-T301/ODU_TR01_user_api_v1_3_0.pdf)  |

For details on differences between Part Numbers, reffer to [TROPIC01 - Catalog list - 1.0](doc/catalog_list/OD_TR01_catalog_list_1v0.pdf).

### Application Notes

[ODN_TR01_app_002 - Pin Verification Application Note](doc/application_notes/ODN_TR01_app_002_pin_verif_1v0.pdf)

[ODN_TR01_app_003 - PKI Application Note](doc/application_notes/ODN_TR01_app_003_pki_1v0.pdf)

[ODN_TR01_app_005 - First Pairing Key Application Note](doc/application_notes/ODN_TR01_app_005_first_pairing_key_1v0.pdf)

[ODN_TR01_app_006 - Configuration Objects Application Note](doc/application_notes/ODN_TR01_app_006_config_obj_1v0.pdf)

[ODN_TR01_app_007 - FW Update Application Note](doc/application_notes/ODN_TR01_app_007_fw_update_1v0.pdf)

### Product Change Notifications (PCN)

For list of Product Change Notifications, see:
[TROPIC01 - PCN](https://tropic-ops.atlassian.net/wiki/external/ODVlMjc1ZWQzM2YxNDEwNmJlZGY0NTk4YWIxMDg0NDI).

### Errata

For the list of Errata related to TROPIC01 product, reffer to:
[TROPIC01 - Errata](https://tropic-ops.atlassian.net/wiki/external/MjRmZDY4ZWNlMTYzNGIwZWJkZGQwNzlhM2U5NWQzN2E).

> [!IMPORTANT]
 > Before you start using TROPIC01 in your product, we strongly recommend to do two things first:
 > * Read CHIP ID and TROPIC01's firmware versions and **save printed output for future reference**
 > * Update TROPIC01's both internal firmwares to latest version.

## Software Support

[Software Development Kit (SDK) - libtropic](https://github.com/tropicsquare/libtropic)

[Software Development Kit (SDK) - Rust Version](https://github.com/tropicsquare/libtropic-rs)

[STM32 Integration examples](https://github.com/tropicsquare/libtropic-stm32)

[Linux integration examples](https://github.com/tropicsquare/libtropic-linux)

[Libtropic - Utilities](https://github.com/tropicsquare/libtropic-util)


## Development boards

[Arduino Shield](http://github.com/tropicsquare/tropic01-arduino-shield-hw)

[Raspberry pi Shield](http://github.com/tropicsquare/tropic01-raspberrypi-shield-hw)

[USB stick](http://github.com/tropicsquare/tropic01-stm32u5-usb-devkit-hw)

[Microe Clickboard](https://github.com/tropicsquare/tropic01-mikroe-click-shield-hw)


## Auditable design

This section provides references to TROPIC01 design materials such as Architecture, HW design (RTL) and FW source code.

> [!IMPORTANT]
> Some of the links below may not function yet. TROPIC01 internal design is being gradually published. As the repositories are being published, all the links below will become active.

### Hardware

[RTL Design](https://github.com/tropicsquare/tropic01-rtl)

### RISCV Software

[Application FW](https://github.com/tropicsquare/ts-tr01-app)

[Bootloader](https://github.com/tropicsquare/ts-tr01-boot)

[Software Development Kit](https://github.com/tropicsquare/ts-tr01-sdk)

### SPECT (ECC Engine) Software

[SPECT (ECC Engine) Compiler](https://github.com/tropicsquare/ts-spect-compiler)

[SPECT (ECC Engine) FW](https://github.com/tropicsquare/ts-spect-fw)

