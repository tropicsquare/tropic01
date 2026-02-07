# Part Numbers

> [!IMPORTANT]
> TROPIC01's behaviour is defined by:
> 1. **Initial firmware (Updateable)** — Application + SPECT firmware versions
> 2. **Factory provisioning (Permanent)** — OTP feature bits + certificate chain
>
> Both information is encoded in Part Number.
> [Read this page](part-number-and-firmware-version.md) to understand impact on lifecycle of your product.

| Part Number | Package | Default Application FW | Default SPECT FW | Status  |
|-------------|---------|------------------------|------------------|---------|
| **[TR01-C2P-T310](parts/TR01-C2P-T310.md)** | QFN32 | 2.0.0 | 1.0.0 | ![STATUS](https://img.shields.io/badge/STATUS-RECOMMENDED_FOR_NEW_DESIGNS-blue) |
| **[TR01-C2P-T301](parts/TR01-C2P-T301.md)** | QFN32 | 1.0.0 | 1.0.0 | ![STATUS](https://img.shields.io/badge/STATUS-AVAILABLE-blue) |
| **[TR01-C2P-T202](parts/TR01-C2P-T202.md)** | QFN32 | 0.5.0 | 0.3.1 | ![STATUS](https://img.shields.io/badge/STATUS-DEPRECATED-red) |
| **[TR01-C2P-T103](parts/TR01-C2P-T103.md)** | QFN32 | 0.3.1 | 0.3.1 | ![STATUS](https://img.shields.io/badge/STATUS-DEPRECATED-red) |
| **[TR01-C2P-T101](parts/TR01-C2P-T101.md)** | QFN32 | 0.3.1 | 0.3.1 | ![STATUS](https://img.shields.io/badge/STATUS-DEPRECATED-red) |
| **[TR01-B2S-T005](parts/TR01-B2S-T005.md)** | B2S | 0.2.0 | 0.3.1 |  ![STATUS](https://img.shields.io/badge/STATUS-DEPRECATED-red) |


## Firmware Versions

Table contains documentation for all released firmwares.

TROPIC01 chips are typically distributed with older firmware. We recommend use [libtropic](https://github.com/tropicsquare/libtropic) to update to the latest firmware, but be aware that each firmware version has its own datasheet and API version. Also [read this page](part-number-and-firmware-version.md) to understand the impact on lifecycle of your product.

| Firmware | Datasheet | User API | Changes |
|----------|-----------|----------|-------------|
| 2.0.0 | [A.11](../datasheet/ODD_TR01_datasheet_vA_11.pdf) | [1.4.0](../api/ODU_TR01_user_api_v1_4_0.pdf) | TBD |
| 1.0.1 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.3.0](../api/ODU_TR01_user_api_v1_3_0.pdf) | TBD |
| 1.0.0 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.3.0](../api/ODU_TR01_user_api_v1_3_0.pdf) | TBD |
| 0.5.0 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.3.0](../api/ODU_TR01_user_api_v1_3_0.pdf) | TBD |
| 0.4.0 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.2.0](../api/ODU_TR01_user_api_v1_2_0.pdf) | TBD |
| 0.3.1 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.2.0](../api/ODU_TR01_user_api_v1_2_0.pdf) | TBD |
| 0.2.0 | [A.7](../datasheet/ODD_TR01_datasheet_vA_7.pdf) | [1.1.2](../api/ODU_TR01_user_api_v1_1_2.pdf) | Initial, for engineering samples |


## Catalog list

For technical details on what differs between part numbers, see [TROPIC01 Catalog List v2.0](../catalog_list/OD_TR01_catalog_list_2v0.pdf).

## Product change notifications

For a complete list of changes across part numbers and firmware versions, see [TROPIC01 - PCN](https://tropic-ops.atlassian.net/wiki/external/ODVlMjc1ZWQzM2YxNDEwNmJlZGY0NTk4YWIxMDg0NDI).
