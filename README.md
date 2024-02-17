# Device tree for Blackview N6000 - MT6789 - A12_13

This branch has ***encrypt/decrypt*** files and option to more test with that. 

## Device

Specs [here](https://www.gsmarena.com/blackview_n6000-12432.php)
Description | Specification
-------:|:-------------------------
Shipped Android Version | 12 -- Android 13, DokeOS 3.1
Internal Storage | 256 GB (UFS 2.1)

![Blackview N6000](https://fdn2.gsmarena.com/vv/pics/blackview/blackview-n6000-1.jpg)

#### Big thanks to:

- @SKOCHE
- @lopestom
- [TeamWin](https://github.com/TeamWin) for TWRP SC.

                  ####### generated by lopestom #######
-----
#### Building

```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_N6000-eng
mka vendorbootimage
```
