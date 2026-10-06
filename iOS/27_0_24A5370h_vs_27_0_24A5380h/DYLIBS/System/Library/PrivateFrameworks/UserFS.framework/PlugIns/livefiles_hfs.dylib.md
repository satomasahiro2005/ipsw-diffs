## livefiles_hfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_hfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d388` | `0x3d360` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x6e0` | `0x6d8` | **`-0x8`** |

### Other Changes

```diff

-748.0.0.0.0
+749.0.0.0.0

-  Functions: 676
-  Symbols:   645
+  Functions: 677
+  Symbols:   646
Symbols:
+ _hfs_set_summary
Functions:
~ _priortysort : 148 -> 156
~ _cat_lookupbykey : 1752 -> 1760
~ _AllocateNode : 440 -> 428
~ _ReadFile : 296 -> 320
~ _journal_open : 3768 -> 3816
~ _replay_journal : 6340 -> 6220
~ _write_journal_header : 672 -> 668
~ _journal_create : 1648 -> 1636
~ _end_transaction : 4508 -> 4504
~ _journal_is_clean : 1516 -> 1508
~ _FastUnicodeCompare : 224 -> 200
~ _ConvertUnicodeToUTF8Mangled : 456 -> 468
~ _ScanUnmapBlocks : 1136 -> 1072
~ _hfs_release_summary : 132 -> 136
~ _hfs_init_summary : 268 -> 284
~ _BlockFindAny : 960 -> 932
~ _BlockFindContiguous : 1992 -> 1984
~ _hfs_find_summary_free : 160 -> 172
+ _hfs_set_summary
~ _InsertKeyRecord : 412 -> 420
```
