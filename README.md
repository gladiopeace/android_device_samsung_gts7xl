## Recovery Device Tree for the Samsung Galaxy Tab S7+ 5G (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_gts7xl-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_gts7xl
