# TWRP for the Samsung Galaxy J7 Neo / Core / Nxt

TWRP device tree for Samsung Galaxy J7 Neo / Core / Nxt (`j7velte`), based on the TWRP AOSP 12.1 manifest.

## Build
```bash
source build/envsetup.sh
lunch twrp_j7velte-eng
mka recoveryimage
```
The recovery image is `out/target/product/j7velte/recovery.img`.
