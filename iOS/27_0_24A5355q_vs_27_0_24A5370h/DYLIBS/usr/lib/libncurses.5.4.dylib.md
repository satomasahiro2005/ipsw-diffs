## libncurses.5.4.dylib

> `/usr/lib/libncurses.5.4.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30380` | `0x30764` | **`+0x3e4`** |
| `__TEXT.__unwind_info` | `0x778` | `0x780` | **`+0x8`** |

### Other Changes

```text
Functions:
~ __nc_rootname : 192 -> 208
~ __nc_add_to_try : 348 -> 352
~ __nc_wrap_entry : 856 -> 848
~ __nc_merge_entry : 316 -> 292
~ __nc_align_termtype : 616 -> 628
~ sub_2be4437a8 -> sub_2bf9b77a8 : 448 -> 456
~ sub_2be443968 -> sub_2bf9b7970 : 264 -> 268
~ sub_2be443a70 -> sub_2bf9b7a7c : 840 -> 804
~ sub_2be443f00 -> sub_2bf9b7ee8 : 148 -> 144
~ sub_2be443f94 -> sub_2bf9b7f78 : 424 -> 400
~ sub_2be44413c -> sub_2bf9b8108 : 688 -> 660
~ __nc_captoinfo : 1720 -> 1736
~ sub_2be444d18 -> sub_2bf9b8cd8 : 548 -> 544
~ __nc_infotocap : 2560 -> 2592
~ sub_2be445bac -> sub_2bf9b9b88 : 152 -> 164
~ sub_2be445ca4 -> sub_2bf9b9c8c : 152 -> 160
~ sub_2be445d50 -> sub_2bf9b9d40 : 104 -> 100
~ sub_2be445dd8 -> sub_2bf9b9dc4 : 172 -> 164
~ __nc_tic_expand : 1216 -> 1368
~ __nc_resolve_uses2 : 1660 -> 1696
~ sub_2be447930 -> sub_2bf9bb9d0 : 120 -> 116
~ __nc_get_token : 2544 -> 2612
~ sub_2be4483f4 -> sub_2bf9bc4d4 : 816 -> 808
~ sub_2be448758 -> sub_2bf9bc830 : 188 -> 200
~ sub_2be448dd8 -> sub_2bf9bcebc : 108 -> 112
~ __nc_first_db : 952 -> 972
~ sub_2be44923c -> sub_2bf9bd338 : 172 -> 176
~ __nc_scroll_optimize : 544 -> 520
~ __nc_hash_map : 1288 -> 1240
~ sub_2be449de0 -> sub_2bf9bde98 : 640 -> 608
~ sub_2be44a344 -> sub_2bf9be3dc : 304 -> 308
~ sub_2be44a474 -> sub_2bf9be510 : 228 -> 236
~ __nc_init_keytry : 260 -> 256
~ __nc_init_acs : 680 -> 672
~ sub_2be44afc8 -> sub_2bf9bf060 : 1308 -> 1316
~ sub_2be44bdd8 -> sub_2bf9bfe78 : 1048 -> 1052
~ _waddchnstr : 336 -> 344
~ __nc_wchstrlen : 28 -> 56
~ _wadd_wchnstr : 888 -> 932
~ __nc_baudrate : 104 -> 112
~ __nc_ospeed : 56 -> 64
~ _baudrate : 132 -> 140
~ _setcchar : 316 -> 312
~ _wchgat : 300 -> 296
~ _start_color : 556 -> 544
~ _init_pair : 952 -> 944
~ _wdelch : 204 -> 312
~ _wget_wch : 460 -> 456
~ sub_2be455eac -> sub_2bf9ca004 : 196 -> 204
~ __nc_wgetch : 1740 -> 1736
~ _win_wchnstr : 200 -> 212
~ __nc_insert_wch : 392 -> 404
~ _wins_nwstr : 304 -> 320
~ _winsnstr : 176 -> 172
~ _winnstr : 480 -> 476
~ sub_2be45818c -> sub_2bf9cc308 : 444 -> 452
~ sub_2be458610 -> sub_2bf9cc794 : 964 -> 956
~ sub_2be459f4c -> sub_2bf9ce0c8 : 1944 -> 1960
~ __nc_makenew : 500 -> 508
~ _derwin : 272 -> 292
~ _meta : 140 -> 136
~ _pnoutrefresh : 984 -> 956
~ _wnoutrefresh : 1252 -> 1176
~ __nc_scroll_window : 576 -> 580
~ _delscreen : 528 -> 520
~ __nc_setupscreen : 1528 -> 1532
~ __nc_setup_tinfo : 252 -> 256
~ __nc_format_slks : 416 -> 420
~ __nc_slk_initialize : 584 -> 576
~ sub_2be45f7c4 -> sub_2bf9d3900 : 724 -> 712
~ _tgetent : 1160 -> 1204
~ _tgetstr : 348 -> 356
~ _is_wintouched : 64 -> 72
~ __nc_tparm_analyze : 832 -> 828
~ sub_2be46114c -> sub_2bf9d52b4 : 5904 -> 5944
~ _tputs : 636 -> 648
~ __nc_timed_wait : 700 -> 692
~ _unget_wch : 268 -> 264
~ _wvline : 424 -> 416
~ _wvline_set : 324 -> 316
~ __nc_init_wacs : 320 -> 328
~ _wsyncup : 152 -> 148
~ _mvderwin : 216 -> 236
~ _wsyncdown : 200 -> 192
~ _dupwin : 364 -> 360
~ __nc_first_name : 204 -> 192
~ __nc_name_match : 176 -> 168
~ __nc_parse_entry : 6152 -> 6228
~ __nc_init_termtype : 252 -> 244
~ __nc_read_termtype : 2124 -> 2168
~ sub_2be467d08 -> sub_2bf9dbef0 : 96 -> 100
~ sub_2be467d68 -> sub_2bf9dbf54 : 276 -> 272
~ __nc_read_termcap_entry : 836 -> 856
~ _resizeterm : 344 -> 352
~ sub_2be468904 -> sub_2bf9dcb08 : 388 -> 404
~ sub_2be4692e4 -> sub_2bf9dd4f8 : 180 -> 172
~ sub_2be469538 -> sub_2bf9dd744 : 208 -> 232
~ __nc_screen_resume : 412 -> 392
~ sub_2be46a01c -> sub_2bf9de22c : 208 -> 204
~ sub_2be46a0ec -> sub_2bf9de2f8 : 884 -> 928
~ sub_2be46a460 -> sub_2bf9de698 : 5432 -> 5608
~ sub_2be46c8dc -> sub_2bf9e0bc4 : 464 -> 460
~ sub_2be46d4c8 -> sub_2bf9e17ac : 524 -> 528
~ sub_2be46d6d4 -> sub_2bf9e19bc : 1120 -> 1132
~ sub_2be46dcac -> sub_2bf9e1fa0 : 556 -> 528
~ sub_2be46df90 -> sub_2bf9e2268 : 1368 -> 1412
~ sub_2be46e60c -> sub_2bf9e2910 : 588 -> 596
~ _wresize : 908 -> 932
~ sub_2be46ec6c -> sub_2bf9e2f90 : 244 -> 264
~ __nc_write_entry : 904 -> 916
~ sub_2be46f3e0 -> sub_2bf9e3724 : 2068 -> 2156
~ sub_2be46fc00 -> sub_2bf9e3f9c : 144 -> 156
~ sub_2be46fc90 -> sub_2bf9e4038 : 96 -> 132
~ sub_2be46fcf0 -> sub_2bf9e40bc : 208 -> 240
~ __nc_keyname : 772 -> 764
```
