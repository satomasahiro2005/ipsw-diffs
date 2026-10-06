## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fb80` | `0x4fd84` | **`+0x204`** |
| `__TEXT.__cstring` | `0x10016` | `0x10104` | **`+0xee`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3283.0.9.502.1
+3283.0.13.0.0

-  CStrings:  1290
+  CStrings:  1294
Functions:
~ sub_100004bf8 : 596 -> 640
~ sub_10001d1c8 -> sub_10001d1f4 : 520 -> 508
~ sub_10002a398 -> sub_10002a3b8 : 1204 -> 1640
~ sub_10002ca68 -> sub_10002cc3c : 10472 -> 10480
~ sub_10003e8ac -> sub_10003ea88 : 632 -> 636
~ sub_1000439e0 -> sub_100043bc0 : 4156 -> 4168
~ sub_100044d90 -> sub_100044f7c : 3496 -> 3520
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object 0x%llx first index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx free index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx last index %u larger than max index %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
+ "%s:%d: obj is NULL or not apfs object!\n"
+ "apfs_sanity_check"
- "%s:%d: %s reap list object 0x%llx first index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx free index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx last index %u larger than max %u\n"
- "%s:%d: obj is NULL or not apfs object!"
```
