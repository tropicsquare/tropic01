# Part Number and Firmware Versions

> ![IMPORTANT]
>
> TROPIC01 is partly software-defined product - the same silicon behaves differently based on firmware version.
> **Factory Provisioning** is permanent
> **Firmware** is updateable and we recommend to keep it updated during the lifecycle of your product.

## Core Concepts of Part Number Encoding

**Part Number** contains information about both **Factory Provisioning** and **initial Firmware versions**.
 If you don't know your Part's Number, you can use tutorial in [libtropic](https://github.com/tropicsquare/libtropic) to read it.

 Part number encodes:

 - **Factory provisioning**
   - Permanent manufacturing configuration (OTP security, hardware features, certificate chain)

 - **Initial Firmware Versions**
   - Application firmware and SPECT firmware are tied together by versions
   - You should follow tutorial in [libtropic](https://github.com/tropicsquare/libtropic) to do firmware update

Read more about the structure of **Part Number** at the beginning of [Catalog List](../catalog_list/OD_TR01_catalog_list_2v0.pdf).

## Released Firmware Versions

| Firmware | Datasheet | User API | Changes |
|----------|-----------|----------|-------------|
| 0.2.0 | [A.7](../datasheet/ODD_TR01_datasheet_vA_7.pdf) | [1.1.2](../api/ODU_TR01_user_api_v1_1_2.pdf) | Initial, for engineering samples |
| 0.3.1 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.2.0](../api/ODU_TR01_user_api_v1_2_0.pdf) | TBD |
| 0.4.0 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.2.0](../api/ODU_TR01_user_api_v1_2_0.pdf) | TBD |
| 0.5.0 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.3.0](../api/ODU_TR01_user_api_v1_3_0.pdf) | TBD |
| 1.0.0 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.3.0](../api/ODU_TR01_user_api_v1_3_0.pdf) | TBD |
| 1.0.1 | [A.10](../datasheet/ODD_TR01_datasheet_vA_10.pdf) | [1.3.0](../api/ODU_TR01_user_api_v1_3_0.pdf) | TBD |
| 2.0.0 | [A.11](../datasheet/ODD_TR01_datasheet_vA_11.pdf) | [1.4.0](../api/ODU_TR01_user_api_v1_4_0.pdf) | TBD |


## Related Resources

- [Part Numbers](part-numbers.md) — Complete overview of all variants
