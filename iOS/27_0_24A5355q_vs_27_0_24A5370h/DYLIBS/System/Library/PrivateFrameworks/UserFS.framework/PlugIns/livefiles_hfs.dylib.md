## livefiles_hfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_hfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d2a4` | `0x3d388` | **`+0xe4`** |
| `__TEXT.__oslogstring` | `0x5e7a` | `0x5ecc` | **`+0x52`** |

### Other Changes

```diff

-747.0.0.0.0
+748.0.0.0.0

-  CStrings:  746
+  CStrings:  747
Functions:
~ _hfs_scandir : 1936 -> 1964
~ _hfs_readdirattr_internal : 1480 -> 1516
~ _SetAttrIntoStruct : 208 -> 204
~ _unicode_decomposeable : 88 -> 96
~ _utf8_encodestr : 772 -> 768
~ _utf8_decodestr : 1616 -> 1592
~ _unicode_combinable : 88 -> 96
~ _get_btree_nodesize : 92 -> 88
~ _SetBTreeBlockSize : 104 -> 100
~ _ExtendBTreeFile : 1644 -> 1636
~ _hfs_create_attr_btree : 1656 -> 1644
~ _vnode_GetAttrInternal : 592 -> 584
~ _BTIterateRecord : 1400 -> 1396
~ _BTIterateRecords : 1436 -> 1432
~ _cat_findname : 332 -> 328
~ _cat_getdirentries : 1152 -> 1144
~ _getdirentries_callback : 1640 -> 1636
~ _cat_idlookup : 508 -> 504
~ _cat_lookupbykey : 1748 -> 1752
~ _cat_getentriesattr : 776 -> 784
~ _cat_resolvelink : 496 -> 488
~ _getbsdattr : 568 -> 564
~ _validate_dir_move : 388 -> 384
~ _cat_rename : 1508 -> 1504
~ _getkey : 360 -> 320
~ _catrec_update : 1216 -> 1212
~ _AllocateNode : 432 -> 440
~ _ExtendBTree : 872 -> 868
~ _BTZeroUnusedNodes : 504 -> 500
~ _hfs_GetVolumeUUIDRaw : 396 -> 392
~ _hfs_GetNameFromHFSPlusVolumeStartingAt : 1368 -> 1364
~ _ReadFile : 284 -> 296
~ _hfs_chash_getcnode : 832 -> 824
~ _hfs_chash_getvnode : 380 -> 372
~ _hfs_flushvolumeheader : 4908 -> 4876
~ _raw_readwrite_get_cluster_from_offset : 212 -> 208
~ _raw_readwrite_read_mount : 344 -> 340
~ _raw_readwrite_write_mount : 344 -> 340
~ _raw_readwrite_read : 552 -> 548
~ _raw_readwrite_write : 508 -> 504
~ _raw_readwrite_zero_fill_last_block_suffix : 308 -> 304
~ _hfs_swap_HFSPlusForkData : 68 -> 72
~ _hfs_swap_BTNode : 3172 -> 3168
~ _hfs_swap_HFSPlusBTInternalNode : 4972 -> 4888
~ _lf_hfs_generic_buf_match_range : 240 -> 232
~ _hfs_vnop_getxattr : 2296 -> 2304
~ _read_attr_data : 264 -> 276
~ _hfs_vnop_setxattr : 2996 -> 3008
~ _getmaxinlineattrsize : 176 -> 172
~ _write_attr_data : 264 -> 276
~ _remove_attribute_records : 976 -> 980
~ _free_attr_blks : 172 -> 188
~ _file_attribute_exist : 252 -> 248
~ _hfs_vnop_listxattr : 772 -> 768
~ _hfs_removeallattr : 424 -> 420
~ _journal_open : 3724 -> 3768
~ _replay_journal : 5984 -> 6340
~ _journal_create : 1604 -> 1648
~ _end_transaction : 4480 -> 4508
~ _journal_kill_block : 1084 -> 1092
~ _hfs_lockfour : 556 -> 560
~ _hfs_unlockfour : 420 -> 424
~ _hfs_fork_release : 336 -> 324
~ _SearchExtentFile : 452 -> 444
~ _FlushExtentFile : 148 -> 144
~ _CreateExtentRecord : 272 -> 264
~ _UpdateExtentRecord : 408 -> 404
~ _TruncateFileC : 748 -> 768
~ _HeadTruncateFile : 1276 -> 1300
~ _FindExtentRecord : 492 -> 488
~ _DeleteExtentRecord : 196 -> 188
~ _NodesAreContiguous : 384 -> 392
~ _ReleaseExtents : 172 -> 184
~ _FastUnicodeCompare : 232 -> 224
~ _GetEmbeddedFileID : 272 -> 260
~ _ConvertUnicodeToUTF8Mangled : 428 -> 456
~ _hfs_trim_callback : 100 -> 108
~ _BlockMarkFreeInternal : 944 -> 948
~ _MetaZoneFreeBlocks : 240 -> 236
~ _hfs_release_reserved : 248 -> 252
~ _LFHFS_Read : 792 -> 788
~ _LFHFS_Write : 1592 -> 1588
~ _LFHFS_StreamRead : 792 -> 788
~ _hfs_remove_orphans : 2168 -> 2164
~ _hfs_MountHFSPlusVolume : 3448 -> 3432
~ _ReleaseMetaFileVNode : 136 -> 132
~ _hfs_systemfile_lock : 448 -> 436
~ _hfs_vnop_blockmap : 1220 -> 1216
~ _hfs_prepare_release_storage : 192 -> 188
~ _do_hfs_truncate : 1008 -> 1004
~ _hfs_vnop_preallocate : 964 -> 960
~ _InsertLevel : 1192 -> 1208
~ _RotateLeft : 984 -> 960
~ _DeleteRecord : 300 -> 284
~ _DeleteOffset : 104 -> 88
~ _hfs_fsync : 612 -> 596
~ _hfs_removefile : 2144 -> 2140
~ _hfs_vnop_readlink : 696 -> 692
~ _hfs_vnop_symlink : 952 -> 948
~ _hfs_unlink : 1284 -> 1280
~ _hfs_makelink : 2236 -> 2256
CStrings:
+ "jnl: replay_journal: block number 0x%llx out of range (device has 0x%llx blocks)\n"
```
