# TWRP device tree for Oukitel K10

## About Device

![OUKITEL K10](http://www.oukitel.com/u_file/images/18_02_01/2b23a7a48b.jpg)

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | Octa-core 2 GHz Mediatek Helio P23
Chipset | MediaTek MT6763T
GPU     | Mali-G71 MP2
architecture | 64 bit
Memory  | 6 GB RAM
Shipped Android Version | 	Android 7.1 Nougat
Storage | 64 GB
Battery | 11000 mAh
Display | 6.0" (15.24 cm)
Screen resolution | 1080 x 2160 pixels
Pixel density | 402 ppi
Screen to body ratio | 70.7 %
Display type | IPS LCD
Aspect ratio | 18:9
Bezelless display | Yes
Primary Camera | 21 MP + 8 MP Samsung 3P3 dual-lens
Secondary Camera | 13 MP + 8 MP dual-lens
Quick charging | Yes
Wifi | Yes Wi-Fi 802.11, a/b/g/n
Bluetooth | v4.2
USB type C | Yes (Doesn`t support micro-USB)
NFC |	Yes
Network support | 4G (doesn't support Indian bands), 3G, 2G
SIM 1 | 4G Bands:FD-LTE 2100(band 1) / 1800(band 3) / 2600(band 7) / 900(band 8) / 800(band 20)3G Bands: UMTS 2100 / 900 MHz2G Bands: GSM 1800 / 1900 / 850 / 900 MHz GPRS:Available EDGE:Available
SIM size | SIM1: Nano, SIM2: Nano (Hybrid)
SIM 2 | 2G Bands: GSM 1800 / 1900 / 850 / 900 MHz GPRS:Available

---

This device tree can be used to build twrp for Oukitel K10


## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_k10-eng
mka recoveryimage
```
