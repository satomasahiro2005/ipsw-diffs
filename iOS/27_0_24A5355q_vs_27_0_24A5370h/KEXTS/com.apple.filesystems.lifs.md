## com.apple.filesystems.lifs

> `com.apple.filesystems.lifs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xfb0` | **`+0xfb0`** |
| `__TEXT.__os_log` | `0x1ee5` | `0x1eba` | **`-0x2b`** |
| `__TEXT.__cstring` | `0x29be` | `0x29e6` | **`+0x28`** |
| `__TEXT_EXEC.__text` | `0x20220` | `0x20214` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x7d0` | `0x7d8` | **`+0x8`** |

### Other Changes

```diff

-971.0.0.0.5
+974.0.1.0.2

-  CStrings:  516
+  CStrings:  517
Functions:
~ _sysctlbyname : 296 -> 304
~ sub_fffffff00aa0f9cc -> sub_fffffff00aab3b44 : 256 -> 264
~ _lifs_mount_request : 764 -> 760
~ _lifs_create_request : 396 -> 392
~ _lifs_clonefile_request : 400 -> 396
~ _lifs_mkdir_request : 396 -> 392
~ _lifs_lookup_request : 396 -> 392
~ _lifs_lookupmed_request : 396 -> 392
~ _lifs_lookupsmall_request : 396 -> 392
~ _lifs_setattr_request : 388 -> 376
~ _lifs_getattr_request : 372 -> 360
~ _lifs_setfsattr_request : 516 -> 512
~ _lifs_setfsattr_request_async : 476 -> 468
~ _lifs_open_request : 372 -> 360
~ _lifs_close_request : 372 -> 360
~ _lifs_rmdir_request : 396 -> 392
~ _lifs_symlink_request : 412 -> 400
~ _lifs_link_request : 396 -> 392
~ _lifs_readlink_request : 372 -> 360
~ _lifs_remove_request : 412 -> 400
~ _lifs_access_request : 372 -> 360
~ _lifs_lookup_named_stream_request : 368 -> 356
~ _lifs_create_named_stream_request : 368 -> 356
~ _lifs_remove_named_stream_request : 376 -> 372
~ _lifs_seek_request : 376 -> 372
~ _lifs_cache_open_request : 372 -> 368
~ _lifs_cache_close_request : 336 -> 332
~ _lifs_cache_upgrade_request : 364 -> 352
~ _lifs_getxattr_request : 440 -> 436
~ _lifs_setxattr_request : 812 -> 824
~ _lifs_removexattr_request : 372 -> 360
~ _lifs_listxattr_request : 416 -> 412
~ _lifs_vnop_readdir : 1744 -> 1740
~ sub_fffffff00aa16cac -> sub_fffffff00aabad5c : 1548 -> 1584
~ _lifs_vnop_getattrlistbulk : 1336 -> 1292
~ _lifs_vnop_blockmap : 2476 -> 2432
~ sub_fffffff00aa1a128 -> sub_fffffff00aabe1a4 : 1272 -> 1268
~ _lifs_vnop_allocate : 732 -> 752
~ _lifs_vnop_getxattr : 748 -> 836
~ _lifs_vnop_setxattr : 364 -> 368
~ _lifs_vnop_removexattr : 228 -> 232
~ _lifs_vnop_clonefile : 1156 -> 1176
~ _lifs_submit_io : 1204 -> 1200
~ sub_fffffff00aa1e728 -> _lifs_xattr_check : 172 -> 216
~ __ZN19AppleLIFSUserClient19methodKernelUnmountEPS_PvP25IOExternalMethodArguments : 564 -> 560
~ _lifs_mount : 2176 -> 2200
~ _lifs_unmount : 1264 -> 1284
~ _lifs_query_mountpoint : 1440 -> 1580
~ _lifs_unmount_dangling_all : 440 -> 460
~ _lifs_unmount_dangling_thread : 180 -> 196
~ _lifs_get_supported_xattrs : 304 -> 324
~ sub_fffffff00aa29bb8 -> sub_fffffff00aacddcc : 828 -> 788
~ _lifs_readdir_cached -> sub_fffffff00aace1e0 : 860 -> 740
~ sub_fffffff00aa2b034 -> sub_fffffff00aacf1a8 : 612 -> 596
CStrings:
+ "11122222222222222222222222222222222222222222222222332222122222222222222212111111111222222222222222211212222222112221"
+ "_S_module_bundle_id"
+ "com.apple.private.fskit.moduleBundleID"
+ "get FS_FSATTR_MODULE_BUNDLE_ID got %d, string %s"
- "%s: Got LIFS_DIRCACHE_LIMIT_REACHED with offset > 0, but no matching cookie entry was found"
- "1112222222222222222222222222222222222222222222222233222212222222222222221211111111122222222222222221121222222211222"
- "lifs_readdir_cached"
```
