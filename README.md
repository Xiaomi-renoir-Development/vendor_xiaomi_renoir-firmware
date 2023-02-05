# android_vendor_xiaomi_renoir-firmware

Firmware images for Mi 11 Lite 5G (renoir), to include in custom ROM builds.


### How to use?

1. copy firmware images folder

2. Clone this repo to `vendor/xiaomi/renoir-firmware`

3. Include it from `BoardConfig.mk` in device or common tree:

```
# Firmware
-include vendor/xiaomi/renoir-firmware/BoardConfigVendor.mk
```
