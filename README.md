# SharpS1GetRoot
For Sharp Android One S1 \n

But NOT support the version after 00WW_5_180

# How To
## before Android 9 via CVE-2019-2215
  1. Download su98,and use "adb push /data/local/tmp && /data/local/tmp/su98"
  2. backup boot image with "dd"
  3. use magisk application to patch boot.img
  4. use fastboot to flash boot image into boot partition

## Android 9
  1. download boot_patch.img from Release
  2. try "fastboot boot boot_patch.img" ,if it boot,you can take next step
  3. use fastboot to flash boot image into boot partition

# Credit
  su98 from https://forum.xda-developers.com/t/root-with-cve-2019-2215.3979341/page-9#post-80702567
 
# What's More
  contact me On CoolApk @Enceka or email me enceka@yeah.net

