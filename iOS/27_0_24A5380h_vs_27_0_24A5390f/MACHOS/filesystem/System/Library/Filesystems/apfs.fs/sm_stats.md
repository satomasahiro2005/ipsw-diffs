## sm_stats

> `/System/Library/Filesystems/apfs.fs/sm_stats`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43e4c` | `0x44058` | **`+0x20c`** |
| `__TEXT.__cstring` | `0xcd2b` | `0xce18` | **`+0xed`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3283.0.9.502.1
+3283.0.13.0.0

-  CStrings:  1047
+  CStrings:  1051
Functions:
~ sub_100005110 : 1204 -> 1640
~ sub_10000d2b4 -> sub_10000d468 : 4156 -> 4168
~ sub_10000e664 -> sub_10000e824 : 3496 -> 3520
~ sub_100012704 -> sub_1000128dc : 596 -> 640
~ sub_100024f1c -> sub_100025120 : 516 -> 512
~ sub_10002ab60 -> sub_10002ad60 : 10472 -> 10480
~ sub_10003c844 -> sub_10003ca4c : 632 -> 636
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object 0x%llx first index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx free index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx last index %u larger than max index %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
+ "apfs_sanity_check"
- "%s:%d: %s reap list object 0x%llx first index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx free index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx last index %u larger than max %u\n"
```
