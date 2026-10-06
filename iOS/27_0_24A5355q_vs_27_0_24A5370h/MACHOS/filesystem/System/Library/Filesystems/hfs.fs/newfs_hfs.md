## newfs_hfs

> `/System/Library/Filesystems/hfs.fs/newfs_hfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x102f` | `0xff1` | **`-0x3e`** |
| `__TEXT.__text` | `0x3198` | `0x315c` | **`-0x3c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-747.0.0.0.0
+748.0.0.0.0

-  CStrings:  122
+  CStrings:  121
Functions:
~ sub_100000780 : 5428 -> 5368
~ sub_1000031e8 -> sub_1000031ac : 220 -> 216
~ sub_100003398 -> sub_100003358 : 68 -> 72
CStrings:
+ "%s: block size %d is too small for %lld sectors"
- "%s: block size is too small for %lld sectors"
- "Error: Disk Device is too big (%llu sectors, %d bytes per sector"
```
