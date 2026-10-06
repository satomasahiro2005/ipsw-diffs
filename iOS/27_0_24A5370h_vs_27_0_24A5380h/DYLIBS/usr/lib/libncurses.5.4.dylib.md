## libncurses.5.4.dylib

> `/usr/lib/libncurses.5.4.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30764` | `0x306e8` | **`-0x7c`** |
| `__AUTH.__data` | `—` | `0x18` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x308` | `0x2f0` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x780` | `0x778` | **`-0x8`** |

### Other Changes

```text
Functions:
~ __nc_rootname : 208 -> 192
~ __nc_add_to_try : 352 -> 344
~ sub_2bf9b7970 -> sub_2bff7b9a8 : 268 -> 284
~ __nc_captoinfo : 1736 -> 1720
~ __nc_infotocap : 2592 -> 2568
~ __nc_resolve_uses2 : 1696 -> 1672
~ __nc_get_token : 2612 -> 2600
~ sub_2bf9bc4d4 -> sub_2bff804d0 : 808 -> 796
~ __nc_first_db : 972 -> 968
~ __nc_hash_map : 1240 -> 1208
~ sub_2bf9be3dc -> sub_2bff823a8 : 308 -> 300
~ sub_2bf9be510 -> sub_2bff824d4 : 236 -> 220
~ __nc_baudrate : 112 -> 120
~ __nc_insert_wch : 404 -> 412
~ _wins_nwstr : 320 -> 304
~ sub_2bf9cc308 -> sub_2bff902bc : 452 -> 440
~ __nc_setupscreen : 1532 -> 1516
~ __nc_tinfo_cmdch : 156 -> 148
~ _slk_set : 816 -> 804
~ _tgetent : 1204 -> 1216
~ _tputs : 648 -> 636
~ __nc_parse_entry : 6228 -> 6200
~ __nc_read_termcap_entry : 856 -> 844
~ _resizeterm : 352 -> 344
~ sub_2bf9dcb08 -> sub_2bffa0a5c : 404 -> 396
~ sub_2bf9dd744 -> sub_2bffa1690 : 232 -> 212
~ sub_2bf9de698 -> sub_2bffa25d0 : 5608 -> 5756
~ __nc_write_entry : 916 -> 908
~ __nc_keyname : 764 -> 780
```
