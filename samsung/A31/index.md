## Samsung Galaxy A31 [SM-A315G / a31nseea] - MT6768

You can find the device tree [here](https://github.com/ZillionMuffin/android_device_a31) to build TWRP.
#
![SM-A315G](https://user-images.githubusercontent.com/77107077/147390947-fdfa942d-1d35-44fc-874e-2e5768ff40b6.png)
### How to compile:
! Requires this [file](https://android.googlesource.com/platform/external/avb/+/refs/heads/sdk-release/test/data/testkey_rsa4096.pem) inside /device/samsung/a31
```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a31-eng
make recoveryimage && make bootimage
```
#
**[``OpenSource``](https://mega.nz/file/6p9H2YZL#Q96SamvRQzEuNAQEnt_-lvkqR4Iw-kuy8MuNLS79jXQ)    [``Kernel Source``](https://github.com/ZillionMuffin/android_kernel_samsung_a31)    [``Twrp build Guide``](https://shrp.github.io/#/guide)      [``Documentation``](https://zillionmuffin.github.io/Docs/samsung/A31/)** 
