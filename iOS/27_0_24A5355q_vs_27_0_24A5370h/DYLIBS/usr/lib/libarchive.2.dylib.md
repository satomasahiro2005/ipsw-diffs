## libarchive.2.dylib

> `/usr/lib/libarchive.2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2c60` | `0xe29c8` | **`-0x298`** |
| `__AUTH_CONST.__auth_got` | `0x880` | `0x888` | **`+0x8`** |

### Other Changes

```diff

-178.0.0.0.0
+182.0.0.0.0

-  Symbols:   2521
+  Symbols:   2522
Symbols:
+ _copyfile_state_free
Functions:
~ _cleanup : 240 -> 228
~ _archive_wstring_append : 196 -> 192
~ _archive_wstring_append_from_mbs : 536 -> 532
~ _lzx_decode_init : 1144 -> 1140
~ _lzx_decode_blocks : 3296 -> 3292
~ _lzx_make_huffman_table : 912 -> 908
~ _Bcj2_Decode : 2608 -> 2604
~ _read_PackInfo : 852 -> 848
~ _read_CodersInfo : 1200 -> 1196
~ _read_Folder : 2232 -> 2224
~ _init_decompression : 3428 -> 3404
~ _setup_sparse : 532 -> 520
~ _make_fflags_entry : 792 -> 656
~ _copy_metadata : 376 -> 408
~ _create_tempdatafork : 304 -> 336
~ _fixup_appledouble : 696 -> 716
~ _iso9660_free : 560 -> 552
~ _zisofs_write_to_temp : 1148 -> 1144
~ _isoent_alloc_path_table : 328 -> 312
~ _isoent_collect_dirs : 300 -> 296
~ _isoent_make_path_table_2 : 524 -> 520
~ _calculate_path_table_size : 372 -> 364
~ _idr_register : 264 -> 260
~ __write_path_table : 896 -> 884
~ _lookup_name : 548 -> 512
~ _blake2s_init_param : 160 -> 156
~ _blake2s_compress : 18468 -> 18464
~ ___archive_check_child : 252 -> 244
~ _Ppmd8_MakeEscFreq : 380 -> 372
~ _register_CE : 868 -> 864
~ _synthesize_ino_value : 536 -> 528
~ _append_entry_w : 1700 -> 1684
~ _archive_acl_from_text_w : 3296 -> 3240
~ _archive_acl_from_text_l : 3288 -> 3232
~ _add_owner_id : 552 -> 544
~ _make_time : 1020 -> 1016
~ _use_data : 248 -> 244
~ _create_decode_tables : 1060 -> 1048
~ _decode_number : 552 -> 548
~ _push_data_ready : 372 -> 368
~ _Ppmd7_DecodeSymbol : 2368 -> 2364
~ _Ppmd7_EncodeSymbol : 2024 -> 2020
~ _Ppmd7_MakeEscFreq : 412 -> 400
~ _compression_name : 180 -> 176
~ _compress_bidder_init : 672 -> 668
~ _archive_string_normalize_D : 6696 -> 6684
~ _archive_string_normalize_C : 9616 -> 9608
~ _lookup_gid : 576 -> 572
~ _lookup_uid : 628 -> 624
~ _archive_write_set_format : 208 -> 204
~ _archive_write_add_filter : 212 -> 208
~ _archive_write_set_format_by_name : 232 -> 228
~ _blake2sp_update : 572 -> 564
~ _blake2sp_final : 480 -> 468
~ _translate_acl : 1040 -> 1032
~ _set_acl : 1752 -> 1744
~ _lzh_make_huffman_table : 2424 -> 2376
~ _lzh_decode_huffman_tree : 260 -> 256
~ _init_winzip_aes_encryption : 732 -> 728
~ _synthesize_ino_value : 536 -> 528
~ _archive_write_add_filter_by_name : 232 -> 228
~ _read_next_symbol : 864 -> 852
~ _new_node : 280 -> 276
~ _add_value : 648 -> 624
~ _make_table_recurse : 600 -> 584
```
