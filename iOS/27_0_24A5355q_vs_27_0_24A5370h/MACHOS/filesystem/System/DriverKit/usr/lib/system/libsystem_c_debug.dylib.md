## libsystem_c_debug.dylib

> `/System/DriverKit/usr/lib/system/libsystem_c_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4650` | `0xc4214` | **`-0x43c`** |
| `__DATA.__data` | `0x188d` | `0x18ad` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2ed2` | `0x2edf` | **`+0xd`** |

### Same-size Content Changes

- `__AUTH.__constrw`
- `__AUTH.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1782.0.0.0.0
+1786.0.0.0.0

-  Functions: 1742
-  Symbols:   2234
-  CStrings:  828
+  Functions: 1743
+  Symbols:   2236
+  CStrings:  831
Symbols:
+ _fts_ufslinks
+ _ufslike_filesystems
Functions:
~ _generalSlowpath : 2796 -> 2784
~ _shiftRightMPWithRounding : 1296 -> 1288
~ _shiftLeftMP : 380 -> 372
~ _divideMPByMP : 1700 -> 1692
~ ___bt_put : 2040 -> 2032
~ ___bt_split : 3160 -> 3152
~ _swap_header : 1312 -> 1284
~ _alloc_segs : 396 -> 392
~ _swap_header_copy : 1444 -> 1396
~ ___big_insert : 1688 -> 1640
~ ___big_delete : 752 -> 744
~ ___find_last_page : 336 -> 332
~ ___big_return : 1036 -> 1032
~ ___big_split : 972 -> 944
~ _newbuf : 1484 -> 1476
~ ___delpair : 848 -> 828
~ ___split_page : 1124 -> 1108
~ _ugly_split : 1496 -> 1488
~ _putpair : 352 -> 340
~ _squeeze_key : 536 -> 508
~ ___add_ovflpage : 468 -> 452
~ ___get_page : 1104 -> 1076
~ ___put_page : 1236 -> 1180
~ _mpool_open : 436 -> 428
~ ___rec_dleaf : 660 -> 656
~ ___rec_iput : 1096 -> 1088
~ ___quorem_D2A : 1032 -> 1020
~ _bitstob : 436 -> 432
~ ___rshift_D2A : 472 -> 464
~ ___trailz_D2A : 248 -> 244
~ ___mult_D2A : 768 -> 752
~ ___lshift_D2A : 580 -> 576
~ ___cmp_D2A : 492 -> 484
~ ___diff_D2A : 616 -> 608
~ ___b2d_D2A : 648 -> 644
~ ___copybits_D2A : 216 -> 208
~ ___any_on_D2A : 348 -> 344
~ ___sum_D2A : 748 -> 740
~ _fts_build : 2520 -> 2668
+ _fts_ufslinks
~ _setmode : 2672 -> 2620
~ _makeextralist : 784 -> 776
~ __collate_wxfrm : 1104 -> 1092
~ __collate_sxfrm : 1284 -> 1272
~ _setlocale : 1804 -> 1744
~ _currentlocale : 344 -> 336
~ _loadlocale : 844 -> 836
~ _wctrans : 284 -> 276
~ _wctype_l : 452 -> 444
~ _MCGetMsg : 712 -> 708
~ _loadSet : 888 -> 884
~ _fgetws_l : 908 -> 904
~ _strtonum : 528 -> 524
~ ___vfprintf : 18864 -> 18784
~ _io_print : 196 -> 192
~ ___vfwprintf : 18452 -> 18372
~ _io_print : 196 -> 192
~ _grouping_print : 476 -> 468
~ ___vfwscanf : 7016 -> 7012
~ _parsefloat : 2112 -> 2096
~ _wmemstream_write : 568 -> 564
~ _wmemstream_grow : 336 -> 332
~ _tzload : 4568 -> 4564
~ _timesub : 1888 -> 1872
~ _leapcorr : 164 -> 160
~ _wcscoll_l : 2124 -> 2100
~ ___atexit_init : 152 -> 148
~ _atexit_register : 424 -> 420
~ ___cxa_finalize_ranges : 768 -> 764
~ _parse_long_options : 1808 -> 1732
~ _hsearch : 392 -> 388
~ _r_sort_a : 1868 -> 1844
~ _r_sort_b : 1796 -> 1760
~ _srandom : 304 -> 300
~ _srandomdev : 332 -> 328
~ _initstate : 648 -> 644
~ _setstate : 480 -> 476
~ __owned_ptr_add : 332 -> 324
~ __owned_ptr_delete : 180 -> 172
~ ___unsetenv_locked : 220 -> 216
~ __Read_RuneMagi : 3480 -> 3468
~ __Read_RuneMagi_A : 3520 -> 3444
~ ___printf_comp : 3208 -> 3200
~ _tre_tag_get : 92 -> 88
~ _tre_tag_touch_get : 40 -> 36
~ _tre_compile : 3768 -> 3824
~ _tre_add_tags : 11552 -> 11508
~ _tre_compute_npfl : 3460 -> 3524
~ _tre_purge_regset : 256 -> 252
~ _tre_set_union : 2676 -> 2488
~ _tre_tnfa_run_backtrack : 8052 -> 8036
~ _tre_tag_set : 112 -> 108
~ _tre_minimal_tag_order : 304 -> 288
~ _tre_tag_order_1 : 620 -> 612
~ _tre_tnfa_run_parallel : 7904 -> 7876
~ _tre_parse : 10016 -> 10012
~ _tre_parse_bracket : 1604 -> 1588
~ _tre_expand_macro : 360 -> 348
~ _tre_parse_bracket_items : 3040 -> 3036
~ _tre_search_cnames : 288 -> 284
~ _tre_new_item : 336 -> 332
CStrings:
+ "apfs"
+ "hfs"
+ "nfs"
```
