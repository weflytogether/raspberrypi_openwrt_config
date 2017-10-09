# raspberrypi_openwrt_config

1) install LEDE openwrt image to SD card (http://downloads.lede-project.org/snapshots/targets/brcm2708/bcm2710/)

2) extend default partition using GParted, then run 'e2fsck -f /dev/sdx2; resize2fs /dev/sdx2' to fix fs errors

3) insert SD card to RPi board slot and copy the config files to /dev/config/ after system booted
