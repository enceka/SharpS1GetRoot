# SharpS1GetRoot
For Sharp Android One S1

# How To
## before Android 9 via CVE-2019-2215
  1. Download su98,and use "adb push /data/local/tmp && /data/local/tmp/su98"
  2. backup boot image with "dd"
  3. use magisk application to patch boot.img
  4. use fastboot to flash boot image into boot partition
## Android 9
  1. download boot_patch.img from Release,according to your S1's Build number 
  2. use fastboot to flash boot image into boot partition
