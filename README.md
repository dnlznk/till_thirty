# till_thirty

[![When is a gift not a gift](https://www.youtube.com/watch?v=dvQyhEt6EXg/0.jpg)](https://www.youtube.com/watch?v=dvQyhEt6EXg "When is a gift not a gift")

[Current keymap](./keymap.pdf)


## Install QMK

[QMK Documentation](https://docs.qmk.fm/)

## Create a new keymap

```shell
qmk new-keymap -kb crkbd/rev1 -km <keymap_name>
```

[Building your first firmware](https://docs.qmk.fm/newbs_building_firmware)

## Compile keymap

```shell
qmk compile -kb crkbd/rev1 -km <keymap_name> -e CONVERT_TO=promicro_rp2040
```

This creates the uf2 file to flash the keyboard.

## Flash keyboard

Press the reset button on the keyboard 2 times.

Drag & drop the uf2 file to the newly connected device.
