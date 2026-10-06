## livefiles_ntfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_ntfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41ee4` | `0x41f84` | **`+0xa0`** |

### Other Changes

```text
Functions:
~ _ntfs_read_compressed : 3604 -> 3580
~ _ntfs_rl_merge : 2280 -> 2288
~ _ntfs_mapping_pairs_decompress : 1152 -> 1144
~ _ntfs_rl_find_vcn_nolock : 104 -> 124
~ _ntfs_get_size_for_mapping_pairs : 772 -> 792
~ _ntfs_mapping_pairs_build : 1116 -> 1140
~ _ntfs_rl_truncate_nolock : 548 -> 564
~ _ntfs_rl_punch_nolock : 1184 -> 1116
~ _ntfs_rl_read : 588 -> 592
~ _ntfs_rl_write : 740 -> 756
~ _ntfs_attr_lookup : 1512 -> 1516
~ _ntfs_attr_find_vcn_nolock : 356 -> 372
~ _ntfs_attr_find_in_mft_record : 632 -> 640
~ _ntfs_attr_find_in_attrdef : 104 -> 120
~ _ntfs_attr_record_resize : 148 -> 152
~ _ntfs_attr_make_non_resident : 2892 -> 2884
~ _ntfs_attr_extend_initialized : 2228 -> 2236
~ _ntfs_attr_extend_allocation : 8612 -> 8628
~ _ntfs_attr_resize : 4976 -> 4984
~ _ntfs_dir_is_empty : 1916 -> 1912
~ _ntfs_cluster_alloc : 2920 -> 2948
~ _ntfs_cluster_free_from_rl_nolock : 592 -> 600
~ _ntfs_collate_ntofs_ulongs : 116 -> 124
~ _ntfs_extent_mft_record_map_ext : 632 -> 640
~ _ntfs_mft_record_alloc : 13156 -> 13144
~ _ntfs_mft_record_lay_out : 256 -> 252
~ _ntfs_mst_fixup_post_read : 168 -> 164
~ _ntfs_mst_fixup_pre_write : 172 -> 168
~ _ntfs_mst_fixup_post_write : 64 -> 60
~ _ntfs_mft_inode_get : 2824 -> 2828
~ _ntfs_system_inodes_get : 5760 -> 5752
~ _ntfs_boot_sector_is_valid : 432 -> 436
~ _ntfs_windows_hibernation_status_check : 628 -> 636
~ _ntfs_get_nr_set_bits : 468 -> 472
~ _ntfs_logfile_check : 2420 -> 2424
~ _ntfs_index_ctx_relock : 608 -> 616
~ _ntfs_index_move_root_to_allocation_block : 4420 -> 4428
~ _ntfs_index_block_alloc : 1624 -> 1620
~ _ntfs_index_ctx_lock_two : 340 -> 348
~ _ntfs_index_entry_delete : 4456 -> 4452
~ _ntfs_index_block_free : 812 -> 816
~ _ntfs_index_get_entries : 460 -> 456
~ _utf8_transcode : 920 -> 916
~ _ubc_create_upl : 288 -> 300
~ _ubc_upl_abort_range : 372 -> 364
~ _ntfs_attr_list_is_needed : 216 -> 220
~ _ntfs_attr_list_add : 3268 -> 3280
~ _ntfs_attr_list_sync_extend : 3792 -> 3800
~ _ntfs_inode_get : 4620 -> 4616
~ _ntfs_inode_reclaim : 1028 -> 1032
~ _ntfs_index_inode_get : 2248 -> 2244
~ _ntfs_inode_sync : 3996 -> 4000
~ _ntfs_are_names_equal : 160 -> 164
~ _ntfs_ucsncmp : 68 -> 76
~ _ntfs_ucsncasecmp : 116 -> 112
~ _ntfs_collate_names : 200 -> 192
~ _ntfs_upcase_table_generate : 292 -> 308
~ _ntfs_default_sds_entry_init : 196 -> 200
~ _ntfs_default_security_id_init : 196 -> 192
~ _ntfs_vnop_getattr : 1580 -> 1576
~ _ntfs_vnop_inactive : 1944 -> 1940
~ _ntfs_link_internal : 1328 -> 1324
```
