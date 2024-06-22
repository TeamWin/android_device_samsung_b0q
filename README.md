# TWRP Device Tree for Samsung Galaxy S22 Ultra

## For Decryption
Not Working for now.

## Kernel source
[Click Here](https://github.com/edward0181/android_kernel_samsung_sm8450)

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Archer3770/twrp_device_samsung_b0q device/samsung/b0q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_b0q-eng
mka recoveryimage
```
