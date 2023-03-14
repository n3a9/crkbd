# crkbd

My keymaps for my crkbd keyboard (3x6 layout).

![SCR-20230313-u6w](https://user-images.githubusercontent.com/7104017/224896578-03c0b825-1491-4161-ba7b-1c090009224d.png)

![SCR-20230313-u7y](https://user-images.githubusercontent.com/7104017/224896583-be003692-3bbe-485d-a526-3686c02b9baa.png)

![SCR-20230313-u87](https://user-images.githubusercontent.com/7104017/224896586-7582e219-ae43-4a17-bfc9-4cecf6d9e793.png)

Currently firmware size is fine: 26204/28672 (91%, 2468 bytes free).

## Compile and flash

Compile with `qmk compile -kb crkbd -km n3a9` and flash with `qmk flash -kb crkbd -km n3a9`.

## Keymap JSON

To generate JSON run `qmk -v c2json -km n3a9 -kb crkbd/rev1 $PATH/qmk_firmware/keyboards/crkbd/keymaps/n3a9/keymap.c --no-cpp`
