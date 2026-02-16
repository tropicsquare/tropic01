# Frequently Asked Questions

- [What do I need to get started?](#what-do-i-need-to-get-started)
- [What changes when you update TROPIC01's firmware?](#what-changes-when-you-update-tropic01s-firmware)
- [Example: updating TR01-C2P-T301](#example-updating-tr01-c2p-t301)

---

## What do I need to get started?

We recommend starting with the [Python model](https://tropicsquare.github.io/libtropic/latest/tutorials/model/) of the chip to experiment with our SDK, even without physical hardware. The model communicates with the library over TCP, and all your code stays the same—only the transport layer file changes—so whatever you develop and test with the model will execute identically on hardware.

Once you're familiar with the API, [order](https://www.tropicsquare.com/order-devkit) a devboard of your preference and continue with real hardware. More [tutorials](https://tropicsquare.github.io/libtropic/latest/tutorials/) for the model and devboards are available with our official C library [libtropic](https://github.com/tropicsquare/libtropic). For more information about existing devboards, visit the dedicated repository [here](https://github.com/tropicsquare/devboards).


## What changes when you update TROPIC01's firmware?

| Aspect | Before Update | After Update |
|--------|---------------|--------------|
| **Chip Behavior** | Follows old firmware | Follows new firmware |
| **Documentation** | Use old datasheet and API | Use new datasheet and API |
| **Factory Provisioning** | Original configuration | Unchanged |
| **Erratas** | Check original part number | Still check original part number |

List with all firmware versions and related datasheets and API can be found [here](part-numbers.md#firmware-versions).

## Example: Updating TR01-C2P-T301 to firmware 2.0.0:

[TR01-C2P-T301](parts/TR01-C2P-T301.md) Part Number page shows that chip is shipped with initial application firmware 1.0.0 and SPECT firmware 1.0.0. Based on firmware table in [Part Numbers](part-numbers.md#firmware-versions) page, application firmware 2.0.0 is compatible with SPECT firmware 1.0.0, so only application firmware needs to be updated.

After updating to firmware 2.0.0, chip will behave according to datasheet [A.11](../datasheet/ODD_TR01_datasheet_vA_11.pdf) and API [1.4.0](../api/ODU_TR01_user_api_v1_4_0.pdf).

Erratas do not change with firmware update, they are still listed in [TR01-C2P-T301](parts/TR01-C2P-T301.md) Part Number page.
