# split_sakura

![split_sakura](https://raw.githubusercontent.com/cwrneiro/qmk_firmware/refs/heads/master/keyboards/split_sakura/image/banner.png)


* Keyboard Maintainer: [Augusto Carneiro](https://github.com/cwrneiro)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Compiling:

```sh
qmk compile -kb split_sakura -km default
```

Flashing:

Left:
```sh
qmk flash -kb split_sakura -km default -bl avrdude-split-left
```

Right:
```sh
qmk flash -kb split_sakura -km default -bl avrdude-split-right
```

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader Mode

Short the GND (ground) and RST (reset) pins twice
