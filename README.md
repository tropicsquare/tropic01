# [TROPIC01](https://tropicsquare.com/tropic01)

Welcome to TROPIC01 repository, an auditable Secure Element from [Tropic Square](https://tropicsquare.com/).

This repository provides technical materials for TROPIC01 such as:
- Documentation
- Software support
- Development boards
- Auditable design

## Documentation

[Latest Datasheet](doc/TR01-C2P-T310/ODD_TR01_datasheet_vA_11.pdf)

[Latest User API](doc/TR01-C2P-T310/ODU_TR01_user_api_v1_4_0.pdf)

### Available Parts

| Part Number (P/N) | Datasheet                                                            |  User API                                                           |
| ----------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------- |
| TR01-B2S-T005     |   [Datasheet - A.7](doc/TR01-B2S-T005/ODD_TR01_datasheet_vA_7.pdf)   | [User API - 1.1.2](doc/TR01-B2S-T005/ODU_TR01_user_api_v1_1_2.pdf)  |
| TR01-C2P-T101     |   [Datasheet - A.10](doc/TR01-C2P-T101/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.2.0](doc/TR01-C2P-T101/ODU_TR01_user_api_v1_2_0.pdf)  |
| TR01-C2P-T103     |   [Datasheet - A.10](doc/TR01-C2P-T103/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.2.0](doc/TR01-C2P-T103/ODU_TR01_user_api_v1_2_0.pdf)  |
| TR01-C2P-T202     |   [Datasheet - A.10](doc/TR01-C2P-T202/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.3.0](doc/TR01-C2P-T202/ODU_TR01_user_api_v1_3_0.pdf)  |
| TR01-C2P-T301     |   [Datasheet - A.10](doc/TR01-C2P-T301/ODD_TR01_datasheet_vA_10.pdf) | [User API - 1.3.0](doc/TR01-C2P-T301/ODU_TR01_user_api_v1_3_0.pdf)  |
| TR01-C2P-T310     |   [Datasheet - A.11](doc/TR01-C2P-T310/ODD_TR01_datasheet_vA_11.pdf) | [User API - 1.4.0](doc/TR01-C2P-T310/ODU_TR01_user_api_v1_4_0.pdf)  |

For details on differences between Part Numbers, reffer to [TROPIC01 - Catalog list - 2.0](doc/catalog_list/OD_TR01_catalog_list_2v0.pdf).

### Application Notes

[ODN_TR01_app_002 - Pin Verification Application Note](doc/application_notes/ODN_TR01_app_002_pin_verif_1v0.pdf)

[ODN_TR01_app_003 - PKI Application Note](doc/application_notes/ODN_TR01_app_003_pki_1v2.pdf)

[ODN_TR01_app_005 - First Pairing Key Application Note](doc/application_notes/ODN_TR01_app_005_first_pairing_key_1v0.pdf)

[ODN_TR01_app_006 - Configuration Objects Application Note](doc/application_notes/ODN_TR01_app_006_config_obj_1v1.pdf)

[ODN_TR01_app_007 - FW Update Application Note](doc/application_notes/ODN_TR01_app_007_fw_update_1v1.pdf)

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

[Mini board](https://github.com/tropicsquare/ts17-tropic01-mini-pcb)

## Auditable design

This section provides references to TROPIC01 design materials such as Architecture, HW design (RTL) and FW source code.

### Hardware

[RTL Design](https://github.com/tropicsquare/tropic01-rtl)

### RISCV Software

[Application FW](https://github.com/tropicsquare/ts-tr01-app)

[Software Development Kit](https://github.com/tropicsquare/ts-tr01-sdk)

### SPECT (ECC Engine) Software

[SPECT (ECC Engine) Compiler](https://github.com/tropicsquare/ts-spect-compiler)

[SPECT (ECC Engine) FW](https://github.com/tropicsquare/ts-spect-fw)

