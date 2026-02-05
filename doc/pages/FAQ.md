# Frequently Asked Questions

## Table of Contents

- [What do I need to get started?](#what-do-i-need-to-get-started)
- [How do I find erratas for my chip?](#how-do-i-find-erratas-for-my-chip)
- [Which Documentation to Use?](#which-documentation-to-use)

---

### What do I need to get started?

We recommend starting with the Python model of the chip to experiment with our SDK, even without physical hardware. The model communicates with the library over TCP, and all your code stays the same—only the transport layer file changes—so whatever you develop and test with the model will execute identically on hardware.

Once you're familiar with the API, order a devboard of your preference and continue with real hardware. Tutorials for the model and devboards are available with our official C library [libtropic](https://github.com/tropicsquare/libtropic). For more information about existing devboards, visit the dedicated repository [here](https://github.com/tropicsquare/devboards).

### How do I find erratas for my chip?

First, identify your chip's **Part Number** (see [Part Numbers and Firmware Versions](part-number-and-firmware-version.md) for how to read it from your chip). Then, check the [Part Numbers](part-numbers.md) page—each part number lists its associated erratas and known issues.

### Which Documentation to Use?

| Question | Answer |
|----------|--------|
| **How do I use the chip right now?** | Use documentation for your **current firmware version** |
| **What hardware limitations exist?** | Check documentation for your **original part number** |
| **Are there known issues I should know?** | Check erratas for your **original part number** |

---

## Example: Updating TR01-C2P-T301

A TR01-C2P-T301 chip shipped with firmware 1.0.0. After updating to firmware 2.0.0:

- ✅ **Chip now behaves like:** TR01-C2P-T310 (firmware 2.0.0)
- ✅ **Use API documentation from:** TR01-C2P-T310 datasheet
- ⚠️ **Hardware limitations still from:** TR01-C2P-T301 (original part number)
- ⚠️ **Check erratas from:** TR01-C2P-T301

## Best Practices

1. **Always track your original part number** - You'll need it to reference erratas and hardware limitations
2. **Update to the latest firmware** - Newer versions include improvements and bug fixes
3. **Use the current firmware documentation** - It reflects actual chip behavior
4. **Test thoroughly after firmware updates** - Verify your integration still works as expected 