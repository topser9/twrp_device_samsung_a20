# TWRP Samsung Galaxy A20

# How to compile it:
```
# How-to clone source and device tree:

$ mkdir -p ~/twrp && cd ~/twrp

$ repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
```
# Clone a20 repo
```
$ git clone https://github.com/topser9/twrp_device_samsung_a20.git device/samsung/a20
```
Sync
```
$ repo sync
```
# How-to build:
```
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ lunch omni_a20-eng
$ mka recoveryimage
```
## How to find the image built
```
`$ cd /out/target/product/a20`
```
see recovery.img
```
# Device Tree for Samsung Galaxy A20 (SM-A205F/DS)

Device Tree Made by topser99
```
![Galaxy A20](https://fdn2.gsmarena.com/vv/bigpic/samsung-galaxy-a20.jpg "Galaxy A20")

# Specs
|---------------------------------------------------------------------------------|
|      Component        |          Specification                                  |
|:----------------------|:--------------------------------------------------------|
| Dimensions            | 158.4 x 74.7 x 7.8 mm (6.24 x 2.94 x 0.31 in)           |
| Weight                | 169 g (5.96 oz)                                         |
| Type                  | Super AMOLED                                            |
| Size                  | 6.4 inches, 100.5 cm2 (~85.0% screen-to-body ratio)     |
| Resolution            | 720 x 1560 pixels, 19.5:9 ratio (~268 ppi density)      |
| OS                    |  Android 9.0 (Pie), One UI                              |
| Chipset               | Exynos 7884 (14 nm)                                     |
| CPU                   | Octa-core (2x1.6 GHz Cortex-A73 & 6x1.35 GHz Cortex-A53)|
| GPU                   | Mali-G71 MP2                                            |
| Internal              | 32GB 3GB RAM eMMC 5.1                                   |
| USB                   | USB Type-C 2.0, USB On-The-Go                           |
| Battery               | Li-Po 4000 mAh, non-removable                           |
| charging              | Fast charging 15W                                       |
| Status                | Available. Released 2019, April 05                      |
|---------------------------------------------------------------------------------|
