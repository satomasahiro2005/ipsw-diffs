## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53f5c` | `0x5426c` | **`+0x310`** |
| `__TEXT.__cstring` | `0xe776` | `0xe85e` | **`+0xe8`** |
| `__TEXT.__unwind_info` | `0x9e0` | `0x9d8` | **`-0x8`** |

### Other Changes

```diff

-3283.0.9.502.1
+3283.0.13.0.0

-  CStrings:  1400
+  CStrings:  1404
Functions:
~ _omap_get : 628 -> 632
~ _spaceman_alloc : 4144 -> 4156
~ _spaceman_alloc_iterate_chunks : 3492 -> 3516
~ _APFSCaptureCreatePreallocFile : 316 -> 408
~ _growCaptureFile : 272 -> 312
~ _APFSCaptureExtendPreallocSizeForFile : 100 -> 212
~ _APFSCaptureSetPreallocSizeForFile : 344 -> 356
~ _nx_check : 10460 -> 10468
~ _apfs_init : 596 -> 640
~ _nx_reaper_checkpoint_traverse : 1200 -> 1636
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object 0x%llx first index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx free index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx last index %u larger than max index %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
+ "3283.0.13"
+ "apfs_sanity_check"
- "%s:%d: %s reap list object 0x%llx first index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx free index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx last index %u larger than max %u\n"
- "3283.0.9.502.1"
```
