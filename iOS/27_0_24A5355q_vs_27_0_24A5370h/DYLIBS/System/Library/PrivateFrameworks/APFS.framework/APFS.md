## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5384c` | `0x53c24` | **`+0x3d8`** |
| `__TEXT.__cstring` | `0xe625` | `0xe653` | **`+0x2e`** |
| `__AUTH_CONST.__cfstring` | `0x1340` | `0x1360` | **`+0x20`** |

### Other Changes

```diff

-3277.0.0.0.1
+3283.0.0.0.0

-  CStrings:  1394
+  CStrings:  1395
Functions:
~ _authapfs_digest : 572 -> 576
~ _record_failure : 196 -> 204
~ _print_metrics : 1072 -> 1068
~ _authapfs_hexdump_hash : 148 -> 164
~ _fs_delete_supplemental_tree : 236 -> 228
~ _omap_obj_get : 476 -> 468
~ _btree_node_init_phys : 232 -> 236
~ _btree_node_entry_update : 2464 -> 2480
~ _btree_node_has_room : 384 -> 396
~ _bt_shift_or_split : 8704 -> 8708
~ _bt_merge_up : 1552 -> 1556
~ _btree_iterate_nodes : 2548 -> 2688
~ _btree_node_space_free_list_search : 528 -> 520
~ _btree_node_compact : 1212 -> 1208
~ _btree_node_space_free_list_alloc : 284 -> 280
~ _bt_move_entries : 1396 -> 1388
~ _spaceman_update_metazone_alloc_index : 128 -> 144
~ _spaceman_get_metazone_alloc_index : 176 -> 172
~ _spaceman_chunk_zone_info_list_insert : 556 -> 564
~ _spaceman_chunk_zone_info_update : 1264 -> 1280
~ _spaceman_chunk_zone_info_cache_update : 524 -> 604
~ _spaceman_datazone_active : 48 -> 56
~ _spaceman_datazones_destroy : 148 -> 168
~ _spaceman_datazone_load_from_disk : 264 -> 268
~ _spaceman_get_new_chunk_for_allocation_zone : 1636 -> 2264
~ _spaceman_datazone_can_use_chunk : 216 -> 212
~ _spaceman_get_new_chunk_for_allocation_zone_scan_callback : 304 -> 392
~ _spaceman_update_allocation_zone_boundaries : 1184 -> 1188
~ _spaceman_should_avoid_data_allocation_at_block : 260 -> 256
~ _spaceman_clip_extent_to_zones : 456 -> 460
~ _spaceman_chunk_zone_info_load_recent_chunks : 956 -> 1016
~ _nextBaseAndAnyMarks : 2016 -> 1980
~ _doReorder : 116 -> 112
~ _spaceman_init_phys : 296 -> 308
~ _spaceman_destroy : 256 -> 252
~ _spaceman_ip_bm_block_alloc : 264 -> 260
~ _spaceman_free_completed : 2024 -> 2032
~ _spaceman_fq_tree_get : 344 -> 340
~ _spaceman_iterate_free_extents_internal : 3776 -> 3724
~ _spaceman_trim_free_extent_callback : 376 -> 372
~ _spaceman_fq_tree_over_threshold : 212 -> 220
~ _spaceman_alloc : 4152 -> 4144
~ _spaceman_alloc_iterate_chunks : 3488 -> 3492
~ _spaceman_modify_bits : 3408 -> 3372
~ _spaceman_fq_tree_insert : 996 -> 1004
~ _spaceman_fq_trim_list_flush : 356 -> 352
~ __ZN6Base856DecodeEPKcmPhmRm : 652 -> 648
~ _nx_check_checkpoint_map_block : 528 -> 524
~ _nx_mount : 5264 -> 5260
~ _nx_unmount_internal : 312 -> 332
~ __APFSVolumeGetUUIDsOfUnlockRecords : 664 -> 672
~ __APFSVolumeAddUnlockRecordsOrHints : 1172 -> 1152
~ _APFSUniquifyName : 440 -> 460
~ _get_free_extent_hist : 308 -> 304
~ _APFSStatisticsProcessContainer : 1752 -> 1744
~ _APFSStreamRestorePrepare : 576 -> 628
~ _APFSStreamRestoreWrite : 756 -> 780
~ _APFSStreamFingerprintFinish : 504 -> 512
~ _APFSGetFragmentationHistogram : 444 -> 440
~ _APFSGetExclavePath : 660 -> 668
~ ___APFSPurgeExtentIteratorCreate : 876 -> 868
~ _key_val_to_jobj : 2556 -> 2568
~ _xf_init_with_blob : 360 -> 364
~ _xf_get_from_blob : 164 -> 168
~ _btree_node_check : 11552 -> 11432
~ _btree_debug_stats_print : 2480 -> 2476
~ _btree_check_recent_sanity : 1260 -> 1256
~ _nx_check : 10384 -> 10460
~ __ZN16MetricsCompactor6ImportEPKcR7metricsP12Perfcounters : 2728 -> 2720
~ __ZN16MetricsCompactor4ReadEv : 124 -> 120
~ _obj_cache_reset : 532 -> 528
~ _obj_checkpoint_get : 1056 -> 1052
~ _obj_checkpoint_check_for_unknown : 216 -> 212
~ _obj_cache_perform_deferred_updates : 364 -> 360
~ _report_obj_alloc : 280 -> 284
~ _obj_get_callback : 556 -> 524
~ _apfs_get_doc_id_tree_ext : 92 -> 88
~ _nx_reap_list_init_phys : 112 -> 128
~ _nx_metadata_fragmented_extent_list_tree_get : 420 -> 412
~ _spaceman_free_extent_cache_print_stats : 932 -> 960
~ _spaceman_fxc_dropped : 72 -> 76
~ _spaceman_fxc_tree_search : 304 -> 308
~ _spaceman_fxc_update_length : 752 -> 756
~ _spaceman_fxc_tree_node_free : 72 -> 76
~ _spaceman_fxc_tree_delete_at_path : 812 -> 844
~ _spaceman_free_extent_cache_remove : 1176 -> 1148
~ _spaceman_free_extent_cache_search : 1724 -> 1716
~ _spaceman_fxc_bitmap_should_be_searched : 616 -> 608
~ _spaceman_fxc_tree_single_rotate : 296 -> 304
~ _crc32c_init : 164 -> 160
~ _bitmap_range_is_set : 232 -> 224
~ _bitmap_range_is_clear : 236 -> 228
~ _bitmap_set_range : 236 -> 232
~ _bitmap_clear_range : 208 -> 200
~ _bitmap_range_find_desired_or_first_clear_range : 524 -> 516
~ _mounted_device_internal : 244 -> 236
~ _tx_checkpoint_write : 1056 -> 1076
CStrings:
+ "3283"
+ "com.apple.apfs.stream.restore.alloc.estimate.override"
- "3277.0.0.0.1"
```
