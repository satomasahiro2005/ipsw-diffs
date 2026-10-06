## livefiles_apfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_apfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb1678` | `0xb19ec` | **`+0x374`** |
| `__TEXT.__oslogstring` | `0x1635c` | `0x16438` | **`+0xdc`** |
| `__TEXT.__cstring` | `0x5c26` | `0x5c33` | **`+0xd`** |

### Other Changes

```diff

-3283.0.9.502.1
+3283.0.13.0.0

-  CStrings:  2239
+  CStrings:  2243
Functions:
~ _nx_check : 22440 -> 22448
~ _apfs_init : 560 -> 604
~ _omap_get : 632 -> 636
~ _spaceman_alloc : 4888 -> 4900
~ _spaceman_alloc_iterate_chunks : 3748 -> 3772
~ _nx_reaper_checkpoint_traverse : 1580 -> 2372
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object 0x%llx first index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx free index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx last index %u larger than max index %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
+ "%s:%d: obj is NULL or not apfs object!\n"
+ "3283.0.13"
+ "apfs_sanity_check"
- "%s:%d: %s reap list object 0x%llx first index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx free index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx last index %u larger than max %u\n"
- "%s:%d: obj is NULL or not apfs object!"
- "3283.0.9.502.1"
```
