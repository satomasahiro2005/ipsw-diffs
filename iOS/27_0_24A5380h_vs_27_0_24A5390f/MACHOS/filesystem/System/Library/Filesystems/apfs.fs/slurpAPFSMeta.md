## slurpAPFSMeta

> `/System/Library/Filesystems/apfs.fs/slurpAPFSMeta`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37c14` | `0x37e18` | **`+0x204`** |
| `__TEXT.__cstring` | `0x903f` | `0x911a` | **`+0xdb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3283.0.9.502.1
+3283.0.13.0.0

-  CStrings:  774
+  CStrings:  778
Functions:
~ sub_1000097c0 : 596 -> 640
~ sub_10001bbdc -> sub_10001bc08 : 632 -> 636
~ sub_100021a84 -> sub_100021ab4 : 4156 -> 4168
~ sub_100022e34 -> sub_100022e70 : 3496 -> 3520
~ sub_100026744 -> sub_100026798 : 172 -> 168
~ sub_1000328d0 -> sub_100032920 : 1204 -> 1640
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
+ "apfs_sanity_check"
```
