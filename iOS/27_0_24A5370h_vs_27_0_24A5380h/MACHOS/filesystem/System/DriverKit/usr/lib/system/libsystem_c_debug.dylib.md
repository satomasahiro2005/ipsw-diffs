## libsystem_c_debug.dylib

> `/System/DriverKit/usr/lib/system/libsystem_c_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4214` | `0xc45f0` | **`+0x3dc`** |
| `__TEXT.__auth_stubs` | `0xc00` | `0xbd0` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x600` | `0x5e8` | **`-0x18`** |

### Same-size Content Changes

- `__AUTH.__constrw`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1786.0.0.0.0
+1786.0.1.0.0
Functions:
~ _fts_read : 2008 -> 2016
~ _both_ftw : 1968 -> 1976
~ _getdate : 2568 -> 2576
~ ___xprintf_domain_init : 960 -> 984
~ _register_printf_domain_function : 488 -> 504
~ _register_printf_domain_render : 480 -> 496
~ _uuid_unparse_x : 268 -> 284
~ ___bt_pgin : 1632 -> 1648
~ ___bt_pgout : 1636 -> 1652
~ ___bt_dpage : 1880 -> 1912
~ ___bt_stkacq : 1648 -> 1664
~ ___bt_dleaf : 908 -> 924
~ ___bt_pdelete : 1048 -> 1064
~ ___bt_put : 2032 -> 2040
~ ___bt_search : 764 -> 772
~ ___bt_seqset : 720 -> 736
~ ___bt_split : 3152 -> 3248
~ _bt_rroot : 424 -> 440
~ _bt_broot : 772 -> 812
~ _bt_psplit : 1944 -> 2024
~ ___bt_ret : 916 -> 924
~ ___bt_cmp : 468 -> 484
~ _hash_seq : 1204 -> 1220
~ _hash_access : 1508 -> 1524
~ ___big_insert : 1640 -> 1688
~ ___find_bigpair : 516 -> 540
~ ___big_return : 1032 -> 1048
~ _collect_data : 676 -> 684
~ _collect_key : 532 -> 540
~ ___delpair : 828 -> 844
~ ___split_page : 1108 -> 1140
~ _ugly_split : 1488 -> 1504
~ _putpair : 340 -> 356
~ _squeeze_key : 508 -> 524
~ ___rec_dleaf : 656 -> 672
~ ___rec_iput : 1088 -> 1096
~ ___rec_search : 920 -> 928
~ ___rec_ret : 668 -> 676
~ ___hdtoa : 1200 -> 1204
~ ___s2b_D2A : 428 -> 436
~ __filldir : 1352 -> 1368
~ _link_addr : 956 -> 972
~ _link_ntoa : 512 -> 544
~ ___svfscanf_l : 7708 -> 7716
~ _tzload : 4564 -> 4572
~ _strsignal_r : 628 -> 636
~ _gcvt : 1208 -> 1216
~ ___printf_render_hexdump : 1068 -> 1100
~ ___printf_render_time : 1240 -> 1296
~ _arrayget : 268 -> 276
~ __strfmon : 4540 -> 4548
~ _tre_tnfa_run_backtrack : 8036 -> 8044
```
