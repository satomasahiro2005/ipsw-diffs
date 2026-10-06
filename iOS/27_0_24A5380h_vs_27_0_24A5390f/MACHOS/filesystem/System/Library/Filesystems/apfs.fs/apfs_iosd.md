## apfs_iosd

> `/System/Library/Filesystems/apfs.fs/apfs_iosd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33cf0` | `0x33d38` | **`+0x48`** |
| `__TEXT.__cstring` | `0x679d` | `0x67af` | **`+0x12`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3283.0.9.502.1
+3283.0.13.0.0

-  CStrings:  751
+  CStrings:  752
Functions:
~ sub_100006ff4 : 596 -> 640
~ sub_1000173a8 -> sub_1000173d4 : 520 -> 508
~ sub_100026554 -> sub_100026574 : 632 -> 636
~ sub_10002a868 -> sub_10002a88c : 4156 -> 4168
~ sub_10002bc18 -> sub_10002bc48 : 3496 -> 3520
CStrings:
+ "apfs_sanity_check"
```
